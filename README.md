# CineFinder

O CineFinder é uma API REST desenvolvida com Java e Spring Boot que simula um sistema de gerenciamento de filmes.

A aplicação permite realizar operações de cadastro, listagem, busca, atualização e remoção de filmes, aplicando conceitos de desenvolvimento backend e boas práticas como arquitetura em camadas e orientação a objetos.

---
## Colaboração

Este projeto foi desenvolvido em grupo como parte de um trabalho acadêmico.

---

## Tecnologias utilizadas

- Java
- Spring Boot
- Maven
- JPA / Hibernate
- Banco de dados H2

---

## Funcionalidades

- Listar todos os filmes
- Buscar filme por ID
- Buscar filmes por título
- Cadastrar novos filmes
- Atualizar informações
- Remover filmes

---

## Endpoints

| Método | Rota                        | Descrição                  |
|--------|-----------------------------|----------------------------|
| GET    | /api/filmes                | Listar todos os filmes     |
| GET    | /api/filmes/{id}           | Buscar filme por ID        |
| GET    | /api/filmes/buscar?titulo= | Buscar por título          |
| POST   | /api/filmes                | Criar novo filme           |
| PUT    | /api/filmes/{id}           | Atualizar filme            |
| DELETE | /api/filmes/{id}           | Remover filme              |

---

## Como executar o projeto

```bash
git clone https://github.com/Marcos-idk/cinefinder.git
cd cinefinder
./mvnw spring-boot:run
