# LM IT Solutions — site

Site institucional da **LM IT Solutions** (CNPJ 46.246.833/0001-38), São Paulo/SP.

## Estrutura

- `index.html` — página institucional da LM IT Solutions (HTML + CSS inline, sem build).
- `multi-ia/index.html` — landing page do produto **Multi-IA** ("gerente de IAs" em PT-BR,
  mobile-first, preço em reais), com a lista de espera. Publicada em `/multi-ia`.
- `assets/` — imagens do site institucional.

## Publicar

Site estático. Deploy automático via **Cloudflare Pages** a cada push na branch `main`
(build vazio, diretório de saída `/`).
