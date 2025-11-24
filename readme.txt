Tecnologias Utilizadas
- Java 21
- Spring Boot 3.58
- Gradle (Groovy)
- MySQL 8
- Spring Data JPA: Abstração de persistência de dados.
- Lombok
- Bean Validation: Validação de regras de negócio
- Swagger (OpenAPI): Documentação automatizada da API.

Pré-requisitos
- JDK 21 instalado.
- MySQL rodando na porta `3306` nome root e senha 123456
- Banco de dados `padaria_db` com o banco criado o sistema vai se configurar automaticamente.

Como Rodar o Projeto
executar o gradle no intelij ou no terminal do OS com o comando ".\gradlew bootRun"
com a aplicação rodando acesse a interface visual pelo url: http://localhost:8080/swagger-ui/index.html#/