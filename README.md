# Invenção do Governo ou Proteção Real? — EGR, DPF e ARLA 32

Site educativo (UFABC · CECS · Projeto Dirigido). Arquivo único: `index.html`, sem dependências externas.

## Como editar
Abra `index.html` e altere só o bloco `CONFIG` (dentro do `<script>`):
- **Vídeos:** cole o ID do YouTube em `youtubeId` (ex.: `watch?v=AbC123` → `"AbC123"`).
  Legendas: envie o `.srt` em português no YouTube Studio; o player já pede legendas ligadas.
- **Fontes:** preencha `texto` e `link` em `fontes`. Itens marcados `verificar: true` são sugestões que precisam de conferência.
- **Textos, quiz, mitos, FAQ, equipe:** todos no mesmo bloco.
- **Endereço público:** preencha `site.urlPublica` após publicar (links de compartilhamento).
- **Cores:** variáveis no começo do CSS (`:root`).

## Como publicar (grátis)
- **GitHub Pages:** suba `index.html` num repositório → Settings → Pages → branch `main` / root.
- **Netlify:** arraste a pasta em app.netlify.com/drop.
- **Vercel:** `vercel` na pasta (ou importe o repositório).

## Antes de publicar
Procure por `[inserir` no arquivo: são todos os pontos onde falta fonte ou dado. Nenhum número ou estudo foi inventado.
