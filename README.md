# Automação Instagram e Facebook — Resumo Sem Enrolação

Publica sozinho, mesmo com o PC desligado, no Instagram @resumosemenrolacao e na Página do Facebook.

- **Reels:** 2 por dia, às 11:00 e às 19:00 (Brasília). Fila em `fila/fila-reels.json`.
- **Stories:** 1 por dia, às 09:00. Fila em `fila/fila-stories.json`.
- Quem enche as filas é o robô do PC (`Robôs/Instagram e Facebook/robo_igfb.py` no projeto).
- Os vídeos ficam como arquivos temporários na release `fila-instagram-facebook` e saem de lá depois de publicados.

Motor copiado do Código da Virada em 27/09/2026 (mesmos testes, lock e confirmação por rede).
Segredos no GitHub: `IG_ACCESS_TOKEN`, `IG_BUSINESS_ID`, `FB_PAGE_ACCESS_TOKEN`, `FB_PAGE_ID`.
