#Tutorial<h1>


>Criar depois link para um artigo separado para Banco de Dados
##Banco de Dados<h2>

###SQL no NodeJS<h3>

> Separar por Cabeçalho de segundo nível '<h2>'
> INSTALAÇÃO E INICIALIZAÇÃO
* instalar _query builder_ __knex__
`$ npm install knex`

* instalar pacote de banco de dados do sqlite
`$ npm install sqlite3`

* iniciar configurações do BD no projeto
 
`$ npx knex init`

Este comando instala no projeto o arquivo _knexfile.js_. Lembrar de alterar nesse arquivo o diretório para salvar dados do BD, dependendo da organização do projeto.

> Separar por Cabeçalho de segundo nível '<h2>'
> MIGRATIONS

* criar migrations
`$ npx knex migrate:make <migration_name>`

* executar migrations
`$ npx knex migrate:latest`

* desfazer alterações de uma migration anterior
`$ npx knex migrate:rollback`

