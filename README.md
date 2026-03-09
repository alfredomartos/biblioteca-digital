# 📚 Biblioteca Digital

Projeto de exemplo utilizado para praticar **Git, GitHub, Docker e trabalho com múltiplos serviços**.

A aplicação representa um sistema simples de biblioteca digital composto por dois serviços principais:

* **book-service** – API responsável pela gestão de livros
* **web-ui** – interface web para consulta dos livros

Os serviços são executados em conjunto através de **Docker Compose**.

---

## 🏗 Estrutura do Projeto

```
biblioteca-digital
│
├── book-service/
│   └── serviço backend da API
│
├── web-ui/
│   └── interface web da aplicação
│
├── docker-compose.yml
└── README.md
```

---

## 🚀 Executar o Projeto

### 1. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd biblioteca-digital
```

### 2. Iniciar os serviços com Docker

```bash
docker-compose up --build
```

---

## 🌐 Serviços

Depois de iniciar os containers:

* **Web UI:** http://localhost:3000
* **API:** http://localhost:8000

---

## 🔧 Tecnologias

* Docker
* Docker Compose
* Python (API)
* JavaScript / Web UI
* Git & GitHub

---

## 🎯 Objetivo do Laboratório

Este projeto é utilizado para praticar:

* criação de repositórios Git
* gestão de branches
* Pull Requests
* resolução automática de Issues
* integração de múltiplos serviços
* utilização de Docker em ambiente de desenvolvimento
