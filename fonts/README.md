# Fonts

Coloque arquivos de fonte (por exemplo `.woff`, `.woff2`, `.ttf`) neste diretório.

Exemplo de uso (no `head`):

```
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
```

Ou copie os arquivos para `fonts/` e importe no CSS:

```
@font-face {
  font-family: 'MinhaFonte';
  src: url('../fonts/minha-fonte.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
```
