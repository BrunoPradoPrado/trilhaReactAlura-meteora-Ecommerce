
# 👗 Meteora — E-commerce em React

🛒 Aplicação de e-commerce desenvolvida em React, com foco em gerenciamento de estado global, boas práticas e performance, utilizando Context API + useReducer.

👉 Deploy: https://https://trilha-react-alura-meteora-ecommerc.vercel.app/
👉 Curso base: React: gerencie estados globalmente com Context API — Alura

---

## ✨ Demonstração

🔗 Acesse o projeto online:  
https://https://trilha-react-alura-meteora-ecommerc.vercel.app/

Projeto responsivo, seguindo o layout proposto no curso, com foco em arquitetura e clareza de código.

---

## 📌 Sobre o projeto

O Meteora simula uma loja virtual de moda e foi construído com o objetivo de evoluir o gerenciamento de estado em React, partindo de estados locais até uma solução escalável, previsível e performática, eliminando prop drilling e centralizando regras de negócio.

---

## 🧠 Conceitos e padrões aplicados

### Context API
- Criação de estado global compartilhado
- Uso de Provider e useContext
- Eliminação de prop drilling

### useReducer
- Centralização da lógica de estado
- Actions bem definidas
- Código mais previsível e fácil de manter

### useMemo
- Otimização de valores derivados:
  - Quantidade total de itens no carrinho
  - Valor total da compra
- Evita cálculos e renderizações desnecessárias

### Boas práticas
- Imutabilidade do estado
- Separação de responsabilidades
- Hook customizado para consumo do contexto
- Código limpo e escalável

---

## 🛒 Funcionalidades

- Adicionar produtos ao carrinho
- Aumentar quantidade de produtos
- Diminuir quantidade de produtos
- Remover produtos do carrinho
- Cálculo automático de:
  - Quantidade total de produtos
  - Valor total da compra
- Gerenciamento de estado global

---

## 🛠️ Tecnologias utilizadas

- React
- JavaScript (ES6+)
- Context API
- React Hooks
  - useContext
  - useReducer
  - useMemo
  - useEffect
- Vite
- HTML5 & CSS3
- Git & GitHub
- Deploy com Vercel

---

## 📂 Estrutura do projeto
```bash
src/
 ├─ components/
 │  ├─ BarraNavegacao
 │  ├─ BannerCarrinho
 │  ├─ ListaProdutosCarrinho
 │  ├─ ResumoCompra
 │  ├─ Titulo
 │  └─ ValorFormatado
 │
 ├─ context/
 │  └─ CarrinhoContext.jsx
 │
 ├─ hooks/
 │  └─ useCarrinhoContext.jsx
 │
 ├─ reducers/
 │  └─ carrinhoReducer.jsx
 │
 ├─ mocks/
 │  └─ produtos.json
 │
 ├─ pages/
 │  ├─ Home.jsx
 │  └─ Carrinho.jsx
 │
 └─ utils/
    └─ formatadorMoeda.js
```
---

## 🚀 Aprendizados

- Organização de estado global em React
- Uso prático de Context API com useReducer
- Otimização de performance com memoização
- Estruturação de código para projetos escaláveis

---

## 👨‍💻 Autor

Bruno do Prado  
Estudante de Front-end | React  

GitHub: https://github.com/BrunoPradoPrado