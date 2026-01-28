# 👟 SyntaxWear - E-commerce de Tênis e Sneakers Online

Uma loja virtual moderna e responsiva especializada em tênis e sneakers premium, desenvolvida com HTML, CSS e design responsivo.

## 📋 Visão Geral

**SyntaxWear** é uma plataforma de e-commerce elegante e intuitiva para compra de tênis e sneakers online. O site oferece uma experiência de navegação fluida com categorias de produtos diversificadas, interface mobile-first e design moderno.

### Principais Características

✅ Design responsivo e mobile-first  
✅ Interface de usuário intuitiva  
✅ Menu de navegação hambúrguer para dispositivos móveis  
✅ Hero section com call-to-action destacado  
✅ Grade de produtos em destaque  
✅ Categorias de produtos (Casual, Esporte, Moderno, Futurista)  
✅ Newsletter e redes sociais no rodapé  
✅ Links de navegação estruturados  
✅ Otimizado para SEO  

---

## 🗂️ Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html                          # Página principal do site
├── README.md                           # Este arquivo
├── .git/                               # Repositório Git
├── css/                                # Estilos CSS
│   ├── reset.css                       # Reset de estilos padrão
│   ├── variables.css                   # Variáveis CSS (cores, fontes)
│   ├── base.css                        # Estilos base e componentes globais
│   ├── layout.css                      # Layout principal (não listado acima)
│   └── components/                     # Componentes específicos
│       ├── header.css                  # Estilos do cabeçalho
│       ├── hero.css                    # Estilos da seção hero
│       ├── product-category.css        # Estilos das categorias
│       ├── product-grid.css            # Estilos da grade de produtos
│       └── footer.css                  # Estilos do rodapé
└── images/                             # Recursos de imagem
    ├── logo/                           # Logotipos
    ├── icons/                          # Ícones (hamburguer, user, bag, etc)
    ├── products/                       # Imagens dos produtos
    ├── favicons/                       # Favicons do site
    └── banners/                        # Imagens de banners
