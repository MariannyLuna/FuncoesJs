
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

------------------------------------------------------------------------------------------------------------------------
```
###E ela também pode ser invocada antes de ser declarada no código por causa do hoisting.
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

------------------------------------------------------------------------------------------------------------------------
```
- Ela só vai ser criada quando a execução do código chegar nela.

### Arrow  (função de Seta):

- Arrow utiliza o meio de encurtar o código, deixar enxuto em uma linha, como se fosse uma seta.

#### Exemplo:
```
------------------------------------------------------------------------------------------------------------------------

cost diminuir =  (x,  y)  => x  –  y;


------------------------------------------------------------------------------------------------------------------------
```
# Principais características e benefícios de usar funções>

- Reutilização de código.
- Organização.
- Legibilidade.
- Manutenção.

## O que dá para fazer com funções?>

- organizar os códigos em blocos separando por tipo de tarefa.

* Páginas Web Interativas.

*Criação e Manutenção de Aplicações: 
