# 🖼️ Projeto: Layout com Flexbox

Este projeto é uma atividade prática de HTML e CSS utilizando **Flexbox**, com base em um design fornecido no [Figma](https://www.figma.com/design/yxVI8OR6rWziXO6fIesjqw/In-Class-Practice%253A-Flexbox-Layout-(Community)).

O objetivo foi **reproduzir o layout visual** proposto, com foco no uso de Flexbox para organizar os elementos da página.

---

## 📌 Estrutura do Projeto

### 1. 📁 Container principal
- Dimensões: `1728px x 1149px`
- Imagem de fundo: `background.png`
- Função: agrupar todos os elementos da página de forma centralizada.

### 2. 🧭 Navegação (`<nav>`)
- Fundo preto
- Fonte: `Montserrat`, tamanho `19px`
- Largura: `100%`, altura: `101px`
- Itens:  
  - `products`  
  - `discounts`  
  - Ícone `diamond.svg` (56px)  
  - `our partners`  
  - `about us`  
- Layout feito com `display: flex` e `justify-content: space-around` ou semelhante.

### 3. 🎯 Hero Section
- Fundo preto
- Dimensões: `1278px x 794px`
- Textos:
  - Título principal: `"Products"`  
    - Tamanho: `64px`  
    - Cor: `#FD7D54`
  - Subtítulo: `"Affordable quality, every time."`  
    - Tamanho: `20px`

### 4. 📰 Articles (3 blocos)
- Fundo preto
- Cada `article` tem:
  - Dimensões: `293px x 440px`
  - Imagem (diferente em cada um): `ellipse_1.svg`, `ellipse_2.svg`, `ellipse_3.svg` (127px)
  - Título (`MATTE`, `SEMI-GLOSS`, `HIGH-GLOSS`)  
    - Fonte: `27px`
  - Texto descritivo  
    - Fonte: `18px`
  - Link/Texto: `"EXPLORE"`  
    - Fonte: `19px`  
    - Cor: `#41C3F6`

Os `articles` foram organizados lado a lado com `display: flex`.

### 5. ⚫ Footer
- Fundo preto
- Altura: `50px`
- Texto: `"© GEM PAINT CO"`  
  - Tamanho: `12px`

---

## 🧰 Tecnologias Utilizadas

- HTML5
- CSS3
- Flexbox
- Fonte Montserrat (importada do Google Fonts)
- Imagens e SVGs do arquivo ZIP fornecido no Classroom

---

## 📝 O que aprendi

- Como estruturar um layout com Flexbox
- Organização de seções com `display: flex`, `justify-content` e `align-items`
- Uso de fontes externas e imagens SVG
- Como aplicar cores, tamanhos e espaçamentos com CSS
- Como separar visualmente as seções da página

---

## 📂 Como visualizar

1. Clone o repositório:
```bash
git@github.com:CarlaMSilva/Layout_com_Flexbox.git
