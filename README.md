
# <Oque é uma função? >

> É um conjunto de códigos nomeados, criados para realizar uma tarefa específica.


# <Como se declara uma função?> 
 Declarar ou definir uma função, consiste no uso da palavra-chave function e depois pelo
-  o nome da função
-  o argumento da função entre ( )
-  O código cujo será realizado entre { }

#### Exemplo: 
```
------------------------------------------------------------------------------------------------------------------------
function boasVindas() {
	console.log(“Seja Bem-Vindo!!”)
}

------------------------------------------------------------------------------------------------------------------------
//Quando essa função ser chamada:

boasVindas();

//vai aparecer a mensagem “Seja Bem-Vindo!!” no browser.

```
# <Tipos de funções>

### Declaration (Declaração da função): 

> Declaration ou declaração da função começa com a palavra-chave (function) em seguida pelo nome dado a função, parênteses para parâmetros e chaves para o corpo da função.
#### Exemplo:
```
------------------------------------------------------------------------------------------------------------------------

function multiplicar(x, y) {
	return x * y;
    }
console.log(multiplicar(10,2));

//quando for executada aparecerá 20

//o que ela faz?

//Ela retorna o produto dos dois números (x * y).
//Depois, o código chama a função com 10 e 2 e mostra o resultado no console.
------------------------------------------------------------------------------------------------------------------------
```
### E ela também pode ser invocada antes de ser declarada no código por causa do *hoisting*.
# O que é hoisting?

 >É um comportamento do JS onde a declaração de variável/var são realocadas para o topo durante a leitura do código, permitindo sua utilização antes da atribuição de valor dessa mesma variável. Que fica registrada como undefined ou indefinido caso ela seja acessada antes de ter sido atribuído um valor.

#### Expression (Expressão da função):

- Expression é uma função que é criada dentro de outra instrução (tipo uma declaração de variável) e vai ser atribuída a uma variável dentro daquela instrução.

#### Exemplo:
```
------------------------------------------------------------------------------------------------------------------------

const somar = function(x, y) {
	return x + y;
}
console.log(somar(2,8))

//Vai aparecer 10 no console

//o que ela faz?

//Cria uma função anônima e a atribui à constante somar.
//Essa função retorna a soma de x e y.
//Depois, ela é chamada com 2 e 8.


------------------------------------------------------------------------------------------------------------------------
```
- Ela só vai ser criada quando a execução do código chegar nela.

### Arrow  (função de Seta):

- Arrow utiliza o meio de encurtar o código, deixar enxuto em uma linha, como se fosse uma seta.

#### Exemplo:
```
------------------------------------------------------------------------------------------------------------------------

const diminuir = (x, y) => x - y;
console.log(diminuir(7,4))

//vai aparecer 3 no console

//o que ela faz?

//Cria uma função arrow.
//Ela recebe x e y e retorna x - y.
//Em seguida, é chamada com 7 e 4.
------------------------------------------------------------------------------------------------------------------------
```
# Principais características e benefícios de usar funções>

- Reutilização de código.
- Organização.
- Legibilidade.
- Manutenção.

## O que dá para fazer com funções?>

- organizar os códigos em blocos separando por tipo de tarefa.

- Páginas Web Interativas.

- Criação e Manutenção de Aplicações: 
