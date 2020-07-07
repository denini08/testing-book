# testing-book
> Livro digital sobre Testes de Software para a disciplina IN0980/IF811 do Centro de Informática da UFPE.

[![NPM Version][npm-image]][npm-url]
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/denini08/testing-book/master?filepath=%2Fjupter)

Neste livro digital interativo abordaremos os temas X e Y.
Você pode acessar através do link: <https://github.com/denini08/testing-book>

## Instalação

### Ferramentas usadas

* [Docsify](https://docsify.js.org/#/) para gerar páginas estáticas.
* [Mybinder](https://mybinder.org/) para interação das páginas usando JupterNotebook.

### Requesitos

* Node >= 10.
* NPM >= 6.

### Instalando o Node

Para instalar o NPM basta baixar e instalar o [Node.js](https://pt.wikipedia.org/wiki/Node.js) acessando este link : https://nodejs.org/

O NPM será instalado juntamente ao Node.js.

### Instalando as dependências

Basta abrir o terminal de sua preferência e executar o comando abaixo:

```bash
npm install
```

## Executando o projeto

Para executar localmente o site do livro basta executar o comando abaixo:

```bash
npm run book
```

E o livro será executado em http://localhost:3000, caso a porta 3000 esteja em uso será possívelpossível acessar o projeto outra porta informada pelo NPM.

## Como Atualizar o Conteúdo

Estamos [jupyter notebook](https://jupyter.org/try) para criar nossos conteúdos. Apos criar o capítulo, exportamos em dois formatos: Markdown (.md) e como documento de notebook (.ipynb). 

O arquivo .md é usado pelo docsify para gerar a pagina estática, então o adicionamos no diretório /docs/capitulos/.

Enquanto o .ipynb serve para o notebook, então o adicionamos no diretório /jupter. O binder está apontado para este diretório. 

## Autores

Denini Gabriel – [@denini08](https://github.com/denini08) – dgs@cin.ufpe.br

Saulo Barros – [@dinosaulo](https://github.com/DinoSaulo) – sab2@cin.ufpe.br

## Contribuindo

1. Faça um fork do projeto (<https://github.com/denini08/testing-book/fork>)
2. Crie sua branch (`git checkout -b feature/TestesABC`)
3. Faça um commit com suas mudanças (`git commit -am 'Adicionado sobre TestesABC'`)
4. Dê um push para a branch (`git push origin feature/TestesABC`)
5. Crie um novo Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
