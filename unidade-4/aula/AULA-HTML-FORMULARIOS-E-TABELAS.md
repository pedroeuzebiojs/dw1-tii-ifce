# Aula - HTML - Formulários e Tabelas

## Formulários

Um formulário HTML é usado para coletar a entrada do usuário. A entrada do usuário é na maioria das vezes enviado para um servidor para processamento.

```html
<form>
  <fieldset>
    <legend>Formulário</legend>

    <label for="email">E-mail</label>
    <input type="email" name="email" id="email" />

    <label for="senha">Senha</label>
    <input type="password" name="senha" id="senha" />

    <button>Enviar</button>
  </fieldset>
</form>
```

## GET x POST

**Notas sobre o GET:**

- Acrescenta os dados do formulário à URL, em pares nome/valor
- NUNCA use GET para enviar dados confidenciais! (os dados do formulário enviado são visíveis no URL!)
- O comprimento de um URL é limitado (2048 caracteres)
- O GET é bom para dados não seguros, como cadeias de caracteres de consulta no Google

**Notas no POST:**

- Acrescenta os dados do formulário dentro do corpo da solicitação HTTP (o enviado os dados do formulário não são mostrados no URL)
- O POST não tem limitações de tamanho e pode ser usado para enviar grandes quantidades de dados.

## Inputs

- Diferentes tipos
  - Texto, número, data, etc
- Devem ter um nome
- Devem ter um rótulo (label)

```html
<input type="text" name="texto" />
<input type="number" name="numero" />
<input type="date" name="data" />
```

## Rótulos (labels)

```html
<label for="email">E-mail</label> <br />
<input type="email" name="email" id="email" />
```

## Radio Buttons

```html
<input type="radio" name="tech" id="html" /> <label for="html">HTML</label>
<input type="radio" name="tech" id="css" /> <label for="css">CSS</label>
<input type="radio" name="tech" id="js" /> <label for="js">JS</label>
```

## Caixas de seleção

```html
<input type="checkbox" name="techs" id="html" value="HTML" />
<label for="html">HTML</label>
<input type="checkbox" name="techs" id="css" value="CSS" />
<label for="css">CSS</label>
<input type="checkbox" name="techs" id="js" value="JS" />
<label for="js">JS</label>
```

## Botões

```html
<input type="submit" value="Enviar" />
```

ou:

```html
<button type="submit">Enviar</button>
```

## Select

```html
<label for="area">Selecione sua área de atuação: </label>
<select id="area" name="area">
  <option value="front-end">Front-end</option>
  <option value="back-end">Back-end</option>
  <option value="full-stack">Full Stack</option>
</select>
```

## Textarea

```html
<label for="sobre">Fale um pouco sobre você: </label>
<textarea name="sobre" id="sobre" cols="30" rows="10"></textarea>
```

## Fieldset e Legend

```html
<form>
  <fieldset>
    <legend>Formulário</legend>
  </fieldset>
</form>
```

## Password

```html
<label for="senha">Digite sua senha: </label>
<input type="password" name="senha" id="senha" />
```

## Campo de Data

```html
<label for="senha">Digite sua data de aniversário: </label>
<input type="date" name="data-de-aniversario" id="data-de-aniversario" />
```

## Campo de Data e Hora

```html
<label for="senha">Digite o horário de hoje: </label>
<input type="datetime-local" name="horario-de-hoje" id="horario-de-hoje" />
```

## Campo de e-mail

```html
<label for="email">Digite seu e-mail: </label>
<input type="email" name="email" id="email" />
```

## Tabelas

- Apresentar dados tabulares
- Não deve ser usado para layout

```html
<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>E-mail</th>
      <th>Senha</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <th>1</th>
      <th>pedroeuzebio@gmail.com</th>
      <th>12345678</th>
    </tr>
    <tr>
      <th>2</th>
      <th>ataslanmonteiro@gmail.com</th>
      <th>87654321</th>
    </tr>
  </tbody>
</table>
```
