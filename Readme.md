
# FS90
> Full Stack em 90 dias

Este plano foca no aprendizado de desenvolvimento de sites full stack, incluindo frontend e backend, e está dividido em sessões de aproximadamente 2 a 4 horas diárias.

Utilizaremos as seguintes ferramentas:
- [vscode](https://code.visualstudio.com/Download)
    - extensões
        - [html preview](https://marketplace.visualstudio.com/items?itemName=george-alisson.html-preview-vscode)
        - [WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
- [chrome](https://www.google.com.br/chrome/) **e** [firefox](https://www.mozilla.org/pt-PT/firefox/new/)
    - extensões
        - [React DevTools](https://react.dev/learn/react-developer-tools)
- [studio3T](https://studio3t.com/download/) **ou** [mongo Compass](https://www.mongodb.com/try/download/compass)
- [WSL2](https://learn.microsoft.com/pt-br/windows/wsl/install)
    - se estiver usando windows 

Também precisaremos de:
- [NodeJs](https://nodejs.org/en/download/package-manager)
- [Yarn](https://classic.yarnpkg.com/lang/en/docs/install/)
- [Docker](https://www.docker.com/)
    - [mongodb](https://hub.docker.com/_/mongo/)


---

### **Dias 1 a 15: Fundamentos do Frontend**

- **HTML e CSS**  
  - HTML5: tags semânticas, formulários, tabelas
  - CSS3: position, flexbox, grid
  - Responsividade e animações: media queries, mobile-first
- **Prática**
  - Criar página simples para calcular o número de horas não trabalhadas (mesma premissa da [cocoladora](https://cocoladora.com/))
  - Desafios de layout no [CSSBattle](https://cssbattle.dev) e [Frontend Mentor](https://www.frontendmentor.io/)

---

### **Dias 16 a 30: JavaScript para o Frontend**

- **JavaScript Básico**
  - Variáveis, operadores, loops, funções
  - Manipulação do DOM
  - Eventos e manipulação de elementos da página

- **Prática**
  - Criar interações como slideshows, menus dropdown e carrosséis
  - Trabalhar com formulários: validações simples e envio (sem backend ainda)
  - Projetos práticos: Calculadora e To-Do List

---

### **Dias 31 a 45: Fundamentos de Backend com Node.js**

- **Node.js e Express**
  - Instalação do Node.js, módulos e NPM
  - Configuração de um servidor básico com Express
  - Criação de rotas e middleware

- **Banco de Dados NoSQL com MongoDB**
  - Conectar e criar uma base de dados no MongoDB
  - Manipulação de dados: CRUD básico (Create, Read, Update, Delete)

- **Prática**
  - Criar uma API básica de um CRUD para cadastro de usuários ou tarefas
  - Conectar o frontend com o backend utilizando `fetch` ou `axios`

---

### **Dias 46 a 60: Frontend Avançado com React**

- **React Básico**
  - Componentes, props e state
  - Hook useState e useEffect
  - Ciclo de vida e gerenciamento de estado local

- **Prática**
  - Criar uma aplicação de blog com React, exibindo posts de uma API externa
  - Construir uma lista de tarefas interativa usando o CRUD desenvolvido anteriormente

---

### **Dias 61 a 75: Backend Avançado**

- **Autenticação e Segurança**
  - Implementação de autenticação JWT (JSON Web Tokens)
  - Proteção de rotas e validação de usuários

- **Gerenciamento de Estado e Armazenamento com MongoDB**
  - Relacionamentos básicos em MongoDB (documentos aninhados e referências)
  - Autenticação e criação de sessões seguras

- **Prática**
  - Adicionar autenticação ao sistema de tarefas
  - Criar um sistema de permissões para diferentes tipos de usuários

---

### **Dias 76 a 90: Integração Full Stack e Projetos Finais**

- **Integração Completa**
  - Conectar o frontend e backend, tratando o ciclo completo de autenticação e CRUD
  - Aprender deploy em serviços como Vercel, Netlify (para frontend) e Heroku (para backend)

- **Projeto Final**
  - **E-commerce Simples**: páginas de produtos, carrinho, checkout, e autenticação de usuário
  - **Painel de Controle**: sistema CRUD completo com autenticação para o administrador e permissões para usuários

---
