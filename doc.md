# Tutorial para criar um layout básico de página HTML

Neste tutorial, você aprenderá a criar um layout básico de página HTML usando a linguagem de marcação HTML. 

Antes de começar, certifique-se de ter um editor de texto instalado em seu computador e um navegador web para visualizar o layout da página.

## Passo 1: Crie um novo arquivo HTML

Crie um novo arquivo em branco em seu editor de texto e salve-o com a extensão ".html".

## Passo 2: Estrutura básica de uma página HTML

Comece com o código do tipo de documento HTML:

```html
<!DOCTYPE html>
```

Em seguida, adicione a estrutura básica de uma página HTML, que consiste em um elemento html contendo um elemento head e um elemento body:

```html
<html>
  <head>
    <title>Meu site</title>
  </head>
  <body>
    <!-- O conteúdo da página vai aqui -->
  </body>
</html>
```

## Passo 3: Adicione metadados à página

No elemento head, adicione metadados, como o conjunto de caracteres utilizado e as informações de exibição da página:

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu site</title>
</head>
```

## Passo 4: Adicione um cabeçalho

Em seguida, adicione um cabeçalho header com um logotipo e um botão de menu:

```html
<header>
  <img src="logo.png" alt="Meu logotipo">
  <button>Menu</button>
</header>
```

## Passo 5: Adicione links de navegação

Crie um elemento de navegação nav com links para outras páginas ou seções do site:

```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Sobre</a></li>
    <li><a href="#">Produtos</a></li>
    <li><a href="#">Contato</a></li>
  </ul>
</nav>
```

## Passo 6: Adicione o conteúdo principal da página

Em seguida, adicione um elemento main para o conteúdo principal da página:

```html
<main>
  <h1>Bem-vindo ao meu site!</h1>
  <p>Aqui você encontrará informações sobre...</p>
</main>
```

## Passo 7: Adicione informações adicionais

Em seguida, adicione um elemento aside para informações adicionais relacionadas ao conteúdo principal:

```html
<aside>
  <h2>Sidebar</h2>
  <ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
    <li><a href="#">Link 3</a></li>
  </ul>
</aside>
```

## Passo 8: Adicione um rodapé

Por fim, adicione um rodapé footer com informações de autoria e direitos autorais:

```html
<footer>
  <p>&copy; 2023 Meu site. Todos os direitos reservados.</p>
</footer>
```

## Passo 9: Salve e visualize a página

# Adicionando estilo à sua página HTML:

1. Crie um novo arquivo em branco e salve-o com a extensão ".css". Por exemplo, "style.css".
2. Adicione o código CSS que deseja aplicar à sua página HTML. Por exemplo, você pode definir o estilo do cabeçalho da página com o seguinte código CSS:
```css
header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header img {
  height: 50px;
}

header button {
  background-color: transparent;
  color: #fff;
  border: none;
  font-size: 20px;
}
```
3. Salve o arquivo CSS.
4. Em seu arquivo HTML, adicione a tag link dentro do elemento head e especifique o caminho para o arquivo CSS:
```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu site</title>
  <link rel="stylesheet" href="style.css">
</head>
```
Agora, a página HTML será estilizada com as regras CSS definidas no arquivo "style.css".

# Adicionando interatividade à sua página HTML:

1. Crie um novo arquivo em branco e salve-o com a extensão ".js". Por exemplo, "script.js".
2. Adicione o código JavaScript que deseja executar em sua página HTML. Por exemplo, você pode criar uma função que altera o texto de um elemento HTML:
```javascript
function alterarTexto() {
  var elemento = document.getElementById("texto");
  elemento.innerHTML = "Novo texto!";
}
```
3. Salve o arquivo JavaScript.
4. Em seu arquivo HTML, adicione a tag script dentro do elemento body e especifique o caminho para o arquivo JavaScript:
```html
<body>
  <main>
    <h1 id="texto">Meu texto</h1>
    <button onclick="alterarTexto()">Clique para alterar o texto</button>
  </main>
  <script src="script.js"></script>
</body>
```
Agora, quando o usuário clica no botão, a função "alterarTexto()" é chamada e o texto do elemento HTML com o id "texto" é alterado para "Novo texto!".

Com essas técnicas básicas, você pode criar páginas HTML mais avançadas e interativas. Lembre-se de que a prática é a chave para aprimorar suas habilidades de desenvolvimento web.