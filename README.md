# Melhores práticas para modelagem e implantação de banco de dados
## Nome completo
* SQL: ``VARCHAR(126)``
* Eloquent: ``$table->string('name', 126);``

## Nome de usuário (para login)
* SQL: ``VARCHAR(14)``
* Eloquent: ``$table->string('login', 14);``

## E-mail (para login e outros usos)
* SQL: ``VARCHAR(254)``
* Eloquent: ``$table->string('private_email', 254);``

## Senha
* SQL: ``VARCHAR(60)``
* Eloquent: ``$table->string('password', 60);``
