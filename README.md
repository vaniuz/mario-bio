# Mario Drums — Link-in-Bio

Página de links (link-in-bio) do baterista **Mario Drums** (@mariodrums03) — tema escuro estilo Instagram, com cards para o canal do YouTube e o site oficial.

## Links
- **YouTube** → https://youtu.be/v8NnovQgnTQ
- **Site oficial** → https://mariodrums.vercel.app/mario-drums.html

## Deploy
Site 100% estático (HTML + CSS, sem build). Qualquer host serve — na Vercel use o preset **Other**.

Arquivos:
- `index.html` — a página (é o que a Vercel serve na raiz `/`)
- `bio.html` — atalho que redireciona para `/` (links antigos continuam funcionando)
- `assets/bio-mario.webp` — foto hero (1440×1800)
- `assets/bio-logo.png` — logo MD (badge branco)
- `assets/bio-thumb.jpg` — thumbnail do card do YouTube

> Importante: a página **precisa** se chamar `index.html`. Um `bio.html` sozinho na raiz faz a Vercel responder `404 NOT FOUND` em `/`.
