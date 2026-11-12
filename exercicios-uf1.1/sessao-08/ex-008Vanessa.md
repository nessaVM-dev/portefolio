### Missão 3: O Relatório

Respondam às seguintes questões por palavras vossas:

1. As Três Formas de Inclusão de CSS:
   Quais são as três formas de aplicar CSS a um documento HTML (inline, interno e externo) e por que razão o CSS externo é considerado a melhor prática da indústria?
   Resposta: [Existem três formas principais de aplicar CSS: inline, interno e externo. O CSS inline é colocado diretamente no elemento HTML, usando o atributo style. É útil para alterações muito específicas, mas pode deixar o código desorganizado. O CSS interno é escrito dentro da tag <stile>, normalmente no <head> da página. Funciona bem para uma página, mas não é tão prático quando existem vários ficheiros HTML. O CSS externo fica num ficheiro separado, como eztilo.css, e é ligado através da tag <link>. Esta é a melhor opção porque separa o conteúdo do design, facilita a manutenção e permite aplicar os menbros estilos em vários páginas.]

2. Seletores de Tipo vs Classe vs ID:
   Expliquem a diferença prática entre um seletor de tipo (`p`), um seletor de classe (`.destaque`) e um seletor de identificador (`#formulario`), dando um exemplo de quando se deve usar cada um.
   Resposta: [O seletor de tipo, como p, aplica o mesmo estilo a todos os elementos desse tipo. Por exemplo, posso usar p para definir a cor e o tamanho de todos os parágrafos. O seletor de classe, como .destaque, pode ser aplicado a vários elementos. É útil para reutilizar um estilo, por exemplo, em vários cartões ou caixas de aviso. O seletor de ID, como 3agendamento, deve ser usado num elemento único da página. Neste exercício, pode servir para identificar e estilizar apenas a secção do formulário de agendamento.]

3. Seletores Descendentes:
   Qual é a diferença entre a regra `nav, a { ... }` (com vírgula) e a regra `nav a { ... }` (com espaço)?
   Resposta: [A regra nav, a {...} aplica o estilo aos elementos nav e a separadamente. Ou seja, altera todos os menus nav e todos os links a da página. Já a regra nav a {...} aplica o estilo apenas aos links que estão dentro do elemento nav. Por isso, é mais indicada para estilizar os links específicos do menu sem alterar todos os outros links da página.]

4. Depuração com DevTools:
   Como é que o separador "Styles" das Ferramentas de Programador (DevTools) ajuda um programador a identificar problemas quando uma regra de estilo não está a funcionar?
   Resposta: [As DevTools, principalmente o separador Style, ajudam a descobrir problemas no CSS. Ao selecionar um elemento, consigo ver quais regras estão a ser aplicadas e quais estão a ser ignoradas. Se uma propriedade aparecer riscada, significa normalmente que outra regra tem maior prioridade ou que foi escrita mais tarde. Também posso verificar se o seletor está correto, se o ficheiro CSS foi carregado e testar alterações diretamente no navegador. Depois de encontrar o problema, tenho de corrigir o ficheiro CSS original, porque as alterações feitas no DevTools são apenas tempórarias.]

     
