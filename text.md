# A primeira coisa que vamos fazer é criar um canvas. 

**O canvas é uma area de desenho.**

Esse canvas tem que ser identificado por um ide para que possamos nos
referenciar a ele depois.

Na nossa tag """ <body> """ colocamos o metodo onload="iniciar()". Isso fara que ao
carregar a pagina, rode o metodo do js iniciar.

Dentro do iniciar colocamos:

- Criamos um canvas colocando dentro da variavel canvas o canvas idCanvas

- Passamos para esse canvas um contexto '2d'

- Criamos uma variavel chamada imagem que tem a nossa nave (pelo id)

- Pegamos o metodo drawImage(imagem, 50,50) isso fara com que o desenho da
nave fique na posicao x 50 e y 50.

- Usamos a mesma variavel e metodo para criar o inimigo1l e posicionamos na
posicao 150 150.

## Com isso aprendemos a posicionar imagens dentro do canvas.

Usamos tambem a funcao onmovemouse. Essa funcao vai mover nossa nave a partir
do movimento do mouse.

A funcao onmovemouse ficara dentro da tag mouse.

Vamos entao criar uma funcao moveNave(event) onde passamos um evendo do mouse
para ela. Dentre as varias propriedades que o evento tem dentro dele, temos o
offsetX e offsetY aue mostram as coordenadas de onde o mouse esta
