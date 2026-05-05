# 🎧 Interface Audiobook - React

![GitHub repo size](https://img.shields.io/github/repo-size/pedromarinz/interface-audiobook?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/pedromarinz/interface-audiobook?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

Este projeto é uma aplicação reativa desenvolvida em **React** que simula a interface de um player de audiobook. O objetivo principal foi o gerenciamento de estados complexos e a criação de uma interface moderna, responsiva e intuitiva.

---

## 🚀 O Projeto

Diferente de um player de áudio convencional, este projeto focou em resolver o desafio de manter a sincronia entre a faixa de áudio, a barra de progresso e a listagem dinâmica de capítulos.

* **Componentização Atómica:** Divisão da interface em peças menores e reutilizáveis (Botões de Controlo, Timeline, Card do Livro).
* **Gestão de Estado Reativa:** Implementação de Hooks (`useState`, `useEffect`) para manipular o ciclo de vida do áudio e as transições entre capítulos sem recarregamento de página.
* **Lógica de Navegação:** Uso de métodos de array para manipulação dinâmica da lista de reprodução, garantindo fluidez na troca de faixas.

## 🛠️ Tecnologias e Ferramentas

* **React.js:** Biblioteca principal para a construção da UI.
* **JavaScript (ES6+):** Lógica de manipulação da API de Áudio e gestão de estados.
* **HTML5 & CSS3:** Foco em design responsivo e acessibilidade.
* **Git & GitHub:** Versionamento de código com foco em boas práticas de documentação.

## ✨ Funcionalidades

- [x] **Controlo Reativo:** Play e Pause sincronizados com o estado global.
- [x] **Navegação Inteligente:** Botões de "Próximo" e "Anterior" que respeitam a ordem dos capítulos.
- [x] **Interface Adaptável:** Feedback visual imediato ao trocar de faixa (Capa e Título).
- [ ] **Persistência (Próximo Passo):** Implementação de `localStorage` para salvar
