# 🛒 Mercado Livre Clone

> réplica front-end da home do Mercado Livre, com busca de produtos em tempo real, sem frameworks

```text
┌─ FICHA TÉCNICA ─────────────────────────────
│ PROJETO   Mercado Livre Clone
│ STATUS    ● Ativo
│ STACK     HTML5 · CSS3 · JavaScript
│ TIPO      Web / Front-end
│ DEMO      mercado-livre-v2.vercel.app
└──────────────────────────────────────────────
```

🔗 [Ver demo](https://mercado-livre-v2.vercel.app) · 📂 parte do [Portfólio de Edilson Moraes](https://porfifolio-theta.vercel.app)

## Sobre o projeto

Clone front-end da página inicial do Mercado Livre, feito durante o curso DevClub como desafio de fixação de HTML, CSS e JavaScript puro. A página monta a listagem de produtos ("Ofertas do dia") dinamicamente a partir de um array de dados em JavaScript, renderizando cards com imagem, título, preço formatado em real (`Intl`/`toLocaleString`) e percentual de desconto. O layout é construído com CSS Grid (`auto-fit`/`minmax`) para os cards e usa media queries em dois breakpoints (768px e 480px) para se adaptar a tablets e celulares.

## Funcionalidades

- Header fixo com logo e campo de busca
- Catálogo de 12 produtos renderizado dinamicamente via JavaScript (`renderProduct`)
- Busca por texto que filtra os produtos pelo título em tempo real (`searchProducts`)
- Formatação de preços em Real (BRL) com `toLocaleString`
- Exibição de percentual de desconto por produto
- Grid de produtos responsivo, com breakpoints dedicados para tablet e mobile
- Efeito de hover nos cards de produto

## Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Como rodar localmente

```bash
# clone este repositório
git clone https://github.com/Edilson-5762/mercado-livre-v2.git

# entre na pasta do projeto
cd mercado-livre-v2

# abra o index.html diretamente no navegador
# ou sirva com uma extensão como Live Server (VSCode)
```

---

**[Edilson Moraes](https://github.com/Edilson-5762)** — Full Stack Developer · Data Analyst em formação
[Portfólio](https://porfifolio-theta.vercel.app) · [LinkedIn](https://www.linkedin.com/in/edilson-moraes-047128408)
