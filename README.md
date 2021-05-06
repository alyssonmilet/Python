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


