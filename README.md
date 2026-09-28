Tema
1. Cascada - O !important ignora a ordem e a especificidade normais. Removi o !important e a cor continua a mesma.

2. Especidicidade - O preço em promoção aparecia azul-escuro, não vermelho. Troquei #cardapio .preco por .preco. Agora as duas regras têm o mesmo peso e vale a ordem, e .promocao vem por último.

3. Box model - Os cartões passavam da lagura de página e apareciam barras de rolagem lateral. Adicionei box-sizing: border-box e troquei width: 100% por flex: 1 1 280px

4. Contraste - O subtítulo quase sumia no fundo branco. Mudei para #4b5563, com razão de cerca de 7,6:1 (passa AA e AAA)

5. Foco - Navegando com Tab, não dava para ver qual link do menu estava focado. Removi essa regra e criei .menu a:focus-visible com contorno laranja de 3px

6. Alinhamento - O menu estava para a direita. Removi a margem e deixei o flexbox alinhar