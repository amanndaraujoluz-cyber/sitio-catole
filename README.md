# Rapadura Sítio Catolé

Site da Rapadura Sítio Catolé — rapadura pura de cana feita em Lavras da Mangabeira (CE). Atacado, comércio e pré-venda da próxima safra, com pedidos pelo WhatsApp.

## Estrutura

- `index.html` — página única (HTML, CSS e JS no mesmo arquivo)
- `img/` — fotos do sítio, canavial e produção

## Publicação

Site estático, sem build. Publicado no Netlify a partir da branch `main`:

- Build command: *(vazio)*
- Publish directory: `.`

Todo push na `main` gera um novo deploy automaticamente.

## Editar

- Número do WhatsApp: constante `WHATSAPP` no `<script>` do `index.html`.
- Fotos: substitua os arquivos em `img/` mantendo os mesmos nomes.
