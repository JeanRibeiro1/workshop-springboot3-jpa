# Projeto de API REST com Spring Boot e JPA

Este é um projeto de API REST desenvolvido utilizando o framework Spring Boot e a tecnologia JPA (Java Persistence API). A finalidade desta API é fornecer endpoints para acessar e manipular recursos relacionados a um determinado domínio.

## Funcionalidades

A API possui as seguintes funcionalidades:

1. **Criar um novo recurso**: Permite criar um novo registro no sistema fornecendo os dados necessários.

2. **Recuperar um recurso por ID**: Permite buscar um recurso específico com base no seu identificador único.

3. **Listar todos os recursos**: Fornece a lista completa de todos os recursos disponíveis no sistema.

4. **Atualizar um recurso existente**: Permite fazer modificações em um recurso existente.

5. **Excluir um recurso**: Permite remover um recurso do sistema com base no seu ID.

## Endpoints

A API possui os seguintes endpoints para interação:

1. `POST /api/recurso`: Cria um novo recurso no sistema. É necessário enviar os dados corretos no corpo da requisição.

2. `GET /api/recurso/{id}`: Retorna o recurso correspondente ao ID fornecido na URL.

3. `GET /api/recursos`: Retorna todos os recursos disponíveis no sistema.

4. `PUT /api/recurso/{id}`: Atualiza o recurso correspondente ao ID fornecido na URL com os dados enviados no corpo da requisição.

5. `DELETE /api/recurso/{id}`: Remove o recurso correspondente ao ID fornecido na URL.

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **Spring Boot**: Framework Java para agilizar e facilitar o desenvolvimento de aplicações.

- **JPA (Java Persistence API)**: Tecnologia que permite a integração com o banco de dados e o mapeamento objeto-relacional.

- **Banco de Dados**: O projeto está configurado para utilizar um banco de dados (MySQL, PostgreSQL, H2, etc.). A configuração do banco pode ser feita no arquivo `application.properties`.

## Executando o Projeto

Para executar o projeto localmente, siga os passos abaixo:

1. Certifique-se de ter o Java Development Kit (JDK) instalado em sua máquina.

2. Clone este repositório para o seu ambiente de desenvolvimento.

3. Configure o banco de dados no arquivo `application.properties`, se necessário.

4. Execute a aplicação utilizando sua IDE de preferência ou através do seguinte comando no terminal:

```bash
$ ./mvnw spring-boot:run
