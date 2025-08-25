# 🚀 Tarefas API

CRUD de tarefas feito com **Spring Boot 3**, **Spring Data JPA** e **MySQL 8**.

![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?logo=springboot)
![Maven](https://img.shields.io/badge/Maven-Wrapper-C71A36?logo=apachemaven)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql)

> A API expõe endpoints REST para **criar**, **listar**, **buscar por ID**, **atualizar** e **remover** tarefas.

---

## 🔎 Sumário
- [Tecnologias](#-tecnologias)
- [Requisitos](#-requisitos)
- [Configuração](#-configuração)
- [Como rodar](#-como-rodar)
- [Endpoints](#-endpoints)
- [Exemplos (cURL)](#-exemplos-curl)
- [Modelo de Dados](#-modelo-de-dados)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Postman](#-postman)
- [Erros comuns](#-erros-comuns)

---

## 🧰 Tecnologias
- Java 17
- Spring Boot (Web)
- Spring Data JPA (Hibernate)
- MySQL 8
- Maven Wrapper (`mvnw`)

---

## ✅ Requisitos
- **Java 17+** instalado
- **MySQL 8** rodando (`localhost:3306`)
- Banco **`tarefasdb`** criado:
  ```sql
  CREATE DATABASE tarefasdb
    CHARACTER SET utf8mb4
    COLLATE utf8mb4_0900_ai_ci;
# Windows
mvnw spring-boot:run


src
├─ main
│  ├─ java/com/example/tarefas
│  │  ├─ controller/TarefaController.java
│  │  ├─ model/Tarefa.java
│  │  ├─ repository/TarefaRepository.java
│  │  └─ TarefasApplication.java
│  └─ resources
│     ├─ application.properties        # (local, não versionado)
│     └─ application-example.properties
└─ test/java/com/example/tarefas/...
