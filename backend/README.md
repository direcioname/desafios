# DESAFIO direciona.me
 
## Instruções
 
- Para solucionar o desafio você deve utilizar [Python](https://python.org/) ou [Node.js](https://nodejs.org).
- A solução final deve estar em um repositório git público, contando com uma documentação que possibilite a execução em qualquer outra máquina.

## O que fazer?

Criar um [web crawler](https://globalad.com.br/blog/o-que-e-crawler/) que colete dados do Instagram(posts e comentários), dada uma hashtag como parâmetro, e armazena os dados em um [banco de dados não relacional](https://www.devmedia.com.br/guia/nosql-e-mongodb/34482). O usuário também deve conseguir pesquisar por uma hashtag já armazenada no banco de dados e visualizar os dados retornados.

## Dicas

Os dados do Instagram podem ser retornados em formato json, para isso, basta colocar o sufixo **?__a=1** no fim da URL, exemplo:

URL de posts contendo a hashtag **#exoticcars**
```
https://www.instagram.com/explore/tags/exoticcars/
```
Mesma URL retornando os dados em json
```
https://www.instagram.com/explore/tags/exoticcars?__a=1
```
## Avaliação

- Entendimento e solução do desafio
- [Modularização](https://pt.wikipedia.org/wiki/Modularidade)
- [Clean Code](https://medium.com/joaorobertopb/1-clean-code-o-que-%C3%A9-porque-usar-1e4f9f4454c6)

## Links úteis

- [Using equests in python](https://www.pythonforbeginners.com/requests/using-requests-in-python)
- [Getting started with python and mongodb](https://www.mongodb.com/blog/post/getting-started-with-python-and-mongodb)
- [JSON formatter](https://jsonformatter.org)
