# 🚀 Cadastro de Usuários - API REST

API CRUD desenvolvida com Spring Boot para gerenciamento de usuários.
Projeto focado em prática de desenvolvimento backend, integração com banco de dados e boas práticas com JPA.

---

## 🛠️ Tecnologias utilizadas

* Java 21+
* Spring Boot
* Spring Data JPA
* H2 Database
* Maven
* Lombok

---

## ⚙️ Funcionalidades

* ✅ Criar usuário
* 📄 Listar usuários
* 🔍 Buscar usuário por ID
* ✏️ Atualizar usuário
* ❌ Deletar usuário

---

## ▶️ Como executar o projeto

```bash
# Clonar repositório
git clone https://github.com/SEU-USUARIO/SEU-REPO.git

# Entrar na pasta
cd SEU-REPO

# Rodar o projeto
./mvnw spring-boot:run
```

A aplicação estará disponível em:

```
http://localhost:8080
```

---

## 🧪 Banco de dados (H2)

Console disponível em:

```
http://localhost:8080/h2-console
```

Configuração padrão:

* JDBC URL: `jdbc:h2:mem:testdb`
* User: `sa`
* Password: *(vazio)*

---

## 📡 Endpoints da API

### ➕ Criar usuário

POST `/usuarios`

### 📄 Listar usuários

GET `/usuarios`

### 🔍 Buscar por ID

GET `/usuarios/{id}`

### ✏️ Atualizar usuário

PUT `/usuarios/{id}`

### ❌ Deletar usuário

DELETE `/usuarios/{id}`

---

## 📌 Melhorias futuras

* 🔐 Implementar autenticação com Spring Security
* 🐳 Dockerizar aplicação
* 🗄️ Migrar para banco PostgreSQL
* 📄 Documentação com Swagger

---

## 👨‍💻 Autor

## 📚 Créditos

Este projeto foi desenvolvido com base em uma videoaula do canal Javanauta no YouTube, com o objetivo de estudo e prática de desenvolvimento backend com Spring Boot.

Algumas adaptações e ajustes foram feitos durante o desenvolvimento para melhor compreensão dos conceitos.

