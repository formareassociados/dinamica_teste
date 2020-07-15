# dinamica_teste

Nesta dinâmica você deve criar uma aplicação com os requisitos abaixo (utilizando o MERN stack ReactJS, ExpressJS, NodeJS, MongoDB)
* *Plus: utilizar GraphQL e Redux será um diferencial*
* preferencialmente utilizar o create-react-app para desenvolver o front end

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
