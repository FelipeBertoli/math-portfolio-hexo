# 📐 Math Portfolio – Hexo

Projeto de portfólio matemático desenvolvido com o framework [Hexo](https://hexo.io/), utilizado para publicar conteúdos e anotações de matemática de forma organizada e visualmente atrativa.

🔗 Acesse o site: [https://felipebertol.github.io/hexo-math-portfolio/](https://felipebertol.github.io/hexo-math-portfolio/)

---

## 📌 Sobre o projeto

Este projeto tem como objetivo centralizar e compartilhar conteúdos de matemática estudados durante a graduação, facilitando a consulta e organização dos temas. Utilizando o Hexo, é possível gerar páginas estáticas com ótimo desempenho e visual limpo, ideal para esse tipo de conteúdo.

---

## 🚀 Tecnologias utilizadas

- **Hexo** – Framework para geração de sites estáticos  
- **Markdown** – Formatação dos conteúdos  
- **HTML/CSS** – Estruturação e estilização das páginas  
- **JavaScript (mínimo)** – Recursos de navegação e interatividade do tema  

---

## 🧩 Funcionalidades

- 📘 Publicação de artigos matemáticos  
- 🧮 Organização por categorias e tags  
- 🔍 Barra de busca integrada (dependente de tema/plugin)  
- 🧠 Temas customizáveis para visual mais limpo  
- 🌐 Deploy automatizado com GitHub Pages  

---

## 📦 Como executar o projeto

<details>
  <summary><strong>1. Clonar o repositório</strong></summary>

```bash
git clone https://github.com/FelipeBertoli/math-portfolio-hexo.git
cd math-portfolio-hexo
```
</details>

<details>
  <summary><strong>2. Instalar as dependências</strong></summary>

É necessário ter o [Node.js](https://nodejs.org/) instalado.

```bash
npm install
```
</details>

<details>
  <summary><strong>3. Rodar localmente</strong></summary>

```bash
npx hexo server
```

Acesse em: `http://localhost:4000`
</details>

<details>
  <summary><strong>4. Fazer deploy</strong></summary>

Configure o arquivo `_config.yml` e utilize:

```bash
npx hexo deploy
```
</details>

---

## 📁 Organização

- `source/_posts`: onde ficam os posts em markdown  
- `themes`: pasta com os temas instalados  
- `_config.yml`: configurações globais do Hexo  
- `scaffolds`: estrutura base para novos posts  

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais informações.
