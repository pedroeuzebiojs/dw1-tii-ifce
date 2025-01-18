# Aula - Introdução à Internet

## Apresentação da disciplina

- Disciplina prática
- Protagonismo do aluno
- Pesquisa
- Digitação
- Formato EaD
  - Ler material
  - Fazer tarefa
  - Pesquisar
  - Encontros para tirar dúvidas

## O que é a Internet?

- Redes ponto-a-ponto
  - Conexão direta entre dois equipamentos
- Redes locais
  - Equipamentos centralizador: switch/roteador
  - Equipamentos precisam de um identificador na rede: número IP
- Redes de redes: Internet
  - Acordo entre empresas para conexão entre suas redes privadas

## Uso da Internet

**Diferentes programas e protocolos de comunicação:**

- E-mail: IMAP/POP3
- Transferência de arquivos: FTP
- Navegador web: HTTP/HTTPS
- Músicas, Vídeos: HTTP, RTMP

## Identificação - IP e Portas

- Identificar equipamentos na rede
  - Número IP. Ex: 192.168.0.1
- Identificar programa no equipamento
  - Portas
    - SSH: 22
    - FTP: 23
    - HTTP: 80
    - HTTPS: 443

## Identificação - Nome de Domínio

- Ao invés de decorarmos IPs, usamos nomes de domínio.
- Paga-se pelo serviços de DNS (Domain Name System)
  - IP é substituído por um Domínio

## Arquitetura Cliente-servidor

- Cliente faz requisições
- Servidor responde

## Sites e Páginas web

- Sites são arquivos relacionados através de hiperlinks
- Principais linguagens
  - HTML - descreve a estrutura
  - CSS - descreve o visual
  - JavaScript - descreve a interatividade

## HTML

**Sintaxe básica:**

```html
<rótulo>conteúdo</rótulo>
```

**Exemplo:**

```html
<button>Clique aqui</button>
```

## CSS

**Sintaxe básica:**

```css
seletor {
  propriedade: valor;
}
```

**Exemplo:**

```css
button {
  color: red;
}
```

## JavaScript

**Exemplo:**

```js
const button = document.querySelector("button");

function olaMundo() {
  alert("Olá, Mundo!");
}

button.addEventListener("click", olaMundo);
```

## Ambientes de desenvolvimento

- Desktop
  - Notepad++
  - Visual Studio Code
  - DevTools do navegador
- Online
  - Codepen
  - JSFinddle
  - JSBin
