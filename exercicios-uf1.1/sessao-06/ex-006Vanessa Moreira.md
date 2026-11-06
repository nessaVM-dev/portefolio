### Missão 3: O Relatório

Respondam às seguintes questões por palavras vossas:

1. A diferença entre `name` e `id`:
   Qual é o papel do atributo `id` e do atributo `name` num campo de formulário? O que acontece aos dados introduzidos pelo utilizador quando um campo não tem o atributo `name`?
   Resposta: [O atributo id serve para identificar um campo na página e permite fazer a ligação com a etiqueta <label>. Já o atributo name serve para identificar os dados quando o formulário é enviado para o servidor. Se um campo não tiver o atrivuto name, os dados que foram escritos nele não serão enviados.]

2. Rótulos e acessibilidade:
   Porque é que colocar apenas um `placeholder` não substitui uma etiqueta `<label>`? Que comportamento útil acontece no navegador quando um utilizador clica em cima do texto de uma `<label>` corretamente configurada?
   Resposta: [O placeholder é um texto de exemplo que aparece dentro do campo e desaparece quando começamos a escrever. Por isso, não substitui o <label>, que serve para identificar o campo e explicar o que devemos escrever. Quando clicamos no texto de etiqueta <label> corretamente ligada ao campo, o cursor vai automaticamente para a caixa de texto, facilitando o preenchimento do formulário.]

3. Rádios vs Checkboxes:
   Em que circunstâncias devemos utilizar botões de rádio (`type="radio"`) e em que casos devemos optar por caixas de verificação (`type="checkbox"`)? Qual é a regra técnica para que vários botões de rádio pertençam ao mesmo grupo de escolha exclusiva?
   Resposta: [Os botões de rádio (radio) são usados quando queremos escolher apenas uma opção entre várias, como escolher entre morador local ou turista. As caixas de verificação (checkbox) são usadas quando podemos marcar uma ou várias opções, como os dias em que temos disponibilidade. Para que os botões de rádios funcionem como umgrupo e permitam apenas uma escolha, todos devem ter o mesmo atributo name.]


