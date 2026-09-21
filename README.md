GymFit

Sistema web de academia desenvolvido em Python com Flask, HTML, CSS e JavaScript.

Funcionalidades

Página inicial da academia

Visualização dos planos

Agendamento de aulas

Área do aluno

Chatbot de atendimento

Painel de testes

Automações com Selenium

Tecnologias utilizadas

Python

Flask

HTML

CSS

JavaScript

Selenium

WebDriver Manager

Gunicorn

Estrutura

O projeto possui uma aplicação Flask responsável pelas páginas e pelas rotas do sistema. O Selenium é utilizado para executar as automações disponíveis no painel de testes.

Instalação

Clone o repositório e instale as dependências:

pip install -r requirements.txt

Execução local

Para executar a aplicação localmente:

python app.py

A aplicação será disponibilizada em:

http://127.0.0.1:5000

Deploy no Render

Build Command

pip install -r requirements.txt

Start Command

gunicorn --bind 0.0.0.0:$PORT app:app

Observação

O projeto utiliza Selenium para automações que abrem e interagem com o site. Essas automações dependem de um navegador compatível e de seu respectivo driver no ambiente de execução.

Projeto

GymFit — projeto desenvolvido para fins de estudo, demonstração e prática de desenvolvimento web com Python e Flask.