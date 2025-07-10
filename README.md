# Projeto "Vozes das Cores" - Site Informativo Outubro Rosa

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-blueviolet)

[cite_start]Este projeto é um site informativo e interativo sobre a campanha **Outubro Rosa**, desenvolvido como parte da iniciativa acadêmica "Vozes das Cores". [cite: 1, 17] [cite_start]O objetivo principal é utilizar a tecnologia para disseminar informações de qualidade sobre a importância da prevenção e do diagnóstico precoce do câncer de mama. [cite: 2]

---

## ✒️ Índice

- [Descrição do Projeto](#-descrição-do-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [📂 Estrutura de Pastas](#-estrutura-de-pastas)
- [🖥️ Como Visualizar o Projeto](#️-como-visualizar-o-projeto)
- [👨‍💻 Autores](#-autores)

---

## 📖 Descrição do Projeto

[cite_start]O projeto "Vozes das Cores" propõe a criação de um site sobre uma das campanhas mensais de conscientização. [cite: 2] [cite_start]Nossa equipe escolheu o **Outubro Rosa** [cite: 17] devido à sua imensa relevância para a saúde pública.

[cite_start]O escopo inicial do projeto, conforme as diretrizes, previa a utilização de um script **Python** para gerar uma página HTML estática a partir de um template. [cite: 3, 38] Buscando aprimorar a experiência do usuário e aplicar conhecimentos de desenvolvimento web moderno, expandimos a proposta inicial. O resultado é uma *Single Page Application (SPA)* dinâmica e interativa, construída com HTML5, CSS3 e JavaScript, e enriquecida com ferramentas como Tailwind CSS e a API generativa do Google (Gemini).

[cite_start]O site aborda seções fundamentais sobre a campanha, como sua definição [cite: 20][cite_start], importância [cite: 21][cite_start], dados estatísticos [cite: 22] [cite_start]e formas de prevenção. [cite: 23]

---

## ✨ Funcionalidades

O site conta com as seguintes seções e funcionalidades interativas:

-   **Conteúdo Informativo:** Seções detalhadas sobre o que é o Outubro Rosa, a importância da causa, dicas de prevenção e como ajudar.
-   **Estatísticas com Gráficos:** Visualização de dados relevantes sobre a incidência do câncer de mama no Brasil, utilizando gráficos interativos gerados com a biblioteca Chart.js.
-   **Mitos e Verdades (com IA):** Uma seção que consome a API do Google Gemini para gerar e desmistificar mitos e verdades comuns sobre o câncer de mama, combatendo a desinformação.
-   **Gerador de Mensagem de Apoio (com IA):** Uma ferramenta que cria mensagens de apoio e encorajamento para pacientes e familiares, também utilizando a API do Google Gemini.
-   **Chatbot Assistente (com IA):** Um assistente virtual inteligente com o qual o usuário pode conversar para tirar dúvidas sobre a campanha, sintomas e prevenção.
-   **Design Responsivo:** A interface se adapta perfeitamente a diferentes tamanhos de tela, como desktops, tablets e celulares.

---

## 🚀 Tecnologias Utilizadas

As seguintes tecnologias foram utilizadas no desenvolvimento do projeto:

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | [cite_start]Linguagem de marcação para a estruturação semântica das páginas. [cite: 7] |
| **CSS3** | [cite_start]Utilizado para a estilização base e animações. [cite: 8] |
| **Tailwind CSS** | Framework CSS utility-first para a criação rápida e consistente do design. |
| **JavaScript** | Linguagem de programação que adiciona toda a interatividade ao site, como a lógica dos gráficos e as chamadas de API. |
| **Chart.js** | Biblioteca para a criação dos gráficos e visualização de dados estatísticos. |
| **Google Gemini API** | Inteligência Artificial generativa utilizada no Chatbot, na seção de Mitos e Verdades e no Gerador de Mensagens. |
| **GitHub** | [cite_start]Plataforma utilizada para o controle de versão do código. [cite: 9] |
| **GitHub Pages**| [cite_start]Serviço de hospedagem para a publicação e disponibilização online do site. [cite: 4, 9] |
| **Python** | [cite_start]Utilizado na fase conceitual do projeto, conforme solicitado, para o estudo de geração de páginas. [cite: 6] |

---

## 📂 Estrutura de Pastas

O projeto está organizado da seguinte forma para garantir a manutenibilidade:

/outubro-rosa-site/
|
├── index.html            # Arquivo principal da página
├── css/
│   └── estilos.css       # Folha de estilos customizada
├── js/
│   └── scripts.js        # Arquivo com toda a lógica JavaScript
├── imagens/
│   └── outubro.jpg       # Imagem de fundo da seção principal
└── README.md             # Documentação do projeto (este arquivo)


---

## 🖥️ Como Visualizar o Projeto

### Opção 1: Acessar o Site Publicado (Recomendado)

O site está publicado e pode ser acessado através do seguinte link:

➡️ **[https://andre-luan.github.io/Outubro-Rosa/](https://andre-luan.github.io/Outubro-Rosa/)** ⬅️ (Substitua pelo link do seu GitHub Pages)

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

---

## 👨‍💻 Autores

Este projeto foi desenvolvido com dedicação por:

-   **André Luan** - [GitHub](https://github.com/andorelol)
-   **Pedro Augusto** - [GitHub](https://github.com/pedroasampa)
-   **Raphael Guthyer** - (Adicione o link do GitHub aqui se houver)
