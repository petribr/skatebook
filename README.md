# Skate Sketch Odyssey ✏️🛹

[![Jogar online](https://img.shields.io/badge/▶%20Jogar%20online-petribr.github.io%2Fskatebook-7a5cc0?style=for-the-badge)](https://petribr.github.io/skatebook/)
&nbsp;
![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-e34f26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?logo=javascript&logoColor=black)
![Sem dependências](https://img.shields.io/badge/depend%C3%AAncias-zero-2a7d2a)

Um jogo de skate 2D com estética **"lápis sobre papel pautado"**, feito em um único arquivo HTML com Canvas + JavaScript puro — sem dependências, sem build. É só abrir o `index.html` no navegador.

## 🎮 Jogar online

**https://petribr.github.io/skatebook/**

## Como jogar

Abra [`index.html`](index.html) no navegador (ou jogue online no link acima) e aperte **Espaço** para começar.

### Controles

| Tecla | Ação |
|---|---|
| `Espaço` | Ollie (segure para pular mais alto) |
| `↓` | Manual |
| `→` + `A` | Kickflip |
| `→` + `B` | FS 180 |
| `↑` + `B` | 360 Spin |
| `↑` + `A` | 540 |
| `←` + `A` | Pop Shuv |
| `↓` + `B` | Bigspin |
| `S` | Especial (barra cheia) |
| `↑` (no grind) | Crooked grind |
| `P` | Pause |
| `M` | Liga/desliga som |
| `R` | Reiniciar |

## Mecânicas

- **Combos encadeados** — tricks, grinds e manuals se ligam numa corrente que multiplica os pontos; só "deposita" quando você assenta limpo. Cair (bail) perde a corrente.
- **Manobras em sequência no ar** — completar um trick no ar credita e libera o próximo.
- **Corrimões variados** — longos, inclinados (sobe/desce), com gaps para pular de um pro outro.
- **Obstáculos** — patinete (desvie pulando), rampa/quarter-pipe (arremessa alto), escadaria (pule o vão).
- **Estrela ✨** — reduz a gravidade por 5s, permitindo sequências enormes de manobras.
- **Barra de especial** (2 níveis) — 2000 pts solta o **900** (super ollie); 4000 pts solta o **1080 + Kickflip**.
- **4 fases**:
  1. **A Base** — tutorial de ollies, giros e combos.
  2. **A Cidade** — missões mais duras; em certo ponto a skin evolui (óculos, touca, calça, tattoos).
  3. **Modo Luta** ⚔️ — você vira Mestre e cai na porrada contra um playboy *bad boy*; lutam com chutes e socos usando os skates (← → mover · `A` chute · `B` soco · `↓` defender).
  4. **Street League** 🏆 — vira profissional e disputa a liga; complete as missões e vire **campeão**.

## VFX (estilo caderno)

Traço imperfeito desenhado à mão, swirls/espirais nos giros, rastro de grafite que brilha na manobra perfeita, poeira nas aterrissagens, e o efeito **borracha + redesenho** quando você cai.

## Áudio

Tudo procedural via Web Audio API (sem arquivos): "lápis riscando" contínuo, whooshes nos giros, e jingles de combo/missão/especial.

## Tecnologia

HTML5 Canvas + JavaScript vanilla, em um único arquivo. Recorde salvo via `localStorage`.
