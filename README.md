# Melhores práticas para banco de dados
## Nome completo
* SQL: ``VARCHAR(126)``
* Eloquent: ``$table->string('name', 126);``

## Nome de usuário (para login)
* SQL: ``VARCHAR(14)``
* Eloquent: ``$table->string('login', 14);``

## E-mail (para login e outros usos)
* SQL: ``VARCHAR(254)``
* Eloquent: ``$table->string('email', 254);``

## Senha
* SQL: ``VARCHAR(60)``
* Eloquent: ``$table->string('password', 60);``

## Senha

* SQL: ``VARCHAR(10)``
* Eloquent: ``$table->string('crm', 10);``
