# 🚀 Cadastro de Usuários - API REST

API CRUD desenvolvida com Spring Boot para gerenciamento de usuários.

Este projeto foi criado com foco em aprendizado de desenvolvimento backend, utilizando conceitos de API REST, persistência de dados com JPA e testes com banco em memória.

---

## 🛠️ Tecnologias utilizadas

* Java 24
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
# Clonar o repositório
git clone https://github.com/drini11/cadastro-usuario.git

# Entrar na pasta
cd cadastro-usuario

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

* JDBC URL: `jdbc:h2:mem:usuario`
* User: `sa`
* Password: *(vazio)*

---


## 📚 Créditos e aprendizado

Projeto desenvolvido com base em uma videoaula do canal Javanauta no YouTube, com o objetivo de estudo e prática.

---

## 📌 Melhorias futuras

* 🔐 Implementar autenticação com Spring Security
* 🐳 Dockerizar aplicação
* 🗄️ Utilizar banco de dados PostgreSQL
* 📄 Documentação com Swagger

---

## 👨‍💻 Autor

Desenvolvido por João Pedro Pizarro Buldrini
