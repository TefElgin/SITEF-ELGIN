## Falha no cadastro da Url de Webhook


##### O retorno abaixo é exibido com frequência durante o credenciamento PIX:

<img src="https://github.com/user-attachments/assets/ffb9a82a-9c49-46b9-b359-59c3694cef00"  width="850">

#### O que é Webhook ?

##### Uma API webhook é um método de comunicação entre aplicações que permite que uma aplicação notifique outra sobre eventos em tempo real. Diferente das APIs tradicionais, onde uma aplicação faz uma solicitação e espera por uma resposta(GET/POST), um webhook funciona de forma inversa: a aplicação que recebe o webhook é notificada automaticamente quando um evento específico ocorre na aplicação que envia o webhook. Em outras palavras, a API é utilizada para validação tempo real, assim que o cliente insere as chaves de integração, a API envia um método com dados para processamento no servidor e já recebe um retorno automaticamente.


#### Como tratar o retorno ?

##### **A comunicação entre a Fiserv e os bancos é realizada através de uma API Webhook. O retorno acima, indica que ocorreu uma falha na validação das credenciais. Nestes casos, é necessário que o cliente entre em contato com seu banco para verificar a liberação/validade das credenciais na Software Express.**
