# pucminas-aws-atividade02

## Ferramenta utilizada

Para a execução das requisitções REST foi utilizado o Postman

## APIs utilizadas

A coleção de requisições está dividida em pastas, uma para cada API utilizada.

As APIs usadas foram: Twitter, Pastebin e Marvel Comics.

## Configuração de autenticação

A configuração da autenticação para cada API depende de variáveis globais criadas no Postman.

### Twitter API

Para executar as requisições da API Twitter é preciso criar uma variável twitter_bearer_token e o valor deve ser definido conforme instruções em https://developer.twitter.com/en/docs/authentication/oauth-2-0

### Pastebin

Para executar a requisição para o Pastebin é preciso criar uma variável no Postman com nome pastebin_api_key e o valor deve ser definido de acordo com sua API Key obtida em https://pastebin.com/doc_api#1

### Marvel Comics API

Para executar as requisições da API Marvel é necessário criar duas variáveis no Postman para a API Public Key com nome marvel_public_key e outra para o Hash com o nome marvel_api_hash.

Para ver como obter os valores para essas variáveis, acesse: https://developer.marvel.com/documentation/authorization