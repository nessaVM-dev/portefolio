### Missão 4: O Relatório

Respondam às perguntas por palavras vossas:

1. Cores:
   Escrevam a cor branca de três formas diferentes. Para que serve o quarto número em `rgba(0, 0, 0, 0.5)`?
   Resposta: [A cor branca pode ser escrita de várias formas em CSS: write - nome da cor, #ffffff - código hexadecimal, rgb(255, 255, 255) - valores de vermelho, verde e azul. Em rgba(0, 0, 0, 0.5), o último valor representa a opacidade. O valor 0.5 significa que o preto aparece com 505 de transparência.]

2. Fontes:
   Porque é que escrevemos `font-family: "Poppins", system-ui, sans-serif;` em vez de só `font-family: "Poppins";`?
   Resposta: [Usamos uma lista de fontes, como em: font-family: "Poppins", system-ui, sans-serif"; Primeiro, o navegador tenta carregar a fonte Poppins. Se ela não estiver disponível, tenta usar system-ui. Se nenhuma dessas fontes existir, utiliza uma fonte genérica sem serifa através de sans-serif. Desta forma, o texto continua legível mesmo que a fonte principal não carregue.]

3. Unidades:
   Qual é a diferença entre `rem` e `em`? Quantos píxeis tem um título com `font-size: 1.5rem`?
   Resposta: [A unidade rem depende do tamanho de letra do elemento principal, o <html>. A unidade em depende do tamanho de letra do próprio elemento ou do elemento pai. Eu considero o rem mais previsível, porque não muda tanto com a hierarquia dos elementos. O em pode aumentar ou diminuir conforme o tamanho de letra do elemento pai. Se o tamanho normal for 16px, então: 1.5rem = 1.5 x 16px = 24px, Assim, um título com font-size: 2.5rem tem normalmente 24 píxeis.]

4. Box model:
   Expliquem, com as vossas palavras, a diferença entre `padding` e `margin`. Qual dos dois mostra a cor de fundo da caixa?
   Resposta: [O padding é o espaço interior da caixa, entre o conteúdo e a borda. O margin é o espaço exterior, entre a caixa e os outros elementos da página. A cor de fundo aparece no conteúdo e no padding, mas não aparece no margin, porque o margin fica fora da caixa. Por exemplo, numa caixa com um cartão, o padding cria espaços entre o texto e a borda. O margin cria distância entre esse cartão e o catão seguinte.]

5. box-sizing:
   Uma caixa tem `width: 300px`, `padding: 20px` e `border: 5px solid`. Que largura ocupa no ecrã com `content-box`? E com `border-box`?
   Resposta: [Considerando uma caixa com `width: 300px`, `padding: 20px` e `border: 5px solid`, com content-box, os 300px representam apenas o conteúdo. Por isso, a largura total é: 300px + 20px + 20px + 5px + 5px = 350px, a caixa ocupa 350px já incluem o conteúdo, o padding e a borda. Portanto, a caixa ocupa apenas 300px no total. A largura do conteúdo será: 300px - 40px - 10px = 250px, eu considero o border-box útil porque impede que as caixas e os campos dos formulários ultrapassem a largura disponível.]

