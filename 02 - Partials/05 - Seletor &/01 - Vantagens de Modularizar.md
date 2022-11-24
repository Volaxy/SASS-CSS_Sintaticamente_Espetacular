Quando você está desenvolvendo, geralmente é útil ter muitas folhas de estilo menores em vez de uma enorme. Quem quer ler uma folha de estilo de mil linhas? No entanto, carregar muitos arquivos CSS pequenos pode ser um problema para o desempenho da web. Se você tiver dez folhas de estilo em uma página específica, isso pode tornar os tempos de carregamento da página muito mais lentos porque cada folha de estilo precisa de uma solicitação separada para carregar.

A importação é um processo pelo qual muitos arquivos são transformados em poucos arquivos. O Sass tem um pequeno truque pelo qual as folhas de estilo menores são importadas para a maior à medida que ela é compilada em CSS.

Ao digitar `@import` , seguido pelo nome do arquivo Sass que deseja importar, você pode misturar arquivos Sass e SCSS à vontade com importações - é tudo a mesma coisa. Basta dizer `@import "nome_do_arquivo"`; e pronto!

> Por padrão, o compilador Sass gera arquivos CSS de todos os seus arquivos sass – mesmo os “pequenos”.

Se você não quiser que um arquivo Sass gere um arquivo CSS correspondente, basta iniciar o nome do arquivo com um undeline.