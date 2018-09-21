[![N|Solid](https://www.onclick.com.br/wp-content/uploads/2016/10/logo.png)](https://www.onclick.com.br/)
# Teste PHP

Ambiente
  - PHP7 (preferencial PHP7.3)
  - Apache2 ou Nginx
  - Mysql ou postgres
  - Docker
  - GIT
  - Composer

# Características
  - Criar projeto onde teremos que cadastrar um cliente e ele pode ter mais de um endereço
  - Pode ser utilizado o framework de preferencia ou apenas PHP puro
  - Criar o banco de dados e anexar o script para criação

# SQL

| Cliente |  |
| ------ | ------ |
| nome | varchar(60) |
| cpf | varchar(14) |
| data_nascimento | date |
| telefone | varchar(15) |
| email | varchar(100) |
| senha | varchar(256) |
| data_cadastro | datetime(now) |

| Cliente Endereço|  |  
| ------ | ------ |
| cliente_id | bigint(20) |
| titulo | varchar(30) |
| rua | varchar(60) |
| numero | varchar(5) |
| complemento | varchar(30) |
| bairro | varchar(60) |    
| cidade | varchar(60) |
| estado | varchar(2) |
| data_cadastro | datetime(now) |   

### Seria legal utilizar
* [Twitter Bootstrap](http://getbootstrap.com) - Interface do usuário para aplicativos da web
* [jQuery](https://jquery.com/) - JQuery
* [PHP](https://php.net) - Orientação a Objeto

### Aqui trablahamos com 
* [phalcon](https://phalconphp.com/pt/)
* [Zend](https://framework.zend.com/)
* [Doctrine](https://www.doctrine-project.org)