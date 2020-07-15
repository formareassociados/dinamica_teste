# dinamica_teste

Nesta dinâmica você deve criar uma aplicação com os requisitos abaixo (utilizando o MERN stack ReactJS, ExpressJS, NodeJS, MongoDB)
* *Plus: utilizar GraphQL e Redux será um diferencial*

## Realizar página de login
  * Usar o campo username para realizar o login
  * *Plus: + password para realizar o login e utilizar autenticação*

## Login como Participante:

* Criar ambiente de chat online
  * Deve ter um campo para o usuario inserir a mensagem
  * Algo indentificando na tela qual o usuário está logado
  * Ter um área onde são exibidas as mensagens no seguinte formato:
    'DD/MM/YY - 'username' - HH:MM => 'mensagem'
  * Essa área que as mensagens serão exibidas deve:
   * Mostrar as mensagens de todos os usuários e organizadas das mais novas para as mais velhas de baixo para cima.
   * Esta área deve atualizar sempre que um usuário enviar alguma mensagem
    
## Login como Consultor:

* O consultor então terá os seguintes campos que serão utilizados para organizar as mensagens enviadas e exibir para o consultor:
  * Filtro por username
  * Filtro por data
  * Ordenar por mais recentes/mais antigas
    * *Plus: Apagar mensagens*
* preferencialmente utilizar o create-react-app para desenvolver o front end  

* Crie uma Api Rest em node que irá gerar uma lista com nomes de 117 participantes.

Em Seguida Crie uma rota para ser consumida (essa rota irá retornar seu JSON de participantes).

Atenção não é necessário o uso de banco de dados aqui, mas se utilizar será contado como um plus.

* Criar uma página que consuma a API de cima, listando os participantes e em seguida dividindo todos em 4 grupos de forma aleatória e automática.

Critério para geração de grupos: Alguns terão mais usuários que os outros, pois a divisão não é exata, mas crie de uma forma que o sistema distribua buscando deixar os grupos da forma mais equalitária possível. A divisão deve ser automática, considerando a quantidade de grupos
