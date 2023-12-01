Descartando Cartas
Dado um baralho com N cartas, numerado de 1 até N,
com essas cartas ordenadas, a seguinte operação é
executada enquanto tiverem mais de uma carta no
baralho: Descarte a carta inicial do baralho, agora
mova a carta inicial do baralho para o final.
O seu objetivo é, usando a estrutura de dados Fila,
detectar a ordem que as cartas foram descartadas e qual
carta sobrou no baralho, ao final de todas as operações
serem executadas.
A entrada é composta de um número N (N <= 50) que
indica o tamanho do baralho.
A saída deve ser todas as cartas descartadas do seu
baralho, e por último a carta restante.
Para um baralho de 5 cartas, a disposição inicial dele
é:1, 2, 3, 4, 5. Aplicando a operação, descarta-se o 1 e
move-se o 2 para o final. A fila se torna 3, 4, 5, 2.
Fazendo a operação em sequência novamente, a fila
seria transformada em [5, 2, 4] => [4, 2] =>[2] com o 2
sendo o elemento restante.

5

solução
1
3
5
4
Restante: 2

7 


SOLUÇÃO
1
3
5
7
4
2
Restante: 6



19

SOLUÇAO
1
3
5
7
9
11
13
15
17
19
4
8
12
16
2
10
18
14
Restante: 6 

FILA 
