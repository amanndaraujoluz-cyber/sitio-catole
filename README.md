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

## Imagens que o atendente do WhatsApp envia (`ofertas/`)

O bot envia os links de `imagens_oferta` do `config-rapadura.json` (Dropbox). Regra completa no
`jarvis-hub/regras/midia-centralizada.md`.

| Arquivo | Chave no config | Foto real de origem (Dropbox `Projetos/Rapadura/fotos/reais/`) |
|---|---|---|
| `oferta-1-quadrada.jpg` | `conversa` | `imagem focada rapadura.jpeg` |
| `oferta-2-foto.jpg` | `foto` | `rapadura estocada no engenho.jpeg` |
| `oferta-3-lote.jpg` | `lote` | `embaladas por carga e armazenada elevada.jpeg` |
| `oferta-4-status.jpg` | `status` | `rapadura estocada no engenho.jpeg` |

- Só foto real do produto. Sem preço, mínimo, cidade ou prazo escrito na imagem.
- Para trocar: substitua o arquivo mantendo o nome e faça push na `main`.
