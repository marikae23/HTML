# HTML
**Olá!**
Primeiramente, aqui estão algumas das tags HTML mais comuns e suas funções básicas:

`<html>`: Envolve todo o conteúdo de uma página da web.

`<head>`: Contém informações sobre a página da web que não são visíveis na janela do navegador, como a codificação de caracteres e o título da página.

`<body>`: Contém todo o conteúdo visível de uma página da web, como texto, imagens e links.

`<h1>` a `<h6>`: Usados para criar títulos e subtítulos em uma página da web.
  
`<p>`: Usado para criar parágrafos de texto.
  
`<a>`: Usado para criar links para outras páginas da web ou para partes da mesma página.
  
`<img>`: Usado para inserir imagens em uma página da web.
  
`<ul>` e `<li>`: Usados para criar listas não ordenadas de itens.

## Passo-a-passo
1. Crie um arquivo HTML vazio e salve-o com a extensão ".html".

2. Adicione a tag <!DOCTYPE html> no topo do arquivo. Isso informa ao navegador que o arquivo é um documento HTML5.

3. Em seguida, crie uma tag <html> e inclua dois atributos: lang e dir. O atributo lang define o idioma do conteúdo e o atributo dir define a direção do conteúdo. Por exemplo, <html lang="pt-br" dir="ltr"> define o idioma como Português do Brasil e a direção como da esquerda para a direita.

4. Dentro da tag <html>, adicione duas seções principais: <head> e <body>. O <head> contém informações sobre o documento, como o título da página, a descrição e as informações de estilo. O <body> contém o conteúdo real da página.

5. Dentro da tag <head>, adicione as seguintes tags: <meta>, <title>, e <link>. A tag <meta> fornece informações adicionais sobre o documento, como a codificação de caracteres e as palavras-chave para motores de busca. A tag <title> define o título da página que aparece na aba do navegador. A tag <link> é usada para vincular
  
## Demonstração visual
Um exemplo simples de código HTML que inclui uma imagem, um parágrafo e um link:
 ```
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <title>Exemplo de Página HTML</title>
  </head>
  <body>
    <h1>Bem-vindo ao meu site!</h1>
    <img src="https://via.placeholder.com/150" alt="Imagem de exemplo">
    <p>Este é um exemplo simples de uma página HTML. Aqui você pode encontrar informações sobre mim e minhas habilidades.</p>
    <a href="https://www.linkedin.com/in/exemplo/">Clique aqui para visitar meu perfil no LinkedIn</a>
  </body>
</html>
```
