# Python

## Aqui teremos em leitura fácil, alguns aprendizados de Python.


### Tipos de dados

* Int: Números inteiros;
* Str: Uma String é sequência de caracteres.
* Bool: Dados booleanos (True ou False);
* List: Estrutura de dados para armazenamento de conjunto de elementos;
* Dict: Dicionários;
* Files: Arquivos

### Identação 

Indentar é o recuo do texto em relação a sua margem.

```
variavel = 10
if (variavel > 5):
    print("Código Identado")
```
Ou seja, o texto só será exportado para a tela do usuário, se a variável tiver valor maior que 5.


### Seu primeiro código em Python

Abaixo você pode visualizar a forma de como imprimir uma variável.

```
print("Hello World")
```

### Imprimindo Variáveis
Abaixo podemos visualizar 4 formas de exportar a informação da variável para o usuário.

```
nome = "Felipe"
sobrenome = "Silva"
idade = 38

\\\ Método 01
print(nome, sobrenome, idade)


\\\ Método 02
print("Olá", nome, sobrenome, "sua idade é ", idade, "anos")

\\\ Método 03 (F String)
print(f"Olá {nome} {sobrenome}, sua idade é {idade} anos")


\\\ Método 04 
print("Olá {} {} sua idade é {} anos".format(nome,sobrenome, idade))
```

### Entrada de Dados

Adiciona-se o input() para guardar a informação do usuário em uma variável.
```
nome = input("Digite seu nome: ")
sobrenome = input("Digite seu sobrenome: ")
idade = input("Digite sua idade: ")

print(f"{nome} {sobrenome} tem {idade} anos")

```


### Atribuição de dados

O valor de = (igual), siginifica que o a variável recebe um tal dado. 
Quando temos,

```
nome = "João"
```
Significa que a variável nome, *recebe* o valor João, cujo o tipo de dado é uma String.
Como o Python é uma linguagem dinâmica, não precisamos identificar o tipo de dado. 

Para descobrir qual o tipo de dados, precisamos de somente executar o código abaixo.

~~~Python
v = 10
t = "Teste"
print(type(v))
print(type(t))


#output
<class 'int'>
<class 'str'>
~~~

Uma outra forma de atribuir um dado à uma variável é em uma atribução múltipla.

~~~Python
nome, email, telefone = "Alysson","alysson@email.com","79999999999"
~~~
Não esquecer das vírgulas para separar os dados. 


### Operador Aritmético

Um operador aritmético são utilizados para comparar valores de variáveis ou expressões. Uma expressão aritmética retorna como resultado um valor numérico. 
Abaixo temos os principais operadores aritméticos utilizado no _*Python*_. 


Operação  | Operador | Resultado
--------- | ------ | ------
Adição | + | Soma de dois ou mais valores
Subtração | - | Subtração de dois ou mais valores
Multiplicação | * | Multiplicação de dois ou mais valores
Divisão | / | Divisão 2/7, que retorna valor sem arrendondamento
Exponenciação | ** | Potência entre os valores informados 2²
Divisão Inteira | // | Retorna a parte inteira da divisão
Módulo | % | Retorna o resto da divisão

~~~Python
print(10 + 10)
#output = 20

print(10 - 2)
#output = 8

print(10 * 5)
#output = 50

print(10 / 2 )
#output = 5

print(5 // 2 )
#output = 2

print(5 % 2 )
#output = 1
~~~

### Precedência dos Operadores Aritméticos

Conforme acontece na matemática, alguns operadores aritméticos possuem precedência sobre outros. 

5 + 2 * 8 - 2 

#### Regras de precedência dos operadores matemáticos

Agora que já vimos uma porção de operadores matemáticos, é pertinente falar sobre as regras de precedência que regem a ordem de avaliação das operações dentro de uma expressão matemática. Python segue a mesma convenção usada na matemática; a ordem de avaliação dos operadores, do de maior precedência para o de menor precedência, é a seguinte:

1. Parênteses
2. Exponenciação
3. Multiplicação e divisão, que possuem a mesma precedência
4. Adição e subtração, que possuem a mesma precedência

~~~Python

5 + 2 * 8 - 2 
#output
5 + 16 - 2 --> 19
~~~


