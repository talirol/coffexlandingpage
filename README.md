# Coffex Landing

Landing page simples e responsiva para o app **Coffex**, construída em HTML e CSS puro.

## Estrutura

- `index.html` — página principal (hero com mockup do app, botões de App Store / Google Play, destaque de métricas).
- `about.html` — página "Sobre" com explicação do produto.
- `contact.html` — página de contato com formulário estático para futuras integrações.
- `download.html` — página dedicada de download do app.
- `styles.css` — estilos globais compartilhados entre todas as páginas.

## Cores

- Primária: `#fd9801`
- Complementar: `#5f3911`
- Fundo: `#faf7f2`

## Rodando localmente

Como o projeto é estático, basta abrir o arquivo `index.html` no navegador ou servir a pasta com qualquer servidor HTTP simples, por exemplo:

```bash
cd coffexlanding
python -m http.server 8000
```

Depois acesse `http://localhost:8000` no navegador.

