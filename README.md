# Rodrigo Cid — Landing Page

Site estático (HTML + CSS + JS puro), trilíngue PT / EN / ES. Pronto para GitHub + Vercel (sem build).

## Antes de publicar
No `index.html`, bloco `CONFIG` (início do `<script>`):
- `whatsapp` — DDI + DDD + número, só dígitos (ex.: 5511999999999)
- `linkedin` — URL do perfil
- `calendly` — URL do Calendly
- `email` — opcional, entra no vCard
- `site` — domínio final

Troque também `https://rodrigocid.com` nas tags `canonical`, `og:url`, `og:image` e no JSON-LD do `<head>`.

## Idiomas
`?lang=en` / `?lang=es` na URL força o idioma. Sem parâmetro: idioma do navegador (padrão PT).

Desenvolvido por KNGflow.
