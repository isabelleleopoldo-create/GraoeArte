# ☕ Grão & Arte - Torrefação e Café Especial

Projeto de desenvolvimento front-end simulando um ambiente profissional para a marca fictícia **Grão & Arte**. A aplicação consiste numa página institucional e catálogo de cafés especiais, focada em semântica HTML5, arquitetura CSS com metodologia BEM, acessibilidade, responsividade e alto padrão visual.

---

## 📌 Visão Geral e Objetivo do Projeto

O objetivo principal deste projeto é aplicar os conceitos fundamentais de desenvolvimento web front-end sem o uso de frameworks, criando uma interface fluida, moderna e totalmente adaptável a qualquer dispositivo (smartphones, tablets e desktops).

A **Grão & Arte** conecta pequenos produtores de cafés especiais diretamente ao consumidor final, oferecendo microlotes com pontuação acima de 85 pontos SCA, além de um clube de assinatura exclusivo.

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **HTML5 Semântico:** Estruturação limpa e acessível utilizando elementos como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<details>`, `<summary>` e `<footer>`.
* **CSS3 Modular & Design System:**
  * **CSS Custom Properties (Variáveis Globais):** Gerenciamento centralizado da paleta de cores, tipografias, sombras e transições no `:root`.
  * **Metodologia BEM (Block Element Modifier):** Nomenclatura padronizada de classes e seletores para garantir legibilidade e reutilização do código.
  * **Escala REM e Tipografia:** Configuração da escala base no elemento raiz (`html { font-size: 62.5%; }`) e utilização estrita de unidades relativas (`rem`) para fontes, espaçamentos e bordas.
  * **Flexbox & Unidades Relativas:** Uso do Flexbox para ordenação de cards/seções, porcentagem (`%`) para containers e unidades de viewport (`vh`/`vw`) para seções em tela cheia.
* **Responsividade:** Layout adaptável desenvolvido com Media Queries e breakpoints para smartphones, tablets e desktops.
* **Microinterações:** Feedback visual interativo com `:hover`, transições suaves e elevação de cards.
* **Recursos Externos:**
  * **Google Fonts:** Importação das famílias *Merriweather* (400, 700) e *Open Sans* (400, 600, 700).
  * **Placehold.co / Unsplash:** Imagens e visuais otimizados para a temática do café.
  * **API do WhatsApp:** Botão flutuante para contato direto via URL oficial com o número do SENAI Henrique Lupo.

---

## 📂 Organização da Arquitetura de Arquivos

A estrutura do projeto garante a separação estrita de responsabilidades (sem estilos inline ou blocos `<style>` embutidos):

```text
grao-e-arte/
├── assets/
│   ├── css/
│   │   ├── variables.css      # Tokens do Design System (Cores, fontes, sombras)
│   │   ├── global.css         # Reset CSS, escala REM e elemento raiz
│   │   ├── components.css     # Estilos de componentes (botões, cards, FAQ, rodapé)
│   │   └── style.css          # Ficheiro principal de importação
│   └── images/                # Recortes e imagens do projeto
├── index.html                 # Estrutura HTML5 semântica da aplicação
└── README.md                  # Documentação oficial do projeto