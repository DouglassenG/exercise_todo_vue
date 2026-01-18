# ✅ Exercise Todo - Vue.js Application

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![Vue.js](https://img.shields.io/badge/Framework-Vue.js-4FC08D?logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/Code-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/Style-CSS3-blue?logo=css3&logoColor=white)

> Uma aplicação SPA focada na produtividade, demonstrando os conceitos fundamentais de reatividade e componentização do framework Vue.js.

## 🎯 Motivação e Propósito

Este repositório foi desenvolvido como parte de um exercício prático para dominar a reatividade no Frontend. O objetivo principal não é apenas criar uma lista, mas entender como o **Vue.js** abstrai a complexidade da manipulação do DOM.

O projeto resolve o problema de gerenciar listas dinâmicas de forma eficiente. Ele demonstra como adicionar, renderizar e remover itens de um array de estado, refletindo essas mudanças instantaneamente na interface do usuário (UI) sem recarregamentos de página.

## 🖼️ Demonstração Visual

*(Se o projeto estiver hospedado na Vercel, Netlify ou GitHub Pages, insira o link aqui. Ex: [Acesse a Demo](URL))*

## 🛠️ Tecnologias Utilizadas

A stack tecnológica é baseada no padrão de SPAs modernas:

* **[Vue.js](https://vuejs.org/):** Framework progressivo utilizado para a construção da interface.
    * **Reatividade:** Atualização automática da UI quando o estado muda.
    * **Diretivas:** `v-model` (binding de formulário), `v-for` (loops), `v-on` (eventos).
* **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Lógica de manipulação de dados.
* **[CSS3 Scoped](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilização isolada por componente para evitar efeitos colaterais.
* **[Node.js & NPM](https://nodejs.org/):** Gerenciamento de dependências e scripts de build.

## ✨ Funcionalidades

O projeto implementa as operações essenciais de uma lista de tarefas:

1.  **Captura de Dados:** Input de texto controlado via *Two-Way Data Binding* (`v-model`).
2.  **Renderização de Lista:** Exibição dinâmica de itens utilizando a diretiva `v-for`.
3.  **Exclusão de Itens:** Remoção de tarefas específicas através de manipulação de índices de array.
4.  **Feedback Visual:** (Se implementado) Limpeza automática do campo de input após a adição.

## 📂 Estrutura de Arquivos

O projeto segue a estrutura padrão gerada pelo Vue CLI/Vite, organizando a lógica em componentes:

```text
exercise_todo_vue/
├── node_modules/        # Dependências do projeto
├── public/              # Arquivos estáticos (index.html, favicon)
├── src/                 # Código Fonte
│   ├── assets/          # Imagens e estilos globais
│   ├── components/      # Componentes Vue reutilizáveis
│   ├── App.vue          # Componente Raiz (Lógica principal)
│   └── main.js          # Ponto de entrada e montagem da instância Vue
├── package.json         # Scripts e lista de dependências
└── README.md            # Documentação
