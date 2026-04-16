📦 API REST - Sistema de Pedidos
📖 Sobre o projeto

API REST desenvolvida em Java com Spring Boot para gerenciamento de um sistema de pedidos (e-commerce básico), incluindo usuários, produtos, categorias e pedidos.

Este projeto foi construído com foco em aprendizado de APIs REST, JPA/Hibernate e arquitetura em camadas.

🛠️ Tecnologias
Java 17
Spring Boot
Spring Data JPA
Hibernate
H2 Database (teste)
PostgreSQL (produção)
Maven
🚀 Como executar o projeto
🔹 Rodando localmente (H2)
./mvnw spring-boot:run

Acesse:

http://localhost:8080/h2-console
🔹 Configuração com PostgreSQL
spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

spring.jpa.hibernate.ddl-auto=update

📡 Endpoints principais:

👤 Users
GET /users
GET /users/{id}
POST /users
PUT /users/{id}
DELETE /users/{id}

📦 Products
GET /products
GET /products/{id}

📂 Categories
GET /categories
GET /categories/{id}

🧾 Orders
GET /orders
GET /orders/{id}

⚠️ Observação
Projeto desenvolvido para fins de estudo com base em curso. Utilizado para praticar conceitos de APIs REST e persistência de dados com JPA.
