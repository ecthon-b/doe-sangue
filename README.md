<p align="center">
<img src="./public/img/logo.png" alt="Logo Doe Sangue"></img>
</p>

<h3 align = "center"> Doe Sangue - MaratonaDev 3.0</h3>

## O projeto
<hr>
<p>O proejto Doe Sangue é uma sistema para cadastro de doadores de sangue, onde serão armazenados dados (nome, email, tipo sanguíneo) 
desses doadores em um banco de dados.</P>

## Tecnologias
<hr>
<p>
Durante o desenvolvimento desse projeto, foram utilizadas as seguintes tecnoligias:
</p>
- [Node.js](https://nodejs.org/en/)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Aprender/JavaScript)
- [Html](https://tableless.com.br/o-que-html-basico/)
- [CSS](https://www.w3schools.com/css/)
- [Nodemon](https://nodemon.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Nunjucks](https://mozilla.github.io/nunjucks/)

## Banco de Dados
<hr>

Para armazenar os dados dos doadores utilizamos o PostgreSQL, onde criamos o banco chamado **'doe'**, com a tabela chamada **'donors'**.
Segue o código SQL para criar a tabela:
```
CREATE TABLE "public"."donors" (
"id" int4 DEFAULT nextval('donors_id_seq'::regclass) NOT NULL,
"name" text COLLATE "default" NOT NULL,
"email" text COLLATE "default" NOT NULL,
"blood" text COLLATE "default" NOT NULL
)
WITH (OIDS=FALSE);
```




