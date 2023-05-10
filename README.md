# RestApi minottocrm-api
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Minotto01/RestApi_minottocrm-api/blob/main/LICENSE) 

# Sobre o projeto

Criação de uma API construída com base no tutorial "REST API com Spring Boot" do canal [AlgaWorks](https://github.com/algaworks).

A API consiste de um CRM (Gestão de Relacionamento com o Cliente) bastante simples que através do mapeamento objeto-relacional registra o NOME junto da ID de um usuário cliente, em um banco de dados relacional armazenado em memória (Utilizando a dependência H2). Através da ferramenta Postman é possível fazer as requisições que lêem (GET) e registram (POST) as informações na tabela.

## Post
Request no postman para adicionar um nome ao banco de dados.

![Post](https://github.com/Minotto01/assets/blob/main/post.png)

## Get
Request no postman para ler o banco de dados.

![Get](https://github.com/Minotto01/assets/blob/main/get.png)

# Tecnologias utilizadas
- Java
- Spring Boot
- JPA
- Maven
- Postman

## Dependências do Spring
- Spring Web
- Spring Boot DevTools
- Spring Data JPA
- H2 Database
- Lombok

## 

# Como executar o projeto
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/Minotto01/RestApi_minottocrm-api

# entrar na pasta target
cd target

# executar o arquivo jar do projeto
java -jar minottocrm-api-0.0.1-SNAPSHOT.jar
```

# Autor

Gabriel Minotto Ferreira Marta

https://www.linkedin.com/in/gabriel-minotto/
