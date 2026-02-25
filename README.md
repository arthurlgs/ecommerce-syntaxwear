# Ecommerce SyntaxWear

Projeto front-end estático de uma loja de tênis e sneakers, construído com HTML e CSS responsivo. Criado durante o curso DEVQUEST 2.0 (DEVEMDOBRO)

Resumo
------
- Objetivo: landing page de e‑commerce com hero, categorias, grid de produtos e rodapé responsivos.
- Status: protótipo estático (apenas HTML/CSS).

Estrutura principal
------------------
- `index.html` — página principal.
- `css/` — estilos e variáveis.
	- `css/reset.css`
	- `css/base.css`
	- `css/variables.css`
	- `css/components/` — estilos por componente (header, hero, product-category, product-grid, footer, etc.).
- `images/` — logos, ícones e imagens de produtos (`logo/`, `icons/`, `products/`, etc).

Responsividade e usabilidade
----------------------------
Este projeto foi desenvolvido com foco em experiências móveis e desktop. Principais pontos:

- Layout fluido: grades e containers usam unidades responsivas e breakpoints para ajustar a exibição em telas pequenas (celular), médias (tablet) e grandes (desktop).
- Navegação simples: cabeçalho com logo e menu adaptativo para dispositivos móveis (ícone "hamburguer") que facilita acessar categorias sem poluir a tela.
- Hierarquia visual clara: uso de tipografia, contrastes e tamanhos de botão (`btn-outline`, `btn-filled`) para guiar o usuário às ações principais (ver modelos, comprar).
- Acessibilidade básica: imagens possuem textos alternativos (`alt`) e o HTML usa marcação semântica (`header`, `nav`, `main`, `section`, `footer`) para melhorar a navegação por leitores de tela.
- Performance e assets: imagens otimizadas para mobile e desktop web na pasta `images/`.

Como obter o código e abrir localmente
-------------------------------------
1. Clone o repositório pela primeira vez (substitua `<URL-REPO>` pelo URL do seu repositório):

```bash
git clone <URL-REPO>
cd ecommerce-syntaxwear
```

2. Se já tiver o repositório localmente, atualize-o com `git pull`:

```bash
# puxe as últimas alterações da branch remota (ex.: main)
git pull origin main

# ou apenas
git pull
```

3. Depois de ter os arquivos localmente, abra `index.html` no navegador ou utilize um servidor local à sua preferência.