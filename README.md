# Banco Digital API

# ************* TESTE - IGNORA ESSA LINHA *********

Estudo de API realizada com Swagger

 Links úteis
  - [Editor Swagger](http://editor.swagger.io/)
  - [Modelando APIs REST com Swagger - Caelum](https://blog.caelum.com.br/modelando-apis-rest-com-swagger/)
  - [Swagger na prática](https://klauslaube.com.br/2018/03/15/swagger-na-pratica.html) - Swagger + Open API Spec
  - [Como interpretar um Swagger](https://medium.com/@ronilsonribeiro/como-interpretar-um-swagger-cdc331b68804)
  - [O que é RESTful? Diferença entre REST e RESTful - DevMedia](https://www.youtube.com/watch?v=7Cbd8WBGrq4)
***
### Modelagem de uma API com Swagger de um banco digital:

Operações da API:
- Cadastro de Correntista
- Edição de Correntista
- Consulta de Correntista
- Abertura de conta-corrente
- Consulta de saldo
- Consulta de extrato
- Cadastro de favorecidos
- Edição de favorecidos
- Remoção de favorecidos
- Realizar transação bancária com favorecidos
- Consultar transação bancárias com favorecidos

URIs:
 - /correntista
    - post
 - /correntista/{correntistaId}
    - get
    - put
 - /cc
    - post
 - /cc/{agencia}/{numero}/{digito}/saldo
    - get
 - /cc/{agencia}/{numero}/{digito}/extrato
    - get
 - /cc/{agencia}/{numero}/{digito}/favorecido
    - post
 - /cc/{agencia}/{numero}/{digito}/favorecido/{favorecidoId}
    - get
    - delete
 - /transacao
    - post
