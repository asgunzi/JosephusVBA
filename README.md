# JosephusVBA
Problema de Josephus através de uma simulação no Excel VBA


O problema de Josephus é um jogo com dois parâmetros: número de participantes e distância entre eliminações.

Diz a lenda que um certo Flavius Josephus, durante uma guerra, se encontrava entre um bando de 41 judeus rebeldes encurralados pelos romanos em uma caverna.

Os rebeldes formam um círculo e começam a partir de certo ponto a executar a terceira pessoa numa direção.
Sabe-se que Josephus sobreviveu. Em que posição ele estava para ser o último?

Por exemplo, para 7 participantes e eliminar a cada 3:
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus01.png)

Na primeira rodada, elimina o número 3.
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus02.png)

Pulando mais três, eliminar o número 6.
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus03.png)

Depois, é a vez do número 2.
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus04.png)

Depois, o número 7 – note que o 3 e o 6 já tinham sido eliminados.
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus05.png)

Na sequência, o 5 e o 1.
![](https://ferramentasexcelvba.files.wordpress.com/2019/08/josephus06.png)

No final das contas, o número 4 é o vencedor. Neste jogo, Josephus deveria ficar na posição 4 para sobreviver!

Desafio: criar uma função Josephus(n, p), que receba o número de participantes (n) e a distância a eliminar (p), e retorne qual a posição vencedora.


Vide planilha anexa.


Links:

Ideias técnicas com uma pitada de filosofia: https://ideiasesquecidas.com

Ferramentas Excel-VBA: https://ferramentasexcelvba.wordpress.com/

