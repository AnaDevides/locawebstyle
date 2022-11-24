![Travis:Master](https://travis-ci.org/locaweb/locawebstyle.svg?branch=master "Travis Master")

-

![Locaweb Style with Gold color](http://i.imgur.com/3mBJPr4.png "Locaweb Style")


# Locastyle 3.0 (Barbecue)

Este é um framework front-end com padrões de comportamentos e estilos para
projetos web. O foco desta estrutura é construir interfaces administrativas
e não sites. Desenhamos essa interface com uma equipe de UX e
A parte dianteira. Também usamos essa interface em nossos próprios produtos aqui no
Locaweb.

Você pode ver todos os exemplos nesse link:
(http://opensource.locaweb.com.br/locawebstyle/documentacao/exemplos/).

### Como instalar

Você pode utilizar os estilos de localweb de varias formas:
(http://opensource.locaweb.com.br/locawebstyle/documentacao/introducao/),
mas sugerimos usar direto do nosso servidor apenas adicionando este endereço em
seu projecto:

```html
<head>
...
  <!-- Insert the CSS in HEAD -->
  <link rel="stylesheet" type="text/css" href="//assets.locaweb.com.br/locastyle/3.10.1/stylesheets/locastyle.css">
...
</head>
<body>
  <!-- Your code -->

  <!-- JQuery is a dependency -->
  <script src="http://code.jquery.com/jquery-2.0.1.min.js"></script>

  <!-- Put the JS in your footer, always after jQuery (dependency) -->
  <script src="//assets.locaweb.com.br/locastyle/3.10.1/javascripts/locastyle.js"></script>
</body>
```


#### Instalando via [bower](http://bower.io)

Para instalar o Estilo Locaweb usando o Bower:

```sh
$ bower install locawebstyle
```

#### Instalar via [npm](https://www.npmjs.com/)

Para instalar o Estilo Locaweb usando o Npm:

```sh
$ npm install locawebstyle
```

### Leia o Manual

Nós mantemos os documentos de componentes e como eles funcionam aqui;
(http://opensource.locaweb.com.br/locawebstyle/documentacao/introducao/). 

Se você usa o navegador Chrome, baixe aqui nossa extensão para acessar a documentação mais facilmente.
(http://opensource.locaweb.com.br/locawebstyle/documentacao/introducao/chrome/)


### Você quer contribuir?

Contribuir é fácil: faça um fork e comece a codificar. :-)

Temos algumas instruções para manter o código mais legível e organizado.
(http://opensource.locaweb.com.br/locawebstyle/documentacao/introducao/contribua/).

Leia aqui o guia de código do CSS:
(http://opensource.locaweb.com.br/locawebstyle/documentacao/praticas/css/)

e Leia aqui o guia de código do Javascript:
(http://opensource.locaweb.com.br/locawebstyle/documentacao/praticas/javascript/)

para manter uma boa prática deste projeto.

### Executando testes

Antes de enviar qualquer código, por favor, execute nossos testes automatizados:

```sh
$ bundle exec rake tests:run
```

Ele executará testes Jasmine e JShint.

