# Gerenciador de Tarefas API

## Visão Geral

Esta é uma API simples de Gerenciador de Tarefas construída usando Spring Boot e Spring Data JPA. A API permite criar, listar, atualizar e deletar tarefas armazenadas em um banco de dados H2.

## Tecnologias Utilizadas

- **Java 13**
- **Spring Boot**
- **HTTPie** (para testar a API)

## Comandos para Executar a Aplicação

http GET localhost:8080/tasks - lista tasks;
http POST localhost:8080/tasks --raw="texto" - cria tasks;
http DELETE localhost:8080/tasks - apaga a lista de tasks;
http DELETE localhost:8080/tasks/{indice} - apaga um item especifico da lista de tasks;
http PUT localhost:8080/tasks/{indice} --raw="Atualizar relatório semanal - Completo" - atualiza uma task da lista

Substitua {indice} pelo numero da tarefa que você deseja atualizar ou deletar. Estes comandos devem cobrir todas as operações básicas para gerenciar suas tarefas usando a API

