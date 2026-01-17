
# SyntaxWear 👟

SyntaxWear é um projeto de e-commerce de front-end para uma loja de tênis e sneakers online. O design é moderno e focado na experiência do usuário, com uma estrutura semântica e estilização modular.

## ✨ Recursos

- **Design Responsivo**: Layout adaptável para desktops e dispositivos móveis.
- **Navegação Intuitiva**: Menus e categorias bem organizados para fácil acesso.
- **Seções de Destaque**:
  - **Herói**: Banner principal com chamada para ação (CTA).
  - **Categorias**: Seções visuais para diferentes estilos de tênis (Casual, Esporte, Moderno, Futurista).
  - **Grade de Produtos**: Exibição de produtos em destaque.
- **Rodapé Completo**: Inclui formulário de newsletter, links de redes sociais e navegação adicional.
- **Estrutura Semântica**: HTML5 semântico para melhor acessibilidade e SEO.

## 📂 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
ecommerce-syntaxwear/
├── css/
│   ├── base.css           # Estilos base (reset, tipografia, cores)
│   ├── variables.css      # Variáveis CSS (cores, fontes, etc.)
│   ├── reset.css          # Reset de estilos do navegador
│   └── components/
│       ├── header.css     # Estilos do cabeçalho
│       ├── hero.css       # Estilos da seção de herói
│       ├── product-category.css # Estilos das categorias de produtos
│       ├── product-grid.css   # Estilos da grade de produtos
│       └── footer.css     # Estilos do rodapé
├── images/
│   ├── banners/           # Banners da página principal
│   ├── icons/             # Ícones (SVG)
│   ├── logo/              # Logo do site
│   └── products/          # Imagens dos produtos
├── index.html             # Estrutura principal da página
└── README.md              # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Para a estrutura semântica do conteúdo.
- **CSS3**: Para estilização, utilizando uma arquitetura modular e variáveis CSS para fácil manutenção.
- **SVG**: Para ícones e logo, garantindo qualidade visual em qualquer resolução.

## 🚀 Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/dansousagtr/ecommerce-syntaxwear.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd ecommerce-syntaxwear
   ```

3. **Abra o arquivo `index.html` no seu navegador** para visualizar o site.

##🎨 Personalização

### Cores

As cores principais do site podem ser facilmente modificadas no arquivo `css/variables.css`.

### Fontes

O projeto utiliza fontes do Google Fonts. Você pode alterar as fontes importadas no `<head>` do `index.html` ou no `css/base.css`.

### Imagens

Para alterar as imagens, substitua os arquivos nas pastas correspondentes em `images/`. Certifique-se de manter os nomes dos arquivos ou atualize as referências no HTML e CSS.
