# Studio Huntter Creators — Grupo VIP

Página de captura do Grupo VIP do Studio Huntter Creators, também instalável como app no celular (PWA).

## Arquivos

- `index.html` — a página completa (a foto já vai embutida)
- `manifest.webmanifest` — nome, cores e ícones do app
- `sw.js` — faz o app abrir rápido e funcionar sem internet
- `icons/` — ícones do app

## Onde mudar as coisas

No final do `index.html`, no bloco `// Configure aqui`:

- `GRUPO` — link do grupo do WhatsApp
- `VAGAS` — porcentagem da barra de vagas preenchidas

## Publicar

Funciona em qualquer hospedagem estática: Vercel, Netlify, GitHub Pages ou o `public_html` do seu domínio.
É só enviar todos os arquivos, mantendo as pastas.

O app só pode ser instalado quando o site está em **https**.

## Instalar no celular

- **Android (Chrome):** abra o site e toque em "Instalar app" (ou ⋮ → "Adicionar à tela inicial").
- **iPhone (Safari):** toque em Compartilhar → "Adicionar à Tela de Início".
