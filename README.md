# apex-kope

Repositório de assets digitais (assinaturas de e-mail, cartões de visita e fichas cadastrais) da Apex Supply e Kope Parts.

## Estrutura

- `assets/img/{apex,kope}/logos/` — logos publicados, referenciados pelos HTMLs de assinatura via URL pública.
- `assinatura-email/{apex,kope}/templates/` — template-base HTML de cada marca.
- `assinatura-email/{apex,kope}/[nome-sobrenome]/` — assinatura personalizada por colaborador (`index.html`, `preview.png`, `README.md`).
- `cartao-visita/{apex,kope}/templates/` — template-base do cartão de visita.
- `cartao-visita/{apex,kope}/[nome-sobrenome]/` — cartão por colaborador, com `source/` (arquivo editável) e `export/` (imagem/PDF final).
- `ficha-cadastral/{apex,kope}/` — fichas cadastrais corporativas (DOCX/PDF) usadas em propostas comerciais.
- `archive/` — versões descontinuadas de assinaturas e cartões.

## Status

Logos (Apex, Kope) e assinatura de e-mail de Vitória Reis (Apex + Kope) já publicados. Demais colaboradores e cartões de visita pendentes.