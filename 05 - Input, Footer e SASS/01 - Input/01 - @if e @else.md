# @if e @else

Assim como a maioria das linguagens de programação usadas atualmente, no Sass também existe as conficionais `if` e `else`.

## @if

O padrão de escrita do if é `@if <expression> { ... }`, que controla se seu bloco é avaliado ou não (incluindo a emissão de qualquer estilo como CSS). A expressão geralmente retorna `true` ou `false` —se a expressão retornar `true`, o bloco será executado e, se a expressão retornar `false`, não será executado.

## @else

Já no caso do else, escrita é `@else { ... }`. O bloco desta regra é avaliado se a `@if` retornar falso.

## Exemplo prático

Na partial `_footer,sass`, vamos incluir um parâmetro para indicar o lado do gradiente, como ilustra o código abaixo:

```scss
@mixin bg-cores($lado, $cores...)
    @if $lado == left
        background: linear-gradient(to left, $cores)
    @else 
        background: linear-gradient(to right, $cores)
```

Se o parâmetro `$lado` tiver o conteúdo `left`, então vamos aplicar o gradiente para o lado esquerdo. Senão, vamos aplicar o gradiente para o lado direito.