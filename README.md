# conceitos-nodeJs
Desafio sobre Conceitos do NodeJs aplicado no Bootcamp GoStack.

POST /repositories: A rota recebe title, url e techs dentro do corpo da requisição. é criado também um id automático usando uuid e também a propriedade Likes, iniciando com 0; 

GET /repositories: Rota que lista todos os repositórios;

PUT /repositories/:id: A rota deve altera apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;

DELETE /repositories/:id: A rota deleta o repositório com o id presente nos parâmetros da rota;

POST /repositories/:id/like: A rota aumenta o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes aumenta em 1;
