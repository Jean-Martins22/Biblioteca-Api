<h1>Api - Biblioteca</h1>

<h2>🔖 Sobre</h2>
<p>Api sobre uma biblioteca com um foco maior em buscas, filtros, paginação e erros, criada durante o curso de APIs com Node.js e Express  📚</p>

<h2> 🚀 Tecnologias </h2>
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src= "https://img.shields.io/badge/Express.js-404D59?style=for-the-badge">
  <img src= "https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white">
</div>

<h2> 🧭Rotas </h2>
<h3> Autores 👨‍💼</h3>

- Buscar Autores: `/autores` (GET)
- Buscar Autor por Id: `/autores/:id` (GET)
- Cadastrar Autor: `/autores` (POST)
- Atualizar Autor: `/autores/:id` (PUT)
- Excluir Autor: `/autores/:id` (DELETE)

<h4>Essa é a estrutura JSON para fazer o POST e o PUT de Autores:</h4>

```json
{
    "nome": "Andrzej Sapkowski",
    "nacionalidade": "Polonês"
}
```

<h3> Livro 📖</h3>

- Buscar Livros: `/livros` (GET)
- Buscar Livros por filtros: `/livros/busca` (GET)
- Buscar Livros por Autor: `livros/busca?nomeAutor=` (GET)
- Buscar Livros por Titulo: `livros/busca?titulo=` (GET)
- Buscar Livro por Id: `/livros/:id` (GET)
- Cadastrar Livro: `/livros` (POST)
- Atualizar Livro: `/livros/:id` (PUT)
- Excluir Livro: `/livros/:id` (DELETE)

<h4>Essa é a estrutura JSON para fazer o POST e o PUT de Livros:</h4>

```json
{
    "titulo": "O Último Desejo",
    "autor": "66df38397ab61e39a53eb222",
    "editora": "WMF Martins Fontes",
    "numeroPaginas": "320",
}
```