Sistema Web de Quiz e Dashboard – Sociedade Esportiva Palmeiras
Descrição

Este projeto consiste em um sistema web interativo inspirado na Sociedade Esportiva Palmeiras, desenvolvido para permitir o cadastro e login de usuários, participação em um quiz sobre o clube e visualização de dados em uma dashboard.

A aplicação foi criada com o objetivo de demonstrar a integração entre frontend e backend, utilizando tecnologias web modernas e banco de dados relacional.

O sistema permite armazenar informações dos usuários, registrar respostas do quiz e apresentar os resultados por meio de visualizações de dados.

Funcionalidades

Cadastro de usuários

Login e autenticação de usuários

Quiz interativo sobre a história do Palmeiras

Registro das respostas dos usuários no banco de dados

Dashboard com visualização dos resultados do quiz

Armazenamento e consulta de dados no banco MySQL

Interface web para interação com o sistema

Tecnologias Utilizadas
Backend

Node.js

JavaScript

Express.js

MySQL

SQL

API para comunicação entre frontend e banco de dados

Frontend

HTML5

CSS3

JavaScript

Infraestrutura

Máquinas Virtuais para execução do projeto

Ambiente de desenvolvimento local e remoto

Estrutura do Projeto

O sistema é dividido em duas partes principais:

Backend

Responsável pela lógica da aplicação, autenticação de usuários e comunicação com o banco de dados.

Principais recursos manipulados pelo sistema:

Usuário

Aviso

Medida (dados utilizados na dashboard)

O backend recebe requisições do frontend e realiza operações no banco de dados utilizando comandos SQL.

Frontend

Interface web desenvolvida com HTML, CSS e JavaScript, responsável pela interação do usuário com o sistema.

O frontend permite:

cadastro e login de usuários

participação no quiz

visualização de dados na dashboard

envio e recebimento de informações do backend

A comunicação com o servidor ocorre através de requisições HTTP.

Como Executar o Projeto
1. Configuração do Banco de Dados

Clone o repositório do projeto.

Execute o script disponível em:

/src/database/script-tabelas.sql

Esse script criará as tabelas necessárias para o funcionamento do sistema.

2. Configuração do Ambiente

No arquivo app.js, configure o ambiente de execução:

Produção (remoto)

var ambiente_processo = 'producao';

Desenvolvimento (local)

var ambiente_processo = 'desenvolvimento';

Configure também as credenciais do banco de dados no arquivo:

.env
ou
.env.dev
3. Instalação das Dependências

No terminal, execute:

npm i

Esse comando instalará todas as bibliotecas necessárias listadas no arquivo package.json.

4. Executar o Projeto

Execute:

npm start

O servidor será iniciado e o projeto poderá ser acessado através do endereço exibido no terminal.

Para interromper a execução, utilize:

CTRL + C
Objetivo do Projeto

Este projeto foi desenvolvido com finalidade acadêmica para praticar conceitos de:

desenvolvimento web full stack

integração entre frontend e backend

manipulação de dados com banco relacional

criação de APIs e rotas no Node.js

utilização de JavaScript para comunicação com o servidor

visualização de dados em aplicações web

Possíveis Melhorias Futuras

Melhorias na interface gráfica da aplicação

Implementação de mais perguntas no quiz

Novas métricas e gráficos na dashboard

Sistema de ranking entre usuários

Implementação de autenticação mais robusta

Melhor tratamento de erros e validações

Autor

Este projeto foi desenvolvido por Bryan Machado da Costa e Silva, aluno de Sistemas de Informação da São Paulo Tech School (SPTech), como parte das atividades acadêmicas do curso.

O sistema tem como tema principal a Sociedade Esportiva Palmeiras, um dos clubes mais importantes do Brasil. A escolha do tema reflete uma conexão pessoal do autor com o clube, que surgiu por influência de seu pai.

O projeto combina aprendizado técnico com interesse pessoal, utilizando tecnologias como Node.js, JavaScript, MySQL, HTML e CSS para criar uma aplicação web interativa que une programação, dados e a paixão pelo futebol.
