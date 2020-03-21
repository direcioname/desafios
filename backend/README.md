# DESAFIO direciona.me
 
## Instruções
 
- Para solucionar o desafio você deve utilizar Python ou Node.js.
- A solução final deve estar em um repositório git público, contando com uma documentação que possibilite a execução em qualquer outra máquina.

## O que fazer?

Criar um crawler que colete dados do Instagram (posts e comentários), dada uma hashtag como parâmetro, e armazena os dados em um banco de dados não relacional. O programa deverá ter a opção de pesquisa de dados no banco através de uma hashtag específica. 

## Dicas

Os dados do instagram podem ser retornados em formato json, para isso, basta colocar o sufixo **?__a=1** no fim da URL, exemplo:

URL de posts contendo a hashtag **#exoticcars**
```
https://www.instagram.com/explore/tags/exoticcars/
```
Mesma URL retornando os dados em json
```
https://www.instagram.com/explore/tags/exoticcars?__a=1
```

Links úteis:

- [Using equests in python](https://www.pythonforbeginners.com/requests/using-requests-in-python)
- [Getting started with python and mongodb](https://www.mongodb.com/blog/post/getting-started-with-python-and-mongodb)
