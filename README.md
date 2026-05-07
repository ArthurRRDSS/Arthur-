

Autores:

Arthur Rodrigues de Lima Costa
Lucas Dyonn Porto Felix 
Thayrone Silva Andrade


# Documento de Requisitos de Software (DRS)

## 1. Introdução

### 1.1 Visão Geral

O sistema de gestão tem como finalidade auxiliar empresas, instituições ou pequenos negócios no controle e organização de informações, processos e atividades internas. A plataforma permitirá centralizar dados importantes, automatizar tarefas e facilitar o acesso às informações de maneira simples, rápida e segura.

O sistema será desenvolvido com foco em usabilidade, acessibilidade e praticidade, podendo ser utilizado em diferentes dispositivos, como computadores, tablets e smartphones.

### 1.2 Objetivos do Sistema

* Facilitar a organização e gerenciamento de informações.
* Automatizar processos manuais.
* Melhorar a produtividade dos usuários.
* Garantir maior segurança e controle dos dados.
* Disponibilizar acesso rápido e intuitivo às funcionalidades do sistema.
* Reduzir erros operacionais e retrabalho.

### 1.3 Público Alvo

O sistema é destinado para:

* Pequenas e médias empresas;
* Instituições educacionais;
* Comércios;
* Prestadores de serviços;
* Administradores e funcionários que necessitam gerenciar informações e processos internos.

---

## 2. Escopo do Sistema

### 2.1 Escopo Incluído

O sistema deverá permitir:

* Cadastro de usuários;
* Login e autenticação;
* Gerenciamento de informações;
* Consulta e atualização de dados;
* Controle de acesso por perfil;
* Emissão de relatórios;
* Interface responsiva e acessível;
* Armazenamento seguro de dados.

### 2.2 Escopo Não Incluído

O sistema não contemplará:

* Integração com sistemas bancários;
* Funcionalidades offline;
* Inteligência artificial avançada;
* Integração com hardware externo;
* Aplicativos nativos para dispositivos móveis.

---

## 3. Requisitos Funcionais

### RF00 - Cadastro de Usuários

O sistema deverá permitir o cadastro de novos usuários com informações básicas como nome, e-mail e senha.

### RF01 - Login no Sistema

O sistema deverá permitir que usuários autenticados acessem a plataforma através de e-mail e senha.

### RF02 - Gerenciamento de Dados

O sistema deverá permitir cadastrar, editar, excluir e visualizar informações armazenadas.

### RF03 - Controle de Acesso

O sistema deverá possuir diferentes níveis de acesso conforme o perfil do usuário.

### RF04 - Geração de Relatórios

O sistema deverá gerar relatórios para consulta e acompanhamento das informações cadastradas.

### RF05 - Recuperação de Senha

O sistema deverá permitir a recuperação de senha através do e-mail cadastrado.

---

## 4. Requisitos Não Funcionais

### RNF00 - Desempenho

O sistema deverá responder às solicitações do usuário em no máximo 3 segundos.

### RNF01 - Segurança

As informações dos usuários deverão ser protegidas por criptografia e autenticação segura.

### RNF02 - Usabilidade

O sistema deverá possuir interface simples, intuitiva e de fácil utilização.

### RNF03 - Compatibilidade

O sistema deverá funcionar nos principais navegadores modernos.

### RNF04 - Disponibilidade

O sistema deverá possuir disponibilidade mínima de 95%.

### RNF05 - Responsividade

O sistema deverá adaptar sua interface para diferentes tamanhos de tela.

---

## 5. Arquitetura Técnica

### 5.1 Stacks

#### 5.1.1 Stack Backend

* Node.js
* Express.js
* API REST
* JWT para autenticação

#### 5.1.2 Stack Frontend

* HTML5
* CSS3
* JavaScript
* React.js

#### 5.1.3 Banco de Dados

* MySQL
  
* PostgreSQL

---

