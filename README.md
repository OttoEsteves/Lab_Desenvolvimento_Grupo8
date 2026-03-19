# Lab_Desenvolvimento_Grupo8 — Portfólio Web (HTML, CSS e JavaScript)

Este projeto consiste em um **portfólio web pessoal** desenvolvido com **HTML, CSS e JavaScript**, com foco em apresentar informações profissionais, habilidades técnicas, experiências em programação, projetos desenvolvidos e formas de contato em uma interface moderna, organizada e responsiva.

A proposta do site é funcionar como uma vitrine digital, permitindo que visitantes, recrutadores, professores ou colegas conheçam melhor o perfil do desenvolvedor por meio de uma navegação simples, objetiva e visualmente agradável.

O projeto foi estruturado em seções bem definidas, com navegação por âncoras, elementos visuais animados e integração com formulário de contato, tornando a experiência do usuário mais dinâmica e intuitiva.

---

## Visão geral do projeto

O portfólio foi construído para reunir, em uma única página, os principais elementos de apresentação profissional do desenvolvedor. A navegação acontece por meio de um menu lateral, que direciona o usuário para diferentes áreas do site sem necessidade de abrir novas páginas.

As seções presentes no projeto foram organizadas para oferecer uma leitura fluida e progressiva, começando pela apresentação inicial e passando por informações pessoais, experiências técnicas, habilidades, projetos e contato.

Esse modelo de portfólio é especialmente útil para:

- apresentar perfil profissional de forma online;
- divulgar projetos e repositórios;
- demonstrar conhecimentos em desenvolvimento front-end;
- disponibilizar currículo para visualização ou download;
- facilitar o contato com recrutadores, clientes ou parceiros.

---

## Seções disponíveis no site

O site é composto pelas seguintes seções principais:

### Home
A seção inicial funciona como a porta de entrada do portfólio. Nela, o visitante tem o primeiro contato com a identidade visual do projeto e com a apresentação principal do desenvolvedor. Normalmente, essa área destaca o nome, a função ou área de atuação e elementos visuais que ajudam a causar uma boa primeira impressão.

### About Me
A seção **About Me** é dedicada à apresentação pessoal e profissional. Nela, podem ser exibidas informações sobre trajetória, objetivos, interesses na área de tecnologia, perfil acadêmico ou profissional, além de um link para o currículo em PDF.

Essa seção é importante porque contextualiza o visitante, mostrando não apenas competências técnicas, mas também quem é a pessoa por trás do portfólio.

### Programming Experience
A seção de **Programming Experience** apresenta experiências relacionadas ao desenvolvimento de software, estudos práticos, projetos acadêmicos, participação em atividades da área ou contato com determinadas linguagens e tecnologias.

Ela ajuda a demonstrar evolução técnica e familiaridade com o universo da programação, mesmo quando o desenvolvedor ainda está em formação.

### Skills
A área de **Skills** reúne as habilidades técnicas dominadas ou estudadas pelo desenvolvedor. Essa seção pode incluir linguagens, frameworks, bibliotecas, ferramentas e conhecimentos complementares relevantes para o perfil profissional.

Além de organizar melhor as competências, essa parte do portfólio facilita a leitura por recrutadores e outros profissionais da área.

### Projects
A seção de **Projects** destaca trabalhos desenvolvidos ao longo da trajetória do autor. Cada projeto pode conter descrição, objetivo, tecnologias utilizadas, link para repositório e, quando houver, link para demonstração online.

Essa é uma das partes mais importantes de qualquer portfólio, pois apresenta evidências práticas das habilidades técnicas mencionadas em outras seções.

### Contact
A seção de **Contact** disponibiliza uma forma direta de comunicação com o desenvolvedor. Neste projeto, ela conta com um formulário integrado ao **StaticForms**, permitindo o envio de mensagens de forma simples, sem necessidade de back-end próprio.

Esse recurso facilita o contato profissional e torna o portfólio mais funcional.

---

## Funcionalidades implementadas

