# Web Services com Spring Boot e JPA / Hibernate

Este repositório contém uma API RESTful desenvolvida como parte do Curso Java Completo, focando nos fundamentos e na arquitetura de aplicações back-end modernas.

## 🎯 Objetivos do Projeto

O foco principal deste projeto é implementar um e-commerce básico para treinar as seguintes habilidades práticas:

* Criar um projeto Spring Boot Java[cite: 6].
* Implementar e mapear um modelo de domínio complexo (Relacionamentos 1:N, N:N, etc.).
* Estruturar o sistema seguindo as melhores práticas de camadas lógicas: Resource (Controladores), Service e Repository.
* Configurar um banco de dados de teste em memória (H2) e povoá-lo com dados iniciais (Database Seeding).
* Implementar operações completas de CRUD (Create, Retrieve, Update, Delete).
* Desenvolver um tratamento de exceções personalizado e elegante para a API.

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Java & Spring Boot** 
* **JPA / Hibernate** 
* **Maven** (Gerenciamento de dependências) 
* **Banco de Dados H2** (Perfil de Teste) 
* **MySQL** (Perfil de Desenvolvimento/Produção) 
* **Postman** (Testes de requisições HTTP) 

## 🏗️ Modelo de Domínio

A aplicação foi modelada em torno das seguintes entidades de negócios:
* **User** (Usuário) 
* **Order** (Pedido) e **OrderItem** (Item de Pedido) 
* **Product** (Produto) e **Category** (Categoria) 
* **Payment** (Pagamento) 
* **OrderStatus** (Status do Pedido - Enum) 

## 👨‍💻 Créditos

Projeto construído acompanhando as aulas do Prof. Dr. Nelio Alves (devsuperior.com.br).
