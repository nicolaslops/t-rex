# T-REX

## Sobre o Projeto

Este projeto consiste em uma versão interativa e personalizada do clássico jogo do dinossauro (T-Rex Game). A aplicação foi desenvolvida utilizando HTML, CSS e a biblioteca **p5.js** para criar uma experiência de jogo fluida diretamente no navegador, contando com animações, efeitos sonoros e mecânicas de colisão em tempo real.

A interface renderiza o cenário onde o jogador deve desviar de obstáculos dinâmicos, utilizando as funções nativas do ecossistema p5.js para gerenciar a física do pulo, a geração de elementos na tela, a contagem de pontos e o estado de fim de jogo (Game Over).

---

## Funcionalidades

* Controle do personagem (T-Rex) com mecânica de pulo para desviar de obstáculos.
* Geração dinâmica e aleatória de múltiplos tipos de obstáculos e elementos de cenário (nuvens e solo).
* Sistema de colisão preciso entre o personagem e os obstáculos utilizando `p5.play`.
* Efeitos sonoros integrados para ações específicas (pular, marcar pontuação/checkpoint e colidir) com `p5.sound`.
* Tela de Game Over com opção de reinicialização (Restart) imediata do jogo.
* Renderização otimizada de sprites e animações fluidas para simular o movimento de corrida infinita.

---

## Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **p5.js** (e extensões: p5.dom, p5.play, p5.sound)

---

## Objetivo

O principal objetivo deste projeto é aplicar conceitos avançados de lógica de programação e desenvolvimento de jogos web utilizando a biblioteca p5.js, trabalhando com o ciclo de vida clássico de um jogo (`preload`, `setup` e `draw`), manipulação de vetores, gerenciamento de sprites e controle de elementos multimídia.

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Utilização do ciclo de renderização contínuo (`draw`) da biblioteca p5.js.
* Criação, manipulação e colisão de sprites utilizando a extensão `p5.play`.
* Pré-carregamento assíncrono de assets (imagens e sons) com a função `preload` para evitar travamentos.
* Gerenciamento e manipulação de múltiplos estados do jogo (Start, Playing, Game Over).
* Controle de áudio digital reproduzido de forma dinâmica através da biblioteca `p5.sound`.

---

## Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/seu-usuario/T-REX.git](https://github.com/seu-usuario/T-REX.git)
```

2. Acesse a pasta do projeto:

```bash
cd T-REX
```

3. Abra o arquivo index.html em seu navegador de preferência para começar a jogar.

--- 

## Estrutura do Projeto
```text
T-REX/
│
├── assets/
│   ├── img/
│   │   ├── cloud.png
│   │   ├── gameOver.png
│   │   ├── ground1.png
│   │   ├── ground2.png
│   │   ├── obstacle1.png
│   │   ├── obstacle2.png
│   │   ├── obstacle3.png
│   │   ├── obstacle4.png
│   │   ├── obstacle5.png
│   │   ├── obstacle6.png
│   │   ├── restart.png
│   │   ├── trex_collided.png
│   │   ├── trex1.png
│   │   ├── trex3.png
│   │   └── trex4.png
│   └── mp3/
│       ├── checkPoint.mp3
│       ├── die.mp3
│       └── jump.mp3
│
├── scripts/
│   ├── p5.dom.min.js
│   ├── p5.js
│   ├── p5.play.js
│   ├── p5.sound.min.js
│   └── sketch.js
│
├── style/
│   └── style.css
│
├── index.html
└── README.md
```

--- 

## Licença

Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado.

Desenvolvido como prática de desenvolvimento web e lógica de jogos, recriando o clássico T-Rex Game com HTML, CSS e a biblioteca p5.js.