O projeto conta com diferentes recursos que melhoram tanto a usabilidade quanto a apresentação visual da aplicação. Abaixo estão os principais destaques:

### 1. Menu lateral com navegação por âncoras
O site possui um **menu lateral fixo** que permite a navegação rápida entre as seções da página. Ao clicar em uma opção do menu, o usuário é direcionado diretamente para a área correspondente do portfólio.

As opções de navegação incluem:

- Home  
- About Me  
- Skills  
- Projects  
- Contact  

Esse tipo de navegação melhora a experiência do usuário, principalmente em páginas do tipo **one page**, onde todo o conteúdo está concentrado em uma única estrutura HTML.

### 2. Efeitos e animações visuais
Foram adicionados **efeitos de exibição e animações** em pontos estratégicos da interface, como no título inicial e na seção **About Me**. Esses recursos ajudam a tornar a navegação mais agradável e moderna, além de valorizar a apresentação do conteúdo.

As animações também contribuem para destacar informações importantes e deixar o site com aparência mais dinâmica.

### 3. Link para currículo em PDF
Na seção **About Me**, o projeto disponibiliza um link para acesso ao arquivo `curriculo.pdf`. Isso permite que visitantes visualizem ou façam download do currículo de forma rápida, sem precisar sair do portfólio em busca de outras plataformas.

Essa funcionalidade é bastante útil em contextos profissionais e acadêmicos, pois centraliza as principais informações do desenvolvedor em um só lugar.

### 4. Exibição de projetos com links externos
A seção de projetos apresenta os trabalhos desenvolvidos com possibilidade de acesso a:

- repositório do projeto;
- demonstração online (demo), quando disponível.

Isso permite que o visitante não apenas leia sobre os projetos, mas também explore o código-fonte e visualize o funcionamento prático das aplicações criadas.

### 5. Formulário de contato integrado ao StaticForms
O formulário de contato foi integrado ao serviço **StaticForms**, que permite o envio de mensagens em sites estáticos sem necessidade de configuração de servidor próprio.

Além do envio, o formulário também oferece:

- confirmação de envio;
- feedback visual no botão;
- melhor interação com o usuário durante o processo.

Esse recurso deixa a aplicação mais completa e pronta para uso em um cenário real.

---

## Tecnologias utilizadas

O desenvolvimento do projeto foi realizado com tecnologias fundamentais do front-end. Abaixo está o detalhamento de cada uma:

### HTML5
O **HTML5** foi utilizado para estruturar semanticamente o conteúdo do portfólio, organizando as seções, textos, links, botões, formulários e demais elementos da página.

Seu uso garante uma base sólida para o projeto, além de contribuir para acessibilidade, organização e manutenção do código.

### CSS3
O **CSS3** foi responsável pela estilização completa da interface, incluindo cores, espaçamentos, fontes, organização dos elementos, responsividade e animações visuais.

Por meio dele, o projeto ganha identidade visual própria e uma apresentação mais profissional.

### JavaScript (Vanilla)
O **JavaScript puro** foi utilizado para implementar comportamentos dinâmicos no site, como interações visuais, feedbacks no formulário e outras funcionalidades que tornam a experiência do usuário mais rica.

A escolha pelo JavaScript Vanilla demonstra domínio dos conceitos centrais da linguagem sem depender diretamente de frameworks.

### Bootstrap 5 (CDN)
O **Bootstrap 5**, carregado via CDN, foi utilizado como apoio para estruturação visual e responsividade. Ele contribui com classes utilitárias, grid system e componentes prontos que ajudam a acelerar o desenvolvimento da interface.

### Bootstrap Icons (CDN)
Os **Bootstrap Icons** foram usados para inserir ícones na interface, enriquecendo visualmente o layout e tornando algumas ações mais intuitivas para o usuário.

---

## Estrutura do projeto

Abaixo está a organização dos principais arquivos utilizados no projeto:

```bash
Lab_Desenvolvimento_Grupo8/
│
├── index.html
├── style.css
├── js.js
├── curriculo.pdf
└── imagens/ ou arquivos de imagem utilizados no layout
