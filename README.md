# apex-kope

Repositório de assets digitais (assinaturas de e-mail, cartões de visita e fichas cadastrais) da Apex Supply e Kope Parts.

## Estrutura

- `assets/img/{apex,kope}/logos/` — logos publicados, referenciados pelos HTMLs de assinatura via URL pública.
- `email-signatures/{apex,kope}/templates/` — template-base HTML de cada marca.
- `email-signatures/{apex,kope}/[nome-sobrenome]/` — assinatura personalizada por colaborador (`index.html`, `preview.png`, `README.md`).
- `business-cards/{apex,kope}/templates/` — template-base do cartão de visita.
- `business-cards/{apex,kope}/[nome-sobrenome]/` — cartão por colaborador, com `source/` (arquivo editável) e `export/` (imagem/PDF final).
- `fichas-cadastrais/{apex,kope}/` — fichas cadastrais corporativas (DOCX/PDF) usadas em propostas comerciais.
- `archive/` — versões descontinuadas de assinaturas e cartões.

## Status

Estrutura inicial criada — pastas vazias, prontas para receber os arquivos. Conteúdo (logos, HTML, fichas) será adicionado em uma etapa posterior.
