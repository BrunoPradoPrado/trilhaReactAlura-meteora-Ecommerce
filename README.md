# 🛍️ Meteora — E-commerce em React com Context API

![Meteora Banner](./public/assets/images/banner.png)

## 📖 Sobre o projeto

O **Meteora** é uma aplicação de e-commerce desenvolvida em **React**, criada ao longo do curso **React: gerencie estados globalmente com Context API** da **Alura**.

O projeto simula uma loja virtual de moda, com foco em **arquitetura de estado global**, **boas práticas de React**, **performance** e **eliminação de prop drilling**, evoluindo de um estado local para uma solução robusta com **Context API + useReducer**.

---

## ✨ Funcionalidades

- 🛒 Carrinho de compras global
- ➕ Adicionar produtos ao carrinho
- ➖ Aumentar e diminuir quantidade de produtos
- 🗑️ Remover produto do carrinho
- 📊 Cálculo automático de:
  - quantidade total de produtos
  - valor total da compra
- 🧠 Gerenciamento de estado global com **Context API**
- ⚙️ Lógica de estado centralizada com **useReducer**
- ⚡ Otimização de performance com **useMemo**
- 🧩 Hook customizado para consumo do contexto
- 🎨 Interface responsiva baseada no layout do curso

---

## 🧠 Principais conceitos aplicados

- **Context API**
  - Criação de contexto global
  - Uso do `Provider` para compartilhar estado
  - Consumo via `useContext`

- **useReducer**
  - Centralização da lógica de estado
  - Actions e reducer bem definidos
  - Evita lógica espalhada em múltiplos componentes

- **useMemo**
  - Otimização de cálculos derivados (valor total e quantidade)
  - Evita renderizações e cálculos desnecessários

- **Boas práticas**
  - Imutabilidade do estado
  - Separação de responsabilidades
  - Eliminação de *prop drilling*
  - Código mais previsível e escalável

---

## 🛠️ Tecnologias utilizadas

- **React**
- **JavaScript (ES6+)**
- **Context API**
- **React Hooks**
  - `useContext`
  - `useReducer`
  - `useMemo`
  - `useEffect`
- **Vite**
- **HTML5 & CSS3**
- **Git & GitHub**

---

## 📂 Estrutura do projeto

```txt
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