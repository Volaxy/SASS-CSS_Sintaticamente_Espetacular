# SASS - CSS Sintaticamente Espetacular

Curso da Alura sobre a linguagem SASS, que da "super poderes" para o CSS.

## Objetivo Final &#x1F3AF;

Desemvolver um Alura SPA usando o SASS para criar o estilo da página.

URL do curso -> [SASS - CSS Sintaticamente Espetacular](https://cursos.alura.com.br/course/sass-css-sintaticamente-espetacular)

![SASS - CSS Sintaticamente Espetacular](https://www.alura.com.br/assets/api/share/curso-sass-css-sintaticamente-espetacular.png)

## Links Úteis &#x1F517;
* [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass) - Extensão do VS Code para compilar arquivos Sass.
* [Color Hunt](https://colorhunt.co/) - Site para se inspirar para pegar paletas de cores.
* [Arquivos Base](https://github.com/alura-cursos/alura-spa/archive/refs/heads/projeto_inicial.zip) - Arquivos necessários para a construção do projeto.

## Siglas &#x1F5FA;
* **SASS** - *Syntactically Awesome Style Sheets* - Folhas de estilo sintaticamente impressionantes.

## Atalhos &#x2328;
*

## 01 - Primeiros Passos com SASS &#x1F516;
* Entendemos o que é Sass e como podemos manter nossas folhas de estilos criando variáveis e funções.
* Instalamos o compilador do [Sass através de uma extensão do VSCode](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass).
* Vimos que podemos aninhar as classes de estilos com Sass, semelhante ao código HTML.

### 01 - Instalando o SASS no VS Code
* Utilizar a extensão **Live Sass Compiler** para transcrever o código **Sass** para código **CSS**.
* Compilar o arquivo **Sass**.
* Estrutura básica de um projeto utilizando **Sass**.

### 02 - Aninhamento
* Declarar estilos para uma classe que esteja dentro de outra.

### 03 - Variáveis
* Criar variáveis com `$`.
* Utilizar as variáveis criadas.

### 04 - Mixin
* Criar uma função com `@mixin`.
* Usar o **mixin** com `@include`.
* Passar argumentos para os parâmetros da função.

***

## 02 - Partials &#x1F516;
* Organizamos os arquivos de estilos criando partials, que contêm pequenos trechos de CSS que podem ser incluídos em outros arquivos Sass.
* Modularizamos o CSS tornando as folhas de estilos mais fáceis de manter.
* Estilizamos o navbar e incluímos o efeito `hover` através do operador `&`.

### 01 - Iniciando o Projeto
* Configurar o projeto.

### 02 - Partial
* Nomear os arquivos **partial** com a convensão de `_`.
* Importar outros arquivo **SASS** com o `@import`.

### 03 - Componentes
* Criar a pasta *components* para arquivos SCSS de componentes específicos da página.

### 04 - navbar Partial
* Criar o arquivo de *variables.scss* para armazenar as variáveis que serão usadas no site.

### 05 - Seletor &
* Usar o seletor `&` para utilizar o elemento acima.
* Conceitos de **Modularização**.
* O que são pré-processadores CSS.