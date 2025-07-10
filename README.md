# Projeto "Vozes das Cores" - Site Informativo Outubro Rosa

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blueviolet)

Este projeto é um site informativo e interativo sobre a campanha **Outubro Rosa**, desenvolvido como parte da iniciativa acadêmica "Vozes das Cores". O objetivo principal é utilizar a tecnologia para disseminar informações de qualidade sobre a importância da prevenção e do diagnóstico precoce do câncer de mama.

---

## 👨‍💻 Autores

Este projeto foi desenvolvido com dedicação por:

-   **André Luan** - [GitHub](https://github.com/andorelol)
-   **Pedro Augusto** - [GitHub](https://github.com/pedroasampa)
-   **Raphael Guthyer** - (Adicione o link do GitHub aqui se houver)

---

## ✒️ Índice

- [Descrição do Projeto](#-descrição-do-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [📂 Estrutura de Pastas](#-estrutura-de-pastas)
- [🖥️ Como Visualizar o Projeto](#️-como-visualizar-o-projeto)


## 📖 Descrição do Projeto

O projeto "Vozes das Cores" propõe a criação de um site sobre uma das campanhas mensais de conscientização. Nossa equipe escolheu o **Outubro Rosa** devido à sua imensa relevância para a saúde pública.

O escopo inicial do projeto, conforme as diretrizes, previa a utilização de um script **Python** para gerar uma página HTML estática a partir de um template. Buscando aprimorar a experiência do usuário e aplicar conhecimentos de desenvolvimento web moderno, expandimos a proposta inicial. O resultado é uma *Single Page Application (SPA)* dinâmica e interativa, construído com HTML5, CSS3 e JavaScript, e enriquecido com ferramentas como Tailwind CSS e a API generativa do Google (Gemini).

O site aborda seções fundamentais sobre a campanha, como sua definição, importância, dados estatísticos e formas de prevenção.

## ✨ Funcionalidades

O site conta com as seguintes seções e funcionalidades interativas:

-   **Conteúdo Informativo:** Seções detalhadas sobre o que é o Outubro Rosa, a importância da causa, dicas de prevenção e como ajudar.
-   **Estatísticas com Gráficos:** Visualização de dados relevantes sobre a incidência do câncer de mama no Brasil, utilizando gráficos interativos gerados com a biblioteca Chart.js.
-   **Mitos e Verdades (com IA):** Uma seção que consome a API do Google Gemini para gerar e desmistificar mitos e verdades comuns sobre o câncer de mama, combatendo a desinformação.
-   **Gerador de Mensagem de Apoio (com IA):** Uma ferramenta que cria mensagens de apoio e encorajamento para pacientes e familiares, também utilizando a API do Google Gemini.
-   **Chatbot Assistente (com IA):** Um assistente virtual inteligente com o qual o usuário pode conversar para tirar dúvidas sobre a campanha, sintomas e prevenção.
-   **Design Responsivo:** A interface se adapta perfeitamente a diferentes tamanhos de tela, como desktops, tablets e celulares.

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Linguagem de marcação para a estruturação semântica das páginas. |
| **CSS3** | Utilizado para a estilização base e animações. |
| **Tailwind CSS** | Framework CSS utility-first para a criação rápida e consistente do design. |
| **JavaScript** | Linguagem de programação que adiciona toda a interatividade ao site, como a lógica dos gráficos e as chamadas de API. |
| **Chart.js** | Biblioteca para a criação dos gráficos e visualização de dados estatísticos. |
| **Google Gemini API** | Inteligência Artificial generativa utilizada no Chatbot, na seção de Mitos e Verdades e no Gerador de Mensagens. |
| **GitHub** | Plataforma utilizada para o controle de versão do código. |
| **GitHub Pages**| Serviço de hospedagem para a publicação e disponibilização online do site. |
| **Python** | Utilizado na fase conceitual do projeto, conforme solicitado, para o estudo de geração de páginas. |

## 📂 Estrutura de Pastas

O projeto está organizado da seguinte forma para garantir a manutenibilidade:

/outubro-rosa-site/

├── css/
│   └── estilos.css

├── js/
│   └── scripts.js

├── imagens/
│   └── outubro.jpg

├── index.html
└── README.md


## 🖥️ Como Visualizar o Projeto

### Opção 1: Acessar o Site Publicado (Recomendado)

O site está publicado e pode ser acessado através do seguinte link:

➡️ **[https://andre-luan.github.io/Outubro-Rosa/](https://andre-luan.github.io/Outubro-Rosa/)** (Substitua pelo link correto, se for diferente)

### Opção 2: Executar Localmente

Caso queira executar o projeto em sua máquina local:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd nome-do-repositorio
    ```
3.  **Abra o arquivo `index.html`** diretamente no seu navegador de preferência.

> **Nota:** Para que as funcionalidades de Inteligência Artificial (Chatbot, Mitos e Verdades) funcionem localmente, é necessário inserir uma chave de API válida do Google Gemini no arquivo `js/scripts.js`.
