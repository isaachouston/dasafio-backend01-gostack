Esse desafio foi para praticar o conhecimento dos fundamentos do NodeJS.

Este aplicativo foi desenvolvido para armazenar repositórios, o que permitiu criar, listar, atualizar e remover os repositórios, além de permitir que os repositórios recebessem "Likes".
   
    POST /repositories => Criar um novo repositório.
    GET /repositories => Listar todos os repositórios.
    PUT /repositories/:id => Atualizar repositórios com o mesmo ID recebido pelos parâmetros de solicitação.
    DELETE /repositories/:id => Deletar repositórios com o mesmo ID recebido pelos parâmetros de solicitação.
    POST /repositories/:id/like => Incrementar mais 1 "like" sempre com o mesmo ID recebido.
    
 Tecnologias:

    NodeJS;
    Express;
    Nodemon;
    Yarn;
    Jest;

