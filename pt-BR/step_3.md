## Achatar a base do corpo

Agora achate a base do corpo para tornar seu inseto mais realista. Um modelo com base plana também é mais fácil para imprimir em 3D!

Para fazer isso, você pode simplesmente remover um cuboide do seu modelo usando o bloco `difference`{:class="blockscadsetops"}.

--- task ---

Para começar, crie um cuboide para cobrir a metade inferior do inseto (a parte que fica abaixo de 0 no eixo Z).

O cuboide deve estar `centralizado` e ter 10mm de altura (ao longo do eixo Z).

Adicione um bloco `translate` para mover o cubo -5mm ao longo do eixo Z (para baixo).

Para facilitar a separação do cuboide e do corpo do inseto, adicione um bloco `color` para tornar o cuboide de uma cor diferente.

![captura de tela](images/bug-body-cuboid.png)

O cuboide é maior que o corpo do inseto. Isso significa que você pode adicionar ao inseto sem precisar aumentar o cuboide posteriormente.

--- /task ---

--- task ---

Use um bloco `difference`{:class="blockscadsetops"} para remover o cuboide do corpo.

![captura de tela](images/bug-difference.png)

Agora o corpo do seu inseto tem uma base plana!

Arraste seu modelo no visualizador para vê-lo de diferentes ângulos.

--- /task ---



  
