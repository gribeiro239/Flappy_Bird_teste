# Flappy Bird (Pygame)

Clone simples do Flappy Bird feito em **Python + Pygame**.  
Renderização por sprites, canos gerados aleatoriamente e chão com rolagem contínua.

![screenshot](docs/screenshot.png) <!-- opcional -->

---

## 🚀 Recursos
- Loop de jogo em **30 FPS** (`clock.tick(30)`).
- Pássaro animado (3 sprites) com **gravidade** e impulso no **ESPAÇO**.
- **Canos** com abertura fixa (`PIPE_GAP`) e posicionamento aleatório.
- **Chão** rolando em loop.
- **Colisão** com canos e chão (game over).

> **Observação:** placar ainda **não** implementado (há um marcador `# SCORE` no código).

---

## 🎮 Controles
- **Pular**: `Barra de Espaço`
- **Sair**: fechar a janela (evento `QUIT`)
