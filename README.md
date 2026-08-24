# API de Chamados de Suporte

Projeto desenvolvido para praticar conceitos básicos de APIs REST,
métodos HTTP, JSON e códigos de status.

## Objetivo

Simular o gerenciamento de chamados de suporte técnico por meio de uma API.

## Tecnologias utilizadas

- MockAPI
- Insomnia
- JSON
- GitHub

## Estrutura dos chamados

Cada chamado possui:

- id
- cliente
- título
- descrição
- status
- data de abertura
- data de resolução

## Métodos testados

| Método | Endpoint | Função |
|---|---|---|
| GET | /conteudos | Listar chamados |
| GET | /conteudos/:id | Consultar um chamado |
| POST | /conteudos | Criar um chamado |
| PUT | /conteudos/:id | Substituir um chamado |
| PATCH | /conteudos/:id | Atualizar parcialmente |
| DELETE | /conteudos/:id | Excluir um chamado |

## Códigos de status observados

- 200 OK
- 201 Created
- 404 Not Found

## Status permitidos

- Aberto
- Andamento
- Resolvido

## Aprendizados

Neste projeto pratiquei criação e consumo de endpoints REST,
envio de dados em JSON, operações CRUD e interpretação de códigos HTTP.
