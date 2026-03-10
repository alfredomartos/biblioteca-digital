# 📚 Biblioteca Digital

Projeto de **microserviços** desenvolvido com **Spring Boot + Flask + PostgreSQL + MongoDB**, orquestrado com **Docker Compose**.

---

# 👤 Informações do Aluno

| Campo       | Valor                            |
| ----------- | -------------------------------- |
| **Nome**    | Alfredo Martos                   |
| **Turma**   | Microservices Academy 2026       |
| **Lab**     | Exercício 1 - Biblioteca Digital |
| **Entrega** | 10/03/2026                       |
| **Email**   | alfredo.martos@timwe.com         |

---

# 🏗 Estrutura e Serviços

Sistema composto por **4 serviços**, orquestrados via **Docker Compose**.

| Serviço          | Tecnologia    | Porta | Papel                               |
| ---------------- | ------------- | ----- | ----------------------------------- |
| **web-ui**       | Python Flask  | 5000  | Interface Web                       |
| **book-service** | Spring Boot 3 | 8080  | API REST (Lógica de Negócio)        |
| **postgresql**   | PostgreSQL 15 | 5432  | Base de Dados do Catálogo (SQL)     |
| **mongodb**      | MongoDB 7     | 27017 | Base de Dados de Avaliações (NoSQL) |

---

# 🚀 Como Executar

### 1️⃣ Clonar o repositório

```bash
git clone git@github.com:alfredomartos/biblioteca-digital.git
cd biblioteca-digital
```

### 2️⃣ Subir a stack de serviços

```bash
docker compose up --build
```

---

# 🌐 Verificação

Depois de iniciar os containers:

| Serviço           | URL                             |
| ----------------- | ------------------------------- |
| **API REST**      | http://localhost:8080/api/books |

---

# 🛠 Troubleshooting

### ❗ Erro de conexão com PostgreSQL

Se o **book-service** falhar ao iniciar, pode ser porque o banco ainda não está pronto.

Execute:

```bash
docker compose restart book-service
```

---

# 🎯 Tecnologias Utilizadas

* Java 17
* Spring Boot 3
* Python
* Flask
* Docker
* PostgreSQL
* MongoDB

---

# 📦 Arquitetura

Arquitetura baseada em **microserviços**, com separação clara de responsabilidades:

* **Spring Boot** → API e regras de negócio
* **Flask** → Interface Web
* **PostgreSQL** → Dados estruturados do catálogo
* **MongoDB** → Avaliações e dados flexíveis
* **Docker Compose** → Orquestração do ambiente

---
