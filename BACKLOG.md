# 🛹 Backlog — Skate Sketch Odyssey

Sugestões para evoluir o jogo. Nada aqui está implementado ainda — é um cardápio pra você
escolher. Cada item tem **ID** (pra você pedir "implementa o J2"), **prioridade** e **esforço**.

- Prioridade: **P1** (alto impacto / pedido), **P2** (bom ter), **P3** (extra/futuro)
- Esforço: **P** (pequeno), **M** (médio), **G** (grande)

---

## J — Jogabilidade & "feel" (sensação de controle)

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **J1** | **Saída de corrimão mais gostosa** (problema atual). Hoje sair do grind dá uma sensação travada. Pacote de melhorias: *coyote time* (ainda dá pra pular ~6 frames depois de sair), *jump buffer* (se apertar pulo um pouco antes de sair, ele guarda), pequeno **boost de "ollie out"** ao saltar do trilho, e manter a velocidade/direção. | P1 | M |
| **J2** | **Janela de manobra na saída do grind** — ao sair do trilho, já poder iniciar um trick imediatamente (sem o pequeno "engasgo" atual), e o combo continuar fluido. | P1 | P |
| **J3** | **Medidor de equilíbrio** em grinds e manuals longos (uma barrinha que oscila; corrigir com ←/→). Recompensa quem segura mais tempo e dá tensão. | P2 | M |
| **J4** | **Revert / "landing into manual"** — ao cair de um trick, segurar ↓ entra em manual e mantém o combo (clássico Tony Hawk). Já temos manual; faltaria o link automático no pouso. | P1 | P |
| **J5** | **Coyote time + jump buffer no ollie comum** (não só no grind) — perdão de timing deixa tudo menos punitivo. | P2 | P |
| **J6** | **Indicador de "perfect landing"** — pousar alinhado dá bônus; pousar torto reduz pontos (sem bail). Camada de skill sem punir demais. | P2 | M |
| **J7** | **Buffer de inputs de trick** — registrar a combinação (→+A etc.) alguns frames antes do ollie, pra não exigir timing perfeito no ar. | P2 | P |
| **J8** | **Curva de dificuldade configurável** — velocidade inicial/aceleração por fase num só lugar, fácil de tunar. | P3 | P |

## C — Combate (Fase 3, modo luta)

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **C1** | **Combos de golpe** (ex.: soco-soco-chute encadeado com dano crescente) e *hitstun* melhor. | P2 | M |
| **C2** | **Golpe especial na luta** — uma barra de fúria que enche apanhando/acertando; libera um "skate spin attack". | P2 | M |
| **C3** | **Esquiva / rolagem** (↑ ou duplo-toque pra dar um *dash* e fugir do golpe). | P2 | P |
| **C4** | **Telegrafar ataques do Bad Boy** (um "!" ou pose de wind-up antes do golpe) pra dar pra defender com leitura. | P1 | P |
| **C5** | **Melhor distinção visual dos lutadores** (cores/silhuetas) e animações de impacto mais expressivas (estrelinhas, "POW!" desenhado). | P2 | M |
| **C6** | **Vida/dano calibráveis + dificuldade** (o oponente fica mais esperto a cada vitória). | P3 | P |

## E — Eras & Fases novas (a "nova era" pós Street League)

> Ideia central: depois de virar profissional (Street League), começa a **Era da Lenda** —
> você é veterano, anda de **skate velho** (física diferente) e sobe de **rank**:
> **Master → Grand Master → Legend**.

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **E1** | **Era da Lenda — estrutura de ranks** (Master, Grand Master, Legend) como fases 5/6/7, cada uma com missões mais difíceis e metas de pontuação altas. | P1 | G |
| **E2** | **Skate velho (física própria)** — board mais pesado/solto: ollie mais baixo, trucks "soltos" (vira mais fácil mas escorrega), trilhos exigem mais equilíbrio. Vira um modo com identidade própria. | P1 | M |
| **E3** | **Estética "envelhecida"** pra Era da Lenda — papel amarelado/sépia, traço mais trêmulo, manchas de café no caderno. Reforça o tema "veterano". | P2 | M |
| **E4** | **Skin de veterano** — barba/grisalho, roupa diferente, board surrado (evolução de visual como já fizemos na Fase 2). | P2 | P |
| **E5** | **Picos temáticos por rank** — Master: pista de bowl/half-pipe; Grand Master: mega ramp; Legend: "line" lendária com tudo junto. | P2 | G |
| **E6** | **Boss/rival recorrente** — reencontrar o Bad Boy (agora aliado ou rival pro) em uma fase de duelo de pontos (game of S.K.A.T.E.) em vez de porrada. | P3 | G |
| **E7** | **Modo livre / "skate park"** sem missão, só pra treinar linhas e bater recorde. | P3 | M |
| **E8** | **Game of S.K.A.T.E.** — minigame de revezamento de manobras contra a CPU (quem erra ganha letra). | P3 | G |

