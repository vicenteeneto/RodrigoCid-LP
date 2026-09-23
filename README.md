# Rodrigo Cid — Landing Page

Site estático (HTML + CSS + JS puro), trilíngue PT / EN / ES. Pronto para GitHub + Vercel (sem build).

## Antes de publicar
No `index.html`, bloco `CONFIG` (início do `<script>`):
- `whatsapp` — já preenchido: +1 (512) 590-9661
- `phoneDisplay` — telefone exibido no bloco de contato
- `linkedin` — já preenchido: /in/rodrigocid10
- `calendly` — **pendente**. Enquanto estiver vazio, os botões de agendamento ficam ocultos e o WhatsApp vira o botão principal
- `instagram` + `igLabel` — Instagram do Twins Group (vazio = oculto)
- `phoneDisplay` — telefone formatado exibido no contato (ex.: +55 11 99999-9999)
- `instagram` — opcional (vazio = oculto)
- `email` — opcional (vazio = oculto; entra no vCard)
- `site` — domínio final

Troque também `https://rodrigocid.com` nas tags `canonical`, `og:url`, `og:image` e no JSON-LD do `<head>`.

## Idiomas
`?lang=en` / `?lang=es` na URL força o idioma. Sem parâmetro: idioma do navegador (padrão PT).

Desenvolvido por KNGflow.
