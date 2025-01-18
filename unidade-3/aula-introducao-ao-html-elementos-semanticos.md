# Aula - Introdução ao HTML

## Roteiro

- Introdução
  - XML
  - Sintaxe básica
  - Elementos básicos
  - Elementos semânticos
  - Estrutura básica
- Introdução ao Github
  - Criar repositório
  - Enviar arquivos
  - Habilitar Github Pages

## HTML5 - Elementos semânticos

- Elementos semânticos = elementos com um significado
  - Cabeçalho
  - Rodapé
  - Navegação
  - Seções
  - Seção principal
  - Seção a parte
  - Artigos
- Um elemento semântico descreve claramente seu significado tanto para o navegador quanto para o desenvolvedor
- Exemplos de elementos não semânticos
  - Não diz nada sobre o seu conteúdo
  - `<div>` e `<span>`
- Exemplos de elementos semânticos
  - Define claramente o seu conteúdo
  - `<form>` e `<table>`

## `<section>`

- O elemento define uma seção em um documento
- Uma seção é um agrupamento temático de conteúdo, normalmente com um título”
- Exemplos de onde um elemento pode ser usado
  - Capítulos
  - Introdução
  - Notícias
  - Informações de contato
- Uma página da Web normalmente poderia ser dividida em seções para introdução, conteúdo e
  informações de contato

```html
<section>
  <h2>Título da seção</h2>

  <p>Texto...</p>
</section>
```

## `<article>`

- O elemento especifica conteúdo independente
- Um artigo deve fazer sentido por si só
- Exemplos de onde o elemento pode ser usado
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

- O elemento representa um contêiner para conteúdo introdutório ou um conjunto de links de
  navegação
- Um elemento normalmente contém
  - Um ou mais elementos de cabeçalho
  - Logotipo ou ícone
  - Informações de autoria

```html
<header>
  <img src="logo.png" alt="Logo" />
</header>
```

## `<footer>`

- O elemento define um rodapé para um documento ou seção
- Um elemento normalmente contém
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

- O elemento define um conjunto de links de navegação
- Observe que NEM todos os links de um documento devem estar dentro de um elemento
- O elemento destina-se apenas aos principais blocos de links de navegação

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

- O elemento define algum conteúdo além do conteúdo que é colocado em (como uma barra lateral)

```html
<aside>
  <h2>Título do conteúdo lateral</h2>

  <p>Texto...</p>
</aside>
```

## `<figure>` e `<figcation>`

- A tag especifica conteúdo independente, como ilustrações, diagramas, fotos, listagens de código, etc
- A tag define uma legenda para um elemento

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
