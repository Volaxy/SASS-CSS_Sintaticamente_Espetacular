Um pré-processador é um programa que construirá código CSS a partir de outra sintaxe semelhante ou quase idêntica ao CSS.Existem diversos pré-processadores, sendo que a maioria deles permite adicionar funções que não são possíveis em CSS puro, como mixins, nesting, seletores, herança, etc. É possível usar a própria sintaxe CSS mas também podemos escrever a folha de estilo com algumas particularidades, como não usar chaves e colocar elementos dentro um do outro, criando o nesting. Essas funções facilitam a manutenção e aumentam a legibilidade do CSS.

As principais vantagens dos pré-processadores são as seguintes:
* Aninhamento de código.
* Capacidade de usar variáveis.
* Capacidade de criar mixins.
* Capacidade de usar operações matemáticas/lógicas.
* Capacidade de usar loops e condições.
* Junção de vários arquivos.

Os principais pré-processadores são Sass, Less e Stylus, mas existem outros menores também. Todos eles fazem coisas similares, com algumas particularidades e uma sintaxe própria. Neste curso estamos usando o Sass, um dos mais populares e também o mais antigo, criado em 2006. [Sass](https://sass-lang.com/) significa *Syntactically Awesome Style Sheets*, e foi escrito em Ruby. O segundo pré-processador mencionado é o [LESS](https://lesscss.org/), que foi criado 3 anos depois do Sass, em 2009, inspirado pelo mesmo, e foi escrito em JavaScript. E o último pré-processador mencionado é o [Stylus](https://stylus-lang.com/), que foi lançado logo após o Less, em 2010, influenciado pelos dois anteriores, foi escrito em Node.js e combina características do Sass e do Less.

Com esses entendimentos, um conjunto de ferramentas surgiu em uma classe conhecida como “CSS Pre-processors”, cujo objetivo é estender o CSS de uma maneira que permita que uma sintaxe programática construa documentos de estilo em um formato 100% compatível com maneira CSS. Essas ferramentas introduziram variáveis, operadores, herança e uma forma de funções para permitir que designers e desenvolvedores tratassem CSS da mesma forma que tratamos HTML.