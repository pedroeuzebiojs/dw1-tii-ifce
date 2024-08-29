# Aula - Introdução ao HTML - Elementos Semânticos

## HTML5 - Elementos semânticos

- Elementos semânticos = elementos com um significado
  - Cabeçalho
  - Rodapé
  - Navegação
  - Seções
  - Seção principal
  - Seção a parte
  - Artigos
- Um elemento semântico descreve claramente seu significado tanto para o navegador quanto para o desenvolvedor.
- Exemplos de elementos não semânticos: Não diz nada sobre o seu conteúdo.`<div>, <span>`
- Exemplos de elementos semânticos: Define claramente o seu conteúdo. `<form>, <table>, <article>`
- O elemento define uma seção em um documento. `<section>`
- Uma seção é um agrupamento temático de conteúdo, normalmente com um título"
- Exemplos de onde um elemento pode ser usado:`<section>`
  - Capítulos
  - Introdução
  - Notícias
  - Informações de contato
- Uma página da Web normalmente poderia ser dividida em seções para introdução, conteúdo e informações de contato

## `<section>`

```html
<section>
  <h2>Título da seção</h2>

  <p>Texto...</p>
</section>
```

## `<article>`

- O elemento especifica conteúdo independente `<article>`
- Um artigo deve fazer sentido por si só
- Exemplos de onde o elemento pode ser usado: `<article>`
  - Postagens no fórum
  - Postagens no blog
  - Comentários dos usuários
  - Cartões de produto
  - Artigos de jornal

```html
<article>
  <h2>Título do artigo</h2>

  <p>Texto...</p>
</article>
```

## `<header>`

- O elemento representa um contêiner para conteúdo introdutório ou um conjunto de links de navegação.`<header>`
- Um elemento normalmente contém: `<header>`
  - Um ou mais elementos de cabeçalho (`<h1>` - `<h6>`)
  - Logotipo ou ícone
  - Informações de autoria

```html
<header>
  <img src="logo.png" alt="Logo" />
</header>
```

## `<footer>`

- O elemento define um rodapé para um documento ou seção. `<footer>`
- Um elemento normalmente contém: `<footer>`
  - Informações de autoria
  - Direitos autorais informação
  - Informações de contato
  - Mapa do site
  - Voltar ao topo dos links
  - Documentos relacionados

```html
<footer>
  <p>Criado com ❤️ por Pedro Euzebio</p>
</footer>
```

## `<nav>`

- O elemento define um conjunto de links de navegação.`<nav>`
- Observe que NEM todos os links de um documento devem estar dentro de um elemento. O elemento destina-se apenas aos principais blocos de links de navegação. `<nav>`

```html
<nav>
  <ul>
    <li>
      <a href="#home">Home</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </li>
  </ul>
</nav>
```

## `<aside>`

- O elemento define algum conteúdo além do conteúdo que é colocado em (como uma barra lateral). `<aside>`

```html
<aside>
  <h2>Título do conteúdo lateral</h2>

  <p>Texto...</p>
</aside>
```

## `<figure>`, `<figcaption>`

- A tag especifica conteúdo independente, como ilustrações, diagramas, fotos, listagens de código, etc. `<figure>`
- A tag define uma legenda para um elemento. `<figcaption>`

```html
<figure>
  <img src="imagem.png" alt="Imagem" />
  <figcaption>Imagem</figcaption>
</figure>
```

## HTML - Estrutura básica

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>

  <body>
    <header>
      <img src="logo.png" alt="Logo" />
    </header>

    <nav>
      <ul>
        <li>
          <a href="#home">Home</a>
          <a href="#sobre">Sobre</a>
          <a href="#contato">Contato</a>
        </li>
      </ul>
    </nav>

    <main>
      <section>
        <h2>Título da seção</h2>

        <p>Texto...</p>
      </section>

      <aside>
        <h2>Título do conteúdo lateral</h2>

        <p>Texto...</p>
      </aside>
    </main>

    <footer>
      <p>Criado com ❤️ por Pedro Euzebio</p>
    </footer>
  </body>
</html>
```
