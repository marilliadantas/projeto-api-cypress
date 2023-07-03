# Testes de API com Cypress
Neste projeto, utilizei o Cypress para automatizar os testes de API, proporcionando uma estrutura organizada que permite a criação e execução de testes de maneira simples e eficiente. Os testes são escritos em JavaScript, seguindo uma abordagem declarativa e intuitiva, que facilita a manutenção e compreensão do código.

Ferramentas utilizadas:
- VSCode
- Cypress
- FakeRESTApi

Tutorial para iniciar um novo projeto utilizando está estrutura
Dentro da pasta especifica para o projeto:
npm init --yes
Instalar o cypress:
npm i cypress -D cypress @9.1

Somente para o report:
npm i mocha -D
npm i mochawesome -D

Em um terminal execute o comando abaixo para abrir o cypress:
cypress open 
Você pode abrir o projeto utilizando o npx:
npx cypress open

Desafios
- Utilizando a API: Implemente os seguintes cenários:
- GET 
- POST
- PUT 
- DELETE

GET:
Listar todos os livros. 

DELETE: 
Excluir um livro com sucesso.

POST:
Criar um novo livro com sucesso. 

PUT: 
Alterar um livro com sucesso.


