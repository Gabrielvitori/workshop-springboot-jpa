# Web Services com Spring Boot e JPA / Hibernate

[cite_start]Este repositório contém uma API RESTful desenvolvida como parte do Curso Java Completo, focando nos fundamentos e na arquitetura de aplicações back-end modernas[cite: 1, 4].

## 🎯 Objetivos do Projeto

O foco principal deste projeto é implementar um e-commerce básico para treinar as seguintes habilidades práticas:

* [cite_start]Criar um projeto Spring Boot Java[cite: 6].
* [cite_start]Implementar e mapear um modelo de domínio complexo (Relacionamentos 1:N, N:N, etc.)[cite: 7].
* [cite_start]Estruturar o sistema seguindo as melhores práticas de camadas lógicas: Resource (Controladores), Service e Repository[cite: 8, 124, 125, 126].
* [cite_start]Configurar um banco de dados de teste em memória (H2) e povoá-lo com dados iniciais (Database Seeding)[cite: 9, 10, 181].
* [cite_start]Implementar operações completas de CRUD (Create, Retrieve, Update, Delete)[cite: 11].
* [cite_start]Desenvolver um tratamento de exceções personalizado e elegante para a API[cite: 11].

## 🛠️ Tecnologias e Ferramentas Utilizadas

* [cite_start]**Java & Spring Boot** [cite: 4, 6]
* [cite_start]**JPA / Hibernate** [cite: 4]
* [cite_start]**Maven** (Gerenciamento de dependências) [cite: 15]
* [cite_start]**Banco de Dados H2** (Perfil de Teste) [cite: 16, 144]
* [cite_start]**MySQL** (Perfil de Desenvolvimento/Produção) [cite: 17, 278]
* [cite_start]**Postman** (Testes de requisições HTTP) [cite: 19]

## 🏗️ Modelo de Domínio

A aplicação foi modelada em torno das seguintes entidades de negócios:
* [cite_start]**User** (Usuário) [cite: 44]
* [cite_start]**Order** (Pedido) e **OrderItem** (Item de Pedido) [cite: 29, 36]
* [cite_start]**Product** (Produto) e **Category** (Categoria) [cite: 22, 32]
* [cite_start]**Payment** (Pagamento) [cite: 51]
* [cite_start]**OrderStatus** (Status do Pedido - Enum) [cite: 54]

## 👨‍💻 Créditos

[cite_start]Projeto construído acompanhando as aulas do Prof. Dr. Nelio Alves (devsuperior.com.br)[cite: 2, 3].
