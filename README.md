# Lab_Desenvolvimento_Grupo8 — Portfólio Web (HTML/CSS/JS)



> Portfólio pessoal responsivo, com menu lateral, seções de apresentação (About me, Skills, Projects) e formulário de contato. Projeto 100% front-end (estático), sem build.



---



## 🚧 Status do Projeto



- ✅ Em desenvolvimento / iterando conteúdo

- ✅ Versão inicial navegável (site estático)

- 🔜 Ajustes de responsividade e conteúdo dos projetos



---



## 📚 Índice

- [Links Úteis](#-links-úteis)

- [Sobre o Projeto](#-sobre-o-projeto)

- [Funcionalidades Principais](#-funcionalidades-principais)

- [Tecnologias Utilizadas](#-tecnologias-utilizadas)

- [Arquitetura](#-arquitetura)

- [Instalação e Execução](#-instalação-e-execução)

  - [Pré-requisitos](#pré-requisitos)

  - [Como Rodar Localmente](#como-rodar-localmente)

- [Deploy](#-deploy)

- [Estrutura de Pastas](#-estrutura-de-pastas)

- [Demonstração](#-demonstração)

- [Testes](#-testes)

- [Documentações utilizadas](#-documentações-utilizadas)

- [Autores](#-autores)

- [Contribuição](#-contribuição)

- [Licença](#-licença)



---



## 🔗 Links Úteis

- 🌐 **Demo Online:** _adicione aqui_ (ex.: GitHub Pages / Vercel / Netlify)

- 📁 **Repositório:** este repositório

- 🧾 **Currículo (PDF):** `curriculo.pdf` (se disponível na raiz do projeto)



---



## 📝 Sobre o Projeto

Este projeto é um **portfólio web** para apresentar informações pessoais e profissionais, habilidades técnicas e projetos.  

Ele foi feito como um site estático, com foco em **layout responsivo**, navegação simples e um **formulário de contato**.



Seções principais:

- Home (mensagem de boas-vindas)

- About me (apresentação)

- Programming Experience (experiência resumida)

- Skills (skills com ícones)

- Projects (cards/área de projetos com links)

- Contact (formulário + contatos)



---



## ✨ Funcionalidades Principais

- 🧭 **Menu lateral de navegação** com âncoras para seções da página

- 📱 **Comportamento responsivo** (layout ajusta em telas menores)

- 🎬 **Efeitos de entrada** (ex.: animação/fade-in no título e na seção About)

- 📨 **Formulário de contato** com confirmação de envio e feedback visual no botão

- 🔗 **Links externos** para redes e projetos (GitHub, LinkedIn, WhatsApp, etc.)



---



## 🛠 Tecnologias Utilizadas



### 💻 Front-end

- **HTML5**

- **CSS3**

- **JavaScript (Vanilla)**



### 🎨 UI / Estilo

- **Bootstrap 5 (CDN)** (para botões e base de componentes)

- **Bootstrap Icons (CDN)**

- **Google Fonts (CDN)**



### 📨 Formulário

- Envio via serviço externo (ex.: StaticForms) usando `action` no `<form>`.



---



## 🏗 Arquitetura

Arquitetura simples de site estático:



- **`index.html`**: estrutura da página, seções e links

- **`style.css`**: estilos globais, layout, responsividade e efeitos visuais

- **`js.js`**: interações (menu mobile, animações e comportamento do formulário)



Fluxo:

1. Usuário navega via menu (âncoras `#HOME`, `#ABOUTME`, `#SKILLS`, `#PROJECTS`, `#CONTACTS`)

2. JS controla:

   - abrir/fechar menu no mobile

   - animações ao carregar/rolar

   - confirmação e feedback do botão de envio

3. Formulário envia para endpoint externo definido no `action`.



---



## 🔧 Instalação e Execução



### Pré-requisitos

- Um navegador moderno (Chrome/Firefox/Edge)

- Internet (para carregar Bootstrap/Icons/Fonts via CDN e para envio do formulário)



### Como rodar localmente

Opção A — abrir direto:

1. Abra o arquivo `index.html` no navegador



Opção B — servidor local (recomendado):

```bash

# Python 3

python -m http.server 8000
