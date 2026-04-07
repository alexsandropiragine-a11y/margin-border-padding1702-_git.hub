# margin-border-padding1702-_git.hub
Explicando conceitos relevantes
MARGIN (margem)
O que é:

É o espaço externo do elemento.

É responsável por afastar um elemento dos outros.

Pense assim:

Margin é o “ar” ao redor da caixa.

Exemplo:

p {
  margin: 20px;
}

Isso cria 20px de espaço fora do <p>.

Formas de usar:

margin: 10px;           /* todos os lados */
margin: 10px 20px;      /* topo/baixo | lados */
margin: 10px 20px 30px 40px; /* topo | direita | baixo | esquerda */

margin-top: 10px;
margin-right: 20px;
margin-bottom: 30px;
margin-left: 40px;

mportante:
Margin não tem cor
Pode colapsar (duas margins podem se juntar)


PADDING (preenchimento interno)
O que é:

É o espaço entre o conteúdo e a borda.

Serve para “engordar” o elemento por dentro.

Pense assim:

Padding é o “acolchoamento” dentro da caixa.

 Exemplo:
p {
  padding: 15px;
}

 O texto fica afastado da borda.

Formas de usar:
padding: 10px;
padding: 10px 20px;
padding: 10px 20px 30px 40px;

padding-top: 10px;
padding-left: 20px;
Importante:
Padding aumenta o tamanho do elemento
Ele mostra a cor de fundo (background)


BORDER (borda)
O que é:

É a linha que envolve o elemento.

Serve para destacar ou delimitar a caixa.

Exemplo:
p {
  border: 2px solid black;
}
Estrutura da borda:
border: espessura estilo cor;

Exemplo:

border: 3px dashed red;
Tipos de estilo:
solid (linha contínua)
dashed (tracejada)
dotted (pontilhada)
double
Extras:
border-radius: 10px; /* bordas arredondadas */
Diferença resumida,
Propriedade	Onde atua	Função,
Margin	Fora	Espaçar elementos,
Padding	Dentro	Espaçar conteúdo da borda,
Border	Meio	Criar borda visível,
Exemplo completo:
p {
  margin: 20px;          /* espaço fora */
  padding: 15px;         /* espaço interno */
  border: 2px solid blue;/* borda */
  background: lightgray;
}
