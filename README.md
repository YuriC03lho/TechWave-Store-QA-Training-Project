# 🧪 TechWave Store — QA Training Project

Projeto fictício de e-commerce criado para prática de **QA Manual e Automação E2E com Playwright**.

Este projeto simula um ambiente real de trabalho com bugs intencionais para treinamento de testes manuais, exploração de sistema e automação.

---

## 🎯 Objetivo

Treinar habilidades de QA em um sistema web realista contendo:

- Testes manuais funcionais
- Testes exploratórios
- Escrita de bug reports
- Criação de casos de teste
- Automação E2E com Playwright

---

## 🧱 Stack do projeto

- HTML
- CSS
- JavaScript (Vanilla)
- Playwright (testes automatizados)

---

## 📦 Funcionalidades do sistema

- Login de usuário
- Listagem de produtos
- Busca e filtros
- Carrinho de compras
- Checkout completo
- Pagamento fake
- Toast de sucesso
- Loading states

---

## 🐞 Atenção

Este sistema contém **15 a 20 bugs intencionais**, incluindo:

- Validações quebradas
- Problemas de cálculo no carrinho
- Botões sem ação
- Erros de UX/UI
- Problemas de responsividade
- Falhas de navegação
- Problemas de sessão/login
- Comportamento incorreto em refresh
- Duplicação de itens no carrinho
- Loadings infinitos

---

## 📁 Estrutura do projeto

```bash
techwave-store/
│
├── pages/
│   ├── login.html
│   ├── home.html
│   ├── products.html
│   ├── cart.html
│   └── checkout.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── auth.js
│   ├── products.js
│   ├── cart.js
│   └── checkout.js
│
├── tests/
│   ├── login.spec.js
│   ├── cart.spec.js
│   └── checkout.spec.js
│
├── docs/
│   ├── test-cases.md
│   ├── bug-reports.md
│   └── checklist.md
│
└── README.md
