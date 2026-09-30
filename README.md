# Jogos — Chá de Bebê do Leonardo

Site com os jogos criados para o chá de bebê do Leonardo. Todos os jogos rodam direto no navegador, sem instalação, e são acessíveis pelo hub central em [`index.html`](index.html).

**Site publicado:** https://Pugialli.github.io/ChaLeo/

---

## Jogos

### 🎱 Bingo
`sorteador_bingo_cha_leonardo_1.html`

Sorteador de pedras de bingo com cartelas temáticas do chá de bebê. O apresentador sorteia as pedras na tela e os participantes marcam nas cartelas físicas. Quem completar uma linha primeiro vence.

---

### 🕵️ Codenames
`codenames_cha_leonardo_3.html`

Adaptação do jogo de palavras Codenames. Dois times se enfrentam: o líder de cada time dá dicas de uma palavra só para que os colegas identifiquem as palavras certas no tabuleiro, evitando as do time adversário e a palavra proibida.

---

### 🔐 Mega Senha
`megasenha_cha_leonardo_3.html`

Versão digital do clássico Mastermind. Um jogador define uma senha secreta com cores e o adversário tenta descobri-la em tentativas limitadas, recebendo dicas de posição e acerto a cada rodada.

---

### ✏️ Adivinhe a Frase
`frases_desenhos_cha_leonardo_5.html`

Um participante assiste a um vídeo com a frase de um filme, música ou série sendo desenhada e tenta adivinhar qual é. Os vídeos ficam na pasta `videos/` e são carregados pelo jogo automaticamente.

---

## Estrutura

```
ChaLeo/
├── index.html                          # Hub central com todos os jogos
├── sorteador_bingo_cha_leonardo_1.html
├── codenames_cha_leonardo_3.html
├── megasenha_cha_leonardo_3.html
├── frases_desenhos_cha_leonardo_5.html
└── videos/                             # Vídeos usados pelo Adivinhe a Frase
    ├── 1.mp4 … 12.mp4
```

## Tecnologia

Sites estáticos em HTML, CSS e JavaScript puro — sem dependências externas nem servidor. Fontes e imagens embutidas em base64 para funcionamento offline.
