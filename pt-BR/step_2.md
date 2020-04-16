## Dê um corpo ao seu bug

--- task ---

Abra o editor BlocksCAD em um navegador da web [blockscad3d.com/editor/](https://www.blockscad3d.com/editor/){: target = "_ blank"}

--- /task ---

Agora crie o corpo do seu bug.

--- task ---

Comece com uma esfera `` com um raio de `10` (a unidade aqui é milímetros):

![captura de tela](images/bug-body-sphere.png)

Clique no botão **Render** para ver o resultado.

Dica: você pode alterar a cor do modelo renderizado clicando no quadrado colorido.

--- /task --- --- task ---

Agora estique a esfera ao longo do seu eixo Y para criar um corpo alongado para o erro.

O bloco `escala`{: class = "blockscadtransforms"} permite esticar ou esmagar objetos ao longo dos eixos X, Y e Z. Defina o valor Y como `1,2` para esticar a esfera ao longo do eixo Y.

![screenshot](images/bug-body-y.png)

Clique em **Render** novamente e verifique se a esfera foi esticada em um elipsóide. Olhe para o seu modelo de diferentes ângulos para poder ver como ele mudou.

--- /task ---

Dica: sempre que você fizer uma alteração no código, clique em **Render** para ver os resultados.

--- task ---

Agora esmague o elipsóide um pouco ao longo do eixo z para criar um erro mais plano.

Definir um valor de eixo abaixo de `1` diminui o objeto ao longo desse eixo. Portanto, altere o valor Z no bloco `escala`{: class = "blockscadtransforms"} para `0,8`.

![screenshot](images/bug-body-z.png)

--- /task ---



