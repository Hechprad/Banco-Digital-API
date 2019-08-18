# Banco Digital API

Estudo de API realizada com Swagger
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
