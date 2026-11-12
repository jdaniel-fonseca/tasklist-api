<div align="center">

# ✅ TaskList API

API REST para gerenciamento de tarefas com Java e Spring Boot.

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

</div>

## Sobre

Criei este projeto para praticar o desenvolvimento de APIs REST com Java e Spring Boot. A ideia é ter uma API de tarefas simples de usar, mas com uma base bem organizada, validações, segurança e testes automatizados.

O projeto ainda está em desenvolvimento, então algumas funcionalidades e configurações podem mudar.

## Tecnologias

- Java 17
- Spring Boot 4
- Spring Web MVC
- Spring Data JPA
- Maven e Lombok
- H2
- PostgreSQL

## Próximos passos

- [ ] Adotar PostgreSQL como banco principal
- [ ] Adicionar Swagger / OpenAPI
- [ ] Implementar autenticação e autorização com Spring Security + JWT
- [ ] Criar testes unitários e de integração
- [ ] Preparar Docker e Docker Compose
- [ ] Automatizar testes e build com GitHub Actions
- [ ] Fazer deploy na AWS

## Como executar

Clone o repositório e execute a aplicação com o Maven Wrapper:

```bash
git clone https://github.com/jdaniel-fonseca/tasklist-api.git
cd tasklist-api
./mvnw spring-boot:run
```

No Windows, substitua `./mvnw` por `mvnw.cmd`. Antes de executar, confira as propriedades de banco e os perfis em `src/main/resources`.

> A configuração de execução pode mudar conforme a migração para PostgreSQL e a inclusão do Docker.

## Autor

[José Daniel](https://github.com/jdaniel-fonseca)
