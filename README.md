# Beer Festival Reserve 🍺

Projeto **front-end** de um sistema simples de **autenticação/reserva** para um festival de cerveja, criado para praticar **HTML e CSS** com organização de pastas e estilos globais reutilizáveis.

O foco do projeto é entregar uma base visual pronta para integração futura com backend (caso você queira), contendo páginas de **Login**, **Criar conta** e **Recuperar senha**.

---

## 🚀 Páginas

- **Login** (`index.html`)
- **Criar conta** (`pages/newaccount.html`)
- **Recuperar senha** (`pages/forgotpass.html`)

---

## ✅ Funcionalidades (front-end)

- Layout consistente entre páginas
- Formulários de login e cadastro
- Página de recuperação de senha (envio de link – protótipo)
- CSS organizado com:
  - estilos globais (normalize, elements, variables, fonts)
  - estilos específicos por página

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**

> Observação: este projeto é visual/front-end (sem backend).

---

## 📁 Estrutura do Projeto

```text
Beer-Festival-Reserve/
│
├── assets/
│   ├── css/
│   │   ├── global/
│   │   │   ├── global.css
│   │   │   ├── normalize.css
│   │   │   ├── elements.css
│   │   │   ├── variables.css
│   │   │   └── fonts.css
│   │   │
│   │   └── pages/
│   │       ├── index/
│   │       │   └── index.css
│   │       ├── newaccount/
│   │       │   └── newaccount.css
│   │       └── forgotpass/
│   │           └── forgotpass.css
│   │
│   └── images/
│       └── (imagens e ícones do projeto)
│
├── pages/
│   ├── newaccount.html
│   └── forgotpass.html
│
├── index.html
└── README.md
