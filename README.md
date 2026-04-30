# 🍷 Vinheria Agnello

## Descrição do Projeto

A Vinheria Agnello é uma empresa familiar de São Paulo com mais de 15 anos de atuação no mercado de vinhos, conhecida pelo atendimento especializado e personalizado.

Com o impacto da pandemia, a empresa decidiu criar um e-commerce para acompanhar a mudança no comportamento dos clientes, mantendo no ambiente digital uma experiência próxima à da loja física.

Este projeto tem como objetivo desenvolver um site moderno, intuitivo e focado na experiência do usuário.

---

## 🏗️ Estrutura do Projeto

O projeto é composto pelas seguintes páginas:

- **Home**: Página inicial do site, apresentando a vinheria, destaques e navegação principal;
- **Produtos**: Exibe os vinhos disponíveis, com informações como tipo, origem e descrição;
- **Curiosidades**: Página com conteúdos sobre o mundo dos vinhos, como dicas e harmonizações;
- **Equipe**: Apresenta os integrantes do projeto e/ou equipe da vinheria;
- **Contato**: Página com formulário e informações para contato;
- **CSS (style.css)**: Responsável pela estilização e layout do site.

---

## 👥 Integrantes

- João Matheus Feliciano de Bueno
- Lucas Figueiredo Kobayashi
- Pedro Viana Alves
- Jhonathan dos Santos Dourado

---

## 🔗 Link do Site

🔗 **GitHub Pages**: [https://jmfeliciano2.github.io/vinheria-agnello/](https://jmfeliciano2.github.io/vinheria-agnello/)

---

## ✨ Efeitos Visuais

Esta seção descreve os efeitos visuais avançados implementados no projeto, utilizando recursos modernos de CSS.

### 🎯 Pseudo-classes Utilizadas

| Pseudo-classe | Elemento Aplicado | Descrição |
|--------------|------------------|-----------|
| `:hover` | #menu-principal li a, #form-contato button, a | Mudança de cor e fundo ao passar o mouse |
| `:focus` | #form-contato input, #form-contato textarea | Destaque com borda dourada ao selecionar o campo |
| `:nth-child(even)` | .tabela-vinhos tr | Efeito zebrado nas linhas pares da tabela |
| `:active` | #form-contato button | Efeito de pressão ao clicar no botão |

### 🎨 Pseudo-elementos Utilizados

| Pseudo-elemento | Elemento Aplicado | Descrição |
|----------------|-------------------|-----------|
| `::before` | #lista-beneficios ul li | Ícone 🍷 antes de cada item da lista |
| `::after` | h2 | Linha decorativa dourada abaixo dos títulos |
| `::first-letter` | #sobre p | Letra capitular estilizada (3.5rem) |
| `::selection` | Texto selecionado | Cor de destaque dourada na seleção |

### 💫 Animações CSS

- **@keyframes aparecer**: Animação de entrada do conteúdo principal com opacity e translateY.

### 🔄 Transições Aplicadas

| Elemento | Transição | Duração |
|----------|-----------|---------|
| #menu-principal li a | all | 0.4s ease |
| img | transform | 0.4s ease-in-out |
| #form-contato button | 0.3s | - |

### 🎢 Transformações CSS

| Transformação | Elemento Aplicado | Efeito |
|---------------|-------------------|--------|
| translateY(-4px) | #form-contato button | Levantamento ao hover |
| skewX(-15deg) | #menu-principal li a | Inclinação no menu |
| scale(0.96) | #form-contato button | Efeito de pressão |
| rotate(2deg) + scale(1.05) | img | Rotação e zoom ao hover |

### 📁 Arquivos CSS

- **style.css**: Estilização principal e layout;
- **efeitos.css**: Arquivo dedicado aos efeitos visuais avançados (importado no final do style.css).
