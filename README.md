# Dashboard em Flask

## Sobre o projeto

Este projeto foi desenvolvido com o objetivo de praticar meus conhecimentos em desenvolvimento web com Flask, modelagem de banco de dados e construção de funcionalidades voltadas para visualização e organização de informações.

A proposta foi estruturar um dashboard com autenticação de usuários e consultas de dados, trabalhando principalmente com registros relacionados a pacientes, estados e doenças.

## Objetivo

O objetivo deste projeto foi explorar, na prática, a construção de uma aplicação web com Flask, integrando back-end, banco de dados e lógica de filtragem para exibição de informações.

Durante o desenvolvimento, foquei em aspectos como:

- autenticação de usuários
- organização de dados com SQLAlchemy
- relacionamento entre tabelas
- criação de consultas com filtros
- estruturação de relatórios para exibição em dashboard

## O que foi desenvolvido

Neste projeto, desenvolvi funcionalidades importantes para a base de um sistema analítico, como:

- login de usuários com autenticação por e-mail ou nome de usuário
- verificação segura de senha com criptografia
- cadastro e modelagem de entidades como usuário, perfil, paciente, estado e doença
- relacionamento entre pacientes e doenças
- geração de relatório com agrupamento de dados
- filtragem de informações por estado e doença

## Estrutura principal do projeto

A aplicação foi construída com foco em uma estrutura de back-end organizada, incluindo:

- camada de autenticação de usuários
- modelos de banco de dados com SQLAlchemy
- relacionamento entre tabelas
- consulta de dados para relatórios
- suporte a migrações de banco

## Funcionalidades observadas no código

Com base nos arquivos principais, o projeto contempla:

### Autenticação
- login por e-mail ou username
- validação de senha criptografada
- busca de usuário por id

### Modelagem de dados
- tabela de usuários
- tabela de perfis de acesso
- tabela de estados
- tabela de situação de doença
- tabela de pacientes
- tabela de doenças
- relacionamento muitos para muitos entre pacientes e doenças

### Relatórios
- contagem de pacientes por estado
- filtro opcional por estado
- filtro opcional por doença
- agrupamento de dados para exibição em dashboard

## Tecnologias utilizadas

- Python
- Flask
- Flask SQLAlchemy
- Flask Migrate
- Flask Script
- SQLAlchemy
- Passlib

## Aprendizados

Com esse projeto, consegui praticar e reforçar conhecimentos em:

- desenvolvimento back-end com Flask
- autenticação e validação de usuários
- criptografia de senhas
- modelagem relacional com SQLAlchemy
- criação de consultas com filtros
- estruturação de dados para relatórios
- uso de migrações para banco de dados

## Observações

Este projeto foi importante para ampliar minha visão sobre como estruturar aplicações web com back-end em Python, especialmente em cenários que exigem autenticação, relacionamento entre tabelas e geração de informações consolidadas para visualização em dashboard.

## Autora

Kailany Bughi