```

---

## 🎨 Seções do Site

### 1️⃣ Header (Cabeçalho)
- **Logo**: Link para página inicial
- **Menu Mobile**: Ícone hamburger para navegação em celulares
- **Navegação Principal**: Links para Masculino, Feminino e Outlet
- **Navegação Rápida**: Links para Lojas, Sobre, Conta, Ajuda e Carrinho

### 2️⃣ Hero Section
- Imagem/banner destaque principal
- Subtítulo: "Krypton One"
- Título atrativo: "Transforme qualquer passo em presença"
- Dois botões de CTA: "Ver modelos" e "Comprar"

### 3️⃣ Seção de Categorias
Grid com 4 categorias principais de produtos:
- **Casual**: Para uso diário
- **Esporte**: Para atividades atléticas
- **Moderno**: Designs atualizados
- **Futurista**: Estilos inovadores

Cada categoria possui:
- Imagem de fundo
- Overlay interativo
- Botão de navegação

### 4️⃣ Grade de Produtos (Product Grid)
- 6 cards de produtos em destaque
- Primeiro produto (Krypton One) com detalhes:
  - Título e subtítulo
  - Filtros por gênero (Feminino/Masculino)
- Layout responsivo que se adapta ao tamanho da tela

### 5️⃣ Footer (Rodapé)
- **Newsletter**: Formulário de inscrição por e-mail
- **Redes Sociais**: Instagram, WhatsApp, TikTok, Facebook
- **Navegação**: Links organizados por:
  - Masculino (categorias)
  - Feminino (categorias)
  - Outlet
  - Nossas Lojas
  - Sobre
- **Direitos Autorais**: Copyright notice

---

## 🎯 Componentes CSS

### Variáveis (`variables.css`)
Define as variáveis globais do projeto como:
- Fontes tipográficas principais
- Cores do brand
- Espaçamentos padrão

### Reset (`reset.css`)
Remove estilos padrão do navegador para uma base consistente.

### Base (`base.css`)
Estilos globais e utilitários:
- Tipografia global
- Componentes de botão (`.btn`, `.btn-outline`, `.btn-filled`)
- Configurações de espaçamento
- Responsividade base

### Componentes
Cada arquivo em `components/` estiliza uma seção específica:
- `header.css`: Navegação, logo, menu mobile
- `hero.css`: Hero section e overlays
- `product-category.css`: Categorias de produtos
- `product-grid.css`: Grade e cards de produtos
- `footer.css`: Rodapé, newsletter, redes sociais

---

## 📱 Responsividade

O projeto utiliza **Mobile-First Approach** com breakpoints em:
- **Mobile**: até 480px
- **Tablet**: até 1280px
- **Desktop**: acima de 1280px

O menu mobile implementado via checkbox permite navegação em dispositivos menores sem necessidade de JavaScript.

---

## 🎯 Ícones e Imagens

### Ícones Utilizados
- `hamburguer.svg` - Menu mobile
- `user.svg` - Minha conta
- `bag.svg` - Carrinho de compras
- `help.svg` - Ajuda/Suporte
- `instagram.svg` - Link para Instagram
- `whatsapp.svg` - Link para WhatsApp
- `tiktok.svg` - Link para TikTok
- `facebook.svg` - Link para Facebook

### Estrutura de Imagens
- **Produtos**: Imagens dos tênis e sneakers
- **Banners**: Imagens de campanhas
- **Logo**: Identidade visual da marca
- **Favicons**: Ícone do site para navegador

---

## 🚀 Como Usar

1. **Clone o repositório**:
```bash
git clone <url-repositorio>
cd ecommerce-syntaxwear
```

2. **Abra no navegador**:
   - Simplesmente abra o arquivo `index.html` no seu navegador preferido
   - Ou use um servidor local (ex: Live Server no VS Code)

3. **Customize o projeto**:
   - Edite `css/variables.css` para mudar cores e fontes
   - Adicione suas imagens em `images/`
   - Atualize links e conteúdo no `index.html`

---

## 🔧 Tecnologias Utilizadas

- **HTML5**: Marcação semântica e estrutura
- **CSS3**: Layout com Flexbox/Grid, variáveis CSS, media queries
- **Responsive Design**: Adaptável para todos os tamanhos de tela
- **Git**: Controle de versão

---

## 📝 HTML Semântico

O projeto utiliza tags semânticas HTML5:
- `<header>`: Cabeçalho da página
- `<main>`: Conteúdo principal
- `<nav>`: Navegação com aria-label
- `<section>`: Seções de conteúdo
- `<footer>`: Rodapé

Cada seção possui classes descritivas para facilitar styling e manutenção.

---

## ♿ Acessibilidade

- Meta tags de descrição para SEO
- Atributos `alt` em imagens
- Aria-labels em elementos interativos
- Navegação semântica estruturada
- Contraste adequado de cores

---

## 📊 SEO

A página inclui:
- `<meta charset="UTF-8">` para encoding correto
- `<meta name="viewport">` para responsividade
- `<title>` otimizado com palavras-chave
- `<meta name="description">` com descrição clara
- URLs amigáveis

---

## 🎨 Design System

### Tipografia
- Fonte principal definida em `variables.css`
- Escalas de tamanho consistentes (1.25rem, etc)
- Peso de fonte padrão: 400

### Cores
- Definidas como variáveis CSS
- Fácil de modificar em um único local
- Consistência visual em todo o site

### Botões
Dois estilos principais:
- `.btn-outline`: Fundo transparente, borda visível
- `.btn-filled`: Fundo preenchido
- Animações suaves em transições

---

## 📌 Próximos Passos (Sugestões)

- [ ] Implementar JavaScript para interatividade
- [ ] Conectar com backend para produtos dinâmicos
- [ ] Adicionar carrinho de compras funcional
- [ ] Implementar sistema de login/cadastro
- [ ] Adicionar filtros e busca de produtos
- [ ] Integrar com gateway de pagamento
- [ ] Melhorar animações com CSS/JavaScript
- [ ] Otimizar performance e imagens
- [ ] Implementar PWA (Progressive Web App)

---

## 📄 Licença

Este projeto é de código aberto. Sinta-se livre para usar e modificar conforme necessário.

---

## 👤 Autor

Projeto desenvolvido com ❤️ para educação e prática em desenvolvimento web.

---

## 📞 Suporte

Para dúvidas ou contribuições, abra uma issue no repositório.

**Última atualização**: 28 de janeiro de 2026