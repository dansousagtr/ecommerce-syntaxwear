# Notas do Projeto — Preparação

## Paleta de cores (exemplo)
- Primary: `#0E7AFE` (azul)
- Accent: `#FF6B6B` (coral)
- Background: `#FFFFFF`
- Text: `#111827`
- Muted: `#6B7280`

> Ajuste as cores no `css/base.css` nas variáveis `:root`.

## Tipografia
- Sugestão: `Inter` para textos e `Playfair Display` para títulos (ou `Roboto` como alternativa).
- Como importar via Google Fonts (exemplo):

  1. Abra https://fonts.google.com
  2. Busque por `Inter` e `Playfair Display`
  3. Use o link de import ou baixe as fontes e coloque os arquivos `.woff2` em `fonts/`.

Exemplo de import no `head` do `index.html` (ou via `@import` em CSS):

```
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
```

## Imagens necessárias (sugestão)
- `assets/images/banner.jpg` — banner principal (desktop)
- `assets/images/banner-mobile.jpg` — banner mobile
- `assets/images/product-01.jpg`, `product-02.jpg`, etc. — imagens de produtos
- `assets/icons/cart.svg`, `search.svg`, `menu.svg`, `user.svg` — ícones

Coloque as imagens finais em `assets/images/` e ícones em `assets/icons/`.

## Próximos passos
- Baixar e instalar/importar as fontes desejadas.
- Inserir imagens reais em `assets/images`.
- Implementar componentes e layout com os arquivos CSS criados.
