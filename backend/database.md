#SQL no NodeJS<h1>

##INSTALAÇÃO E INICIALIZAÇÃO<h2>

* instalar _query builder_ __knex__
`$ npm install knex`

* instalar pacote de banco de dados do sqlite
`$ npm install sqlite3`

* iniciar configurações do BD no projeto
 
`$ npx knex init`

Este comando instala no projeto o arquivo _knexfile.js_. Lembrar de alterar nesse arquivo o diretório para salvar dados do BD, dependendo da organização do projeto.

##MIGRATIONS<h2>

* criar migrations
`$ npx knex migrate:make <migration_name>`

* executar migrations
`$ npx knex migrate:latest`

* desfazer alterações de uma migration anterior
`$ npx knex migrate:rollback`
