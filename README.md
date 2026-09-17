<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:2563EB,100:38BDF8&text=🧮%20Calculadora%20Simples&fontSize=42&fontColor=FFFFFF&fontAlignY=40&desc=Uma%20calculadora%20interativa%20desenvolvida%20com%20React%20JS&descAlignY=62&descSize=17&animation=fadeIn" width="100%"/>

<br>

# ⚛️ React JS

**Projeto acadêmico desenvolvido para praticar os fundamentos do React.**

<br>

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=111827)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=111827)
![CSS3](https://img.shields.io/badge/CSS3-38BDF8?style=flat-square\&logo=css3\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square\&logo=vite\&logoColor=white)

</div>

---

## 💻 Sobre o projeto

A **Calculadora Simples** é uma aplicação web criada com **React JS** que permite realizar operações matemáticas básicas de maneira rápida e interativa.

O usuário informa dois números, escolhe a operação desejada e, ao clicar em **Calcular**, o resultado é apresentado na própria tela.

> 📚 Este projeto foi desenvolvido como exercício em sala de aula para colocar em prática os conceitos básicos de desenvolvimento com React.

---

## 🎯 Objetivo

O exercício tem como principal objetivo entender como o **React pode ser utilizado para criar interfaces interativas**, trabalhando com dados inseridos pelo usuário e atualizando informações na tela.

Durante o desenvolvimento são praticados conceitos como:

**Componentes** → organização da aplicação
**Estados** → armazenamento dos valores
**Eventos** → interação com os botões
**Formulários** → entrada de informações
**JSX** → construção da interface
**CSS** → aparência da aplicação

---

## ✨ O que a calculadora faz?

### 🔢 Entrada de dados

O usuário pode informar:

* Primeiro número
* Segundo número

### ➕ Escolha da operação

A operação é selecionada através de um campo `<select>`.

```text
+  Adição
-  Subtração
*  Multiplicação
/  Divisão
```

### 🧮 Cálculo

Depois de preencher os campos, o usuário pode clicar em:

**CALCULAR**

A aplicação realiza a operação selecionada e mostra o resultado.

### 🧹 Limpeza

O botão:

**LIMPAR**

remove os valores preenchidos e o resultado exibido.

---

## 🧠 Funcionamento

A lógica da aplicação pode ser entendida de uma forma simples:

```text
        👤 USUÁRIO
            │
            ▼
     🔢 Digita 2 números
            │
            ▼
      🔽 Escolhe uma
        operação
            │
            ▼
       🧮 CALCULAR
            │
            ▼
       ⚙️ React processa
        a operação
            │
            ▼
       📊 RESULTADO
```

---

## 📁 Estrutura

A aplicação possui um componente específico para o formulário da calculadora:

```text
calculadora-simples/
│
├── 📂 components/
│   └── 📄 FormCalculadora.jsx
│
├── 📄 App.jsx
├── 📄 App.css
├── 📄 index.css
├── 📄 main.jsx
├── 📄 package.json
└── 📄 README.md
```

### `FormCalculadora.jsx`

É o componente responsável pela calculadora.

Nele ficam os campos, o seletor de operação, os botões e a apresentação do resultado.

---

## 🎨 Interface

A aplicação também possui uma estilização própria em **CSS**, deixando os elementos organizados e facilitando a utilização da calculadora.

O estilo trabalha principalmente com:

* 🎨 Cores e contraste
* 📦 Organização dos elementos
* 🔘 Botões
* 📝 Campos de entrada
* 🔽 Campo de seleção
* 📊 Área de resultado

---

## 🛠️ Tecnologias utilizadas

<div align="center">

### ⚛️ React JS

Biblioteca utilizada para construir a interface e os componentes.

### 🟨 JavaScript

Responsável pela lógica das operações matemáticas.

### 🎨 CSS3

Utilizado para estilizar e organizar a interface.

### ⚡ Vite

Utilizado para executar e desenvolver o projeto React.

</div>

---

## 🚀 Como executar

Primeiro, abra o projeto no **VS Code** e abra o terminal.

### 1. Instale as dependências

```bash
npm install
```

### 2. Execute o projeto

```bash
npm run dev
```

### 3. Acesse no navegador

Após executar o comando, o Vite mostrará o endereço l


