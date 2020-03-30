SQL no NodeJS
=============

Aqui se encontram alguns dos comandos de terminal utilizados para o presente projeto, sendo bem básico. Outras dúvidas podem ser solucionadas na [documentação do knex](http://knexjs.org).

INSTALAÇÃO E INICIALIZAÇÃO
--------------------------

* instalar _query builder_ __knex__

`$ npm install knex`

* instalar pacote de banco de dados do sqlite

`$ npm install sqlite3`

* iniciar configurações do BD no projeto

Este comando instala no projeto o arquivo _knexfile.js_. Lembrar de alterar nesse arquivo o diretório para salvar dados do BD, dependendo da organização do projeto.

`$ npx knex init`

MIGRATIONS
----------

* criar migrations

`$ npx knex migrate:make <migration_name>`

* executar migrations

`$ npx knex migrate:latest`

* desfazer alterações de uma migration anterior

`$ npx knex migrate:rollback`
