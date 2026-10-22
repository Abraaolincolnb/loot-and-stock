# 🎒 Loot&Stock

**Sistema de gerenciamento de estoque para pequenos comércios.**

O Loot&Stock é um projeto desenvolvido com o objetivo de facilitar o controle de produtos, movimentações de estoque e pedidos, reunindo informações importantes para ajudar na organização de pequenos negócios.

O projeto também tem como objetivo colocar em prática conhecimentos de desenvolvimento de software, construção de APIs REST, bancos de dados relacionais, testes automatizados e trabalho colaborativo com Git e GitHub.

## 🚀 Funcionalidades

As funcionalidades planejadas para o projeto incluem:

- [ ] **Gerenciamento de produtos:** cadastro, consulta, edição e desativação de produtos.
- [ ] **Categorias:** organização dos produtos por categorias.
- [ ] **Controle de estoque:** registro de entradas e saídas de produtos.
- [ ] **Histórico de movimentações:** consulta das alterações realizadas no estoque.
- [ ] **Gerenciamento de pedidos:** criação e acompanhamento de pedidos.
- [ ] **Validação de estoque:** prevenção de saídas que ultrapassem a quantidade disponível.
- [ ] **Alertas de estoque baixo:** identificação de produtos que precisam de reposição.
- [ ] **Relatórios:** visualização de informações relevantes sobre os produtos e o estoque.
- [ ] **Interface web:** painel para interação com as funcionalidades do sistema.

> As caixas de seleção serão atualizadas conforme as funcionalidades forem implementadas.

## 🛠️ Tecnologias

O projeto será desenvolvido utilizando as seguintes tecnologias:

### Backend
- **Java** — linguagem principal da aplicação.
- **Spring Boot** — desenvolvimento da API REST.
- **Spring Data JPA / Hibernate** — persistência e mapeamento dos dados.
- **Flyway** — gerenciamento das migrações do banco de dados.

### Banco de dados
- **PostgreSQL** — armazenamento dos dados da aplicação.

### Frontend
- **Angular** — construção da interface web.
- **TypeScript** — desenvolvimento da aplicação frontend.

### Testes e ambiente
- **JUnit e Mockito** — testes automatizados.
- **Docker e Docker Compose** — preparação e execução do ambiente de desenvolvimento.
- **Git e GitHub** — versionamento, colaboração e revisão de código.

## 🏗️ Arquitetura

O Loot&Stock será organizado em duas partes principais:

- **Backend:** responsável pelas regras de negócio, validações, persistência dos dados e disponibilização da API.
- **Frontend:** responsável pela interface utilizada para gerenciar produtos, movimentações, pedidos e relatórios.

A aplicação será estruturada para manter as responsabilidades bem definidas, facilitando a manutenção, os testes e a evolução do sistema.

## 📋 Regras de negócio

Algumas regras importantes previstas para o sistema:

- A quantidade de produtos em estoque não pode ser negativa.
- As movimentações devem atualizar o saldo do estoque corretamente.
- Um pedido não pode ser confirmado se não houver estoque suficiente.
- A confirmação de um pedido e a atualização do estoque devem ocorrer de forma consistente.
- O histórico de movimentações deve ser preservado para consulta.
- Os valores dos itens de um pedido devem registrar o preço praticado no momento da criação do pedido.

## 👥 Desenvolvimento colaborativo

O projeto está sendo desenvolvido em dupla, com foco tanto na construção de uma aplicação funcional quanto no aprendizado de práticas utilizadas no desenvolvimento profissional.

O fluxo de trabalho inclui:

- Versionamento com Git.
- Organização de tarefas e funcionalidades.
- Desenvolvimento em branches.
- Pull requests para revisão de código.
- Testes para verificar o comportamento da aplicação.
- Documentação das decisões técnicas relevantes.

## ▶️ Como executar

As instruções de instalação e execução serão adicionadas conforme a estrutura do projeto for implementada.

A documentação incluirá os requisitos necessários, a configuração do banco de dados, as variáveis de ambiente e os comandos para executar o backend e o frontend.

## 🎯 Objetivos do projeto

- Desenvolver uma aplicação full stack utilizando tecnologias relevantes para o mercado.
- Aplicar conceitos de orientação a objetos e arquitetura de software.
- Trabalhar com APIs REST e bancos de dados relacionais.
- Praticar testes automatizados e integridade dos dados.
- Aprender e aplicar um fluxo de trabalho colaborativo com Git e GitHub.
- Construir um projeto documentado para compor o portfólio dos desenvolvedores.

---

**Loot&Stock** — Organize seu estoque, mantenha o controle e encontre seu próximo loot. 📦
