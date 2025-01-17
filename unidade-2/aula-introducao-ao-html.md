# Aula - Introdução ao HTML

## Roteiro

- Introdução ao HTML
  - XML
  - Sintaxe básica
  - Elementos básicos

## XML

- XML - Extensible Markup Language
- Criado para armazenar e transmitir informações
- Sintaxe básica:

  ```html
  <rótulo atributo="”valor”">informação</rótulo>
  ```

- Exemplo:

  ```html
  <cliente>
    <nome>Ana</nome>
    <conta tipo="”corrente”">
      <agencia>1234-5</agencia>
      <numero>98765-4</numero>
      <saldo>1000</saldo>
    </conta>
  </cliente>
  ```

## HTML

- HTML - HyperText Markup Language
- XML com rótulos (tags) específicos para descrição de hipertexto (textos ligados por hiperlinks)

## HTML - Atributos

- Elementos podem apresentar atributos

## HTML - Elementos vazios

- Elementos vazios não possuem conteúdo, não precisam de tag de fechamento
- Exemplo:

```html
<img src="imagens/gato.png" alt="Meu gato" />
```

## HTML - Primeira página

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Título da página - Aparece na aba</title>
    <meta charset="utf-8" />
  </head>
  <body>
    <h1>Título</h1>
    <p>Parágrafo</p>
  </body>
</html>
```

## HTML - Elementos básicos

**Procure na Internet os rótulos para:**

- Parágrafo
- Itálico
- Negrito
- Sublinhado
- Link
- Imagem
- Tabela
- Listas
  - Numeradas
  - Não-numeradas
- IFrames

## Cabeçalhos e Parágrafos

```html
<h1>My First Heading</h1>

<p>My First paragraph</p>
```

```html
<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>
```

## Links

```html
<a href="https://meusite.com">This is link</a>
```

## Imagem

```html
<img src="minha-imagem.png" alt="Minha imagem" width="200px" height="200px" />
```

## URLs no Site

- URL absoluta
  - Links para uma imagem externa que está hospedada em outro site
    - Exemplo: `src="https://www.w3schools.com/images/img_girl.jpg"`
- URL relativo
  - Links para uma imagem hospedada dentro o site
  - Aqui, o URL não inclui o nome de domínio
  - Se o URL começar sem uma barra, será relativo à página atual
    - Exemplo: `src="img_girl.jpg”`
  - Se a URL começar com uma barra, ela será relativa ao domínio
    - Exemplo: `src="/images/img_girl.jpg”`
  - Quase sempre é melhor usar URLs relativas. Eles não será interrompido se você alterar o
    domínio

## Linha divisória

```html
<h1>This is Heading 1</h1>
<p>This is some text</p>

<hr />

<h2>This is Heading 2</h2>
<p>This is some other text</p>

<hr />

<h3>This is Heading 3<</h3>
<p>This is some other text</p>
```

## Quebra de Linha

```html
<p>
  This is <br />
  a paragraph <br />
  with line breaks
</p>
```

## Padrão de Textos no Parágrafo

```html
<p>In HTML, spaces and new lines are ignored:</p>

<p>
  My Bonnie lies over the ocean. My Bonnie lies over the sea. My Boonie lies
  over the ocean. Oh, bring back my Bonnie to me.
</p>
```

## Parágrafo Formatado

```html
<p>The pre tag preserves both spaces and line breaks:</p>

<pre>
 My Bonnie lies over the ocean.
 
 My Bonnie lies over the sea.
 
 My Boonie lies over the ocean.
 
 Oh, bring back my Bonnie to me.
</pre>
```

## Tag Style - Cores

```html
<p>I am normal</p>
<p style="color: red;">I am red</p>
<p style="color: blue;">I am blue</p>
<p style="font-size: 56px">I am big</p>
```

## Tag Style - Cor de Fundo

```html
<body style="background-color: blue;">
  <h1>This is Heading</h1>
  <p>This is paragraph</p>
</body>
```

## Tag Style - Cor de Fundo no Parágrafo

```html
<p style="background-color: red;">This is paragraph</p>
```

## Tag Style - Cor do Texto no Parágrafo

```html
<p style="color: yellow;">This is paragraph</p>
```

## Tag Style - Tipo de Fonte

```html
<p style="font-family: Arial;">This is paragraph</p>
```

## Tag Style - Tamanho da Fonte

```html
<p style="font-size: 18px;">This is paragraph</p>
```

## Tags de Formatação

**Os elementos de formatação foram projetados para exibir tipos especiais de texto:**

- `<b>` - Texto em negrito
- `<strong>` \*\*\*\*- Texto importante
- `<i>` - Texto itálico
- `<em>` - Texto enfatizado
- `<mark>` - Texto marcado
- `<small>` - Texto menor
- `<del>` - Texto excluído
- `<ins>` - Texto
- `<sub>` - Texto subscrito
- `<sup>` - Texto sobrescrito

## Texto em Negrito

```html
<p>This text is normal</p>

<p><b>This text is bold<b></p>
```

## Marcação de Texto Importante

```html
<p>This text is normal</p>

<p><strong>This text is important<strong></p>
```

## Texto em Itálico

```html
<p>This text is normal</p>

<p><i>This text is italic<i></p>
```

## Texto com ênfase

```html
<p>This text is normal</p>

<p><em>This text is emphasized<em></p>
```

## Texto pequeno

```html
<p>This is some normal text</p>

<p><small>This is some smaller text</small></p>
```

## Texto Marcado

```html
<p>Do not forget to buy <mark>milk</mark> today</p>
```

## Texto que deve ser deletado/ignorado

```html
<p>My favorite color is <del>blue</del> red</p>
```

## Texto que deve ser inserido

```html
<p>My favorite color is <del>blue</del> <ins>red</ins></p>
```

## Texto subscrito

```html
<p>This is <sub>subscrited</sub> text</p>
```

## Texto Sobrescrito

```html
<p>This is <sup>superscrited</sup> text</p>
```

## Comentários em HTML

```html
<!-- This is a coment -->
<p>This is paragraph</p>
<!-- Comments are not displayed in the browser -->
```

## Lista não ordenada

```html
<h2>An unordetered HTML list</h2>

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

## Lista ordenada

```html
<h2>An ordetered HTML list</h2>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## Listas de Descrição

```html
<h2>A Description List</h2>

<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

## Tabelas

```html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germay</td>
  </tr>
</table>
```

## Colspan

```html
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
```

## Rowspan

```html
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan>Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
  </tr>
</table>
```

## IFrame

Um iframe HTML é usado para exibir uma página da Web dentro de uma página da Web

```html
<iframe
  src="demo.html"
  height="200"
  width="200"
  title="Iframe Example"
></iframe>
```

## Ambientes de desenvolvimento

- Desktop
  - Notepad++
  - Visual Studio Code - Extensão Live Preview
  - DevTools do navegador (Inspecionar)
- Online
  - Live Environment for Agents - tiia.com.br
  - Codepen
  - JSFiddle
  - JSBin
