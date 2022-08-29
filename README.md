# mate85-grupo1-sistemas-proap
Trabalho da disciplina MATE85 - T�picos em Sistemas de Informa��o e Web I 

[Documento de vis�o e Requisitos](https://docs.google.com/document/d/1m9wSqd6X_1-cIYyQlSkXVTLkZj8PFWPeTRYjBZ5t95s/edit?usp=sharing)


# Informa��es da API

### Configura��o relacionada ao banco de dados para desenvolvimento local da API

No arquivo `src/main/resources/application.propoerties` adicione as declara��es abaixo:

* spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
* spring.datasource.url=jdbc:mysql://url_db
* spring.datasource.username=nome\_usuario\_db
* spring.datasource.password=senha_db

Configura��o adicional para gera��o das tabelas de forma autom�tica:

* spring.jpa.hibernate.ddl-auto=update
* spring.jpa.hibernate.generateDdl=true

### [Link para documenta��o da API](https://proap-api.herokuapp.com/proap-api/swagger-ui.html#/)