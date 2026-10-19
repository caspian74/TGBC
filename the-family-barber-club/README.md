# The Family Barber Club – Landing page

Sitio estático para Cloudflare Workers (Static Assets).

## Deploy
1. `npm install`
2. `npx wrangler login`
3. `npm run deploy`

Queda en `https://the-family-barber-club.<tu-subdominio>.workers.dev`.
Para dominio propio: Workers & Pages → el Worker → Settings → Domains & Routes.

## Antes de entregar al cliente (editar `public/index.html`)
- Número de WhatsApp: buscar `526640000000` (formato 52 + 10 dígitos).
- Precios, horario y dirección reales.
- Para cambiar el nombre del Worker: `name` en `wrangler.jsonc`.
