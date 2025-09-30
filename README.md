<h1 align="center"> Clever — Sistema de Gestão de Máquinas e Ordens de Serviço</h1>
<p align="center">Projeto acadêmico desenvolvido para a disciplina de Projeto Empreendedor II (UNIFTEC).</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-14.17.6-green?logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-4.18-blue?logo=express" alt="Express">
  <img src="https://img.shields.io/badge/MongoDB-6.3-green?logo=mongodb" alt="MongoDB">
  <img src="https://img.shields.io/badge/EJS-3.1-orange" alt="EJS">
</p>

---

## Objetivo

Este projeto foi desenvolvido como **Trabalho de Conclusão de Curso (TCC)** para a disciplina de Projeto Empreendedor II — UNIFTEC.  
O sistema tem como foco a **gestão de máquinas e ordens de serviço**, oferecendo funcionalidades que simulam um ambiente de manutenção preventiva e corretiva.

---

## Funcionalidades

- Cadastro e edição de **usuários** e **máquinas**.  
- Criação e gerenciamento de **ordens de serviço**.  
- Relatórios de ordens abertas, fechadas e preventivas.  
- Emissão e envio de **e-mails automáticos** (via Nodemailer).  
- Painéis com **gráficos de acompanhamento**.  
- Autenticação de usuários e login seguro.  

---

## Tecnologias Utilizadas

- [Node.js](https://nodejs.org/) — Backend da aplicação.  
- [Express](https://expressjs.com/) — Framework para rotas e middlewares.  
- [MongoDB](https://www.mongodb.com/) — Banco de dados NoSQL para persistência.  
- [Mongoose](https://mongoosejs.com/) — Modelagem de dados para MongoDB.  
- [EJS](https://ejs.co/) — Template engine para renderização de views.  
- [Nodemailer](https://nodemailer.com/about/) — Envio de e-mails automatizados.  
- [Moment.js](https://momentjs.com/) — Manipulação de datas.  

---

## Instalação e Execução

Para rodar este projeto localmente, siga os passos:

```bash
# Clone o repositório
git clone https://github.com/jaquetrevizan/clever.git

# Acesse o diretório do projeto
cd clever

# Instale as dependências
npm install

# Execute a aplicação
npm start
````

O servidor será iniciado em `http://localhost:3000`.

---

## Aprendizados

Durante o desenvolvimento deste sistema, tivemos contato com:

* Estruturação de um projeto **full-stack** com Node.js e MongoDB.
* Utilização de **template engines (EJS)** para renderização dinâmica.
* Implementação de **CRUD completo** (usuários, máquinas, ordens de serviço).
* Integração de **serviço de e-mails** para automação de notificações.
* Experiência de **deploy em nuvem** via Heroku.

