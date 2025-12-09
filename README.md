# 👹 DOOM BOY - Red Edition

Um projeto de interface web desenvolvido puramente com **HTML e CSS** (sem dependência de JavaScript complexo), simulando a experiência de jogar um caça-níquel temático de DOOM em um Game Boy clássico modificado.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen)
![CSS](https://img.shields.io/badge/CSS-Advanced-blue)
![Theme](https://img.shields.io/badge/Theme-Doom%20x%20Retro-red)

## 🎮 Funcionalidades

* **Design Responsivo:** Centralizado e escalável.
* **Estética Retrô:** Recriação fiel do chassi do Game Boy usando apenas CSS (`border-radius`, `box-shadow`).
* **Efeito LCD:** Scanlines e paleta de cores monocromática esverdeada (`#8bac0f`).
* **Filtros de Imagem:** Uso de `mix-blend-mode` e `grayscale` para fazer imagens JPG e Emojis modernos parecerem gráficos de 1989.
* **CSS Logic:** O botão de "Desligar" funciona sem JavaScript, utilizando a técnica do **Checkbox Hack**.

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**
* **CSS3 / SCSS**
    * Flexbox & Grid Layout
    * CSS Transitions & Animations
    * Advanced Selectors (`:checked`, `~`)
* **Fontes:** [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P) (Google Fonts).

## 📂 Estrutura do Projeto

```text
doom-boy/
├── assets/
│   ├── favicon.png
│   └── doomFaceIcon.jpg
├── index.html       # Tela Inicial (Menu)
├── game.html        # Tela do Jogo (Slots)
├── style.css        # (ou styleTwo.css) Estilização principal
└── README.md