## O — Obstáculos & Level design

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **O1** | **Half-pipe / bowl / quarter de transição** que devolve pro outro lado (não só lança pra frente). | P2 | M |
| **O2** | **Wallride / wallie** em muros. | P3 | M |
| **O3** | **Spine transfer** (rampa-rampa costas com costas). | P3 | M |
| **O4** | **Trilhos curvos / em S** e trilhos quebrados (gap entre dois trechos de grind). | P2 | M |
| **O5** | **Mais variedade de obstáculos urbanos** — hidrante, banco, carro, cone, mesa picnic; uns desviáveis, uns "grindáveis". | P2 | M |
| **O6** | **Geração de "lines" curadas** (sequências desenhadas à mão em vez de 100% aleatório) pra ter momentos memoráveis. | P3 | G |

## P — Progressão, pontuação & meta

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **P1** | **Loja / desbloqueáveis** — gastar pontos pra liberar skates, skins, cores de traço. | P2 | M |
| **P2** | **Multiplicador visível e "banco de combo"** mais claro (mostrar a corrente crescendo e o risco de perder). | P2 | P |
| **P3** | **Mais especiais** e uma "árvore" deles por era (900→grind já existe; ex.: "manual infinito", "darkslide", "the 1260"). | P3 | M |
| **P4** | **Conquistas / selos desenhados** (carimbos no caderno) por feitos (ex.: combo de 12, 5 grinds seguidos). | P3 | M |
| **P5** | **Placar local com nomes** (top 5 no localStorage, tela de high scores no estilo caderno). | P2 | P |
| **P6** | **Desafios diários** (seed do dia) — mesma pista pra todo mundo daquele dia. | P3 | M |

## U — UX / Interface

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **U1** | **Tela de controles / "como jogar"** acessível no menu e no pause (hoje a dica fica fixa embaixo). | P1 | P |
| **U2** | **HUD de luta e de skate separados e mais limpos**; esconder a dica de skate durante a luta. | P2 | P |
| **U3** | **Suporte a toque (mobile)** — botões na tela pra jogar no celular. | P2 | M |
| **U4** | **Remapear teclas** e/ou suporte a gamepad. | P3 | M |
| **U5** | **Tela de transição entre eras** mais elaborada (não só virar página) — um "card" de rank conquistado. | P3 | P |
| **U6** | **Acessibilidade** — modo daltônico, opção de reduzir screen shake, alto contraste. | P3 | P |

## A — Áudio

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **A1** | **Música de fundo** procedural/loop por era (algo lo-fi pro caderno). | P2 | M |
| **A2** | **Mais variação de SFX** — som distinto por tipo de trick, grind contínuo com "pitch" pela velocidade, torcida na vitória. | P2 | P |
| **A3** | **Controle de volume** (slider) além do mute. | P3 | P |

## R — Polimento visual / "juice"

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **R1** | **Variedade de bails** — escorregão, sentar no chão, capacete voando; e a "borracha" já existente com variações. | P2 | M |
| **R2** | **Câmera com leve zoom/parallax** nos momentos de especial e KO. | P3 | M |
| **R3** | **Mais camadas de cenário** (parallax de prédios, postes, pichações desenhadas). | P3 | M |
| **R4** | **Efeito de "speed lines"** quando muito rápido / sob estrela. | P3 | P |

## T — Técnico / saúde do código

| ID | Item | Pri | Esf |
|----|------|-----|-----|
| **T1** | **Separar em arquivos** (HTML/CSS/JS) ou módulos quando crescer — hoje é um `index.html` único (ótimo pra distribuir, mas começa a ficar grande). | P2 | M |
| **T2** | **Pausar/limitar quando a aba perde o foco** (evita "pulo" de tempo ao voltar). | P2 | P |
| **T3** | **`requestAnimationFrame` com delta-time** pra física consistente em telas 120Hz+. | P2 | M |
| **T4** | **Tela responsiva** (canvas escala pro tamanho da janela mantendo proporção). | P2 | P |
| **T5** | **Limpar os macetes de teste** (ou esconder atrás de `?dev` na URL) antes de divulgar pra valer. | P2 | P |

---

## 🎯 Sugestão de "primeira leva" (se quiser um ponto de partida)
Itens de **alto impacto e baixo/médio custo** que melhoram o jogo já:
- **J1 + J2** — resolve a dor que você citou (saída de corrimão).
- **J4** — revert no pouso deixa os combos muito mais fluidos.
- **C4** — telegrafar o golpe do Bad Boy deixa a luta mais justa.
- **U1** — tela de "como jogar".
- **P5** — placar local com nomes (engajamento, custo baixo).

E pra a **nova era**, o núcleo seria **E1 + E2** (ranks Master/Grand Master/Legend + física do skate velho),
com **E3/E4** entrando pra dar identidade visual.
