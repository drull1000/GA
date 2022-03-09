# Equações lineares com coeficientes unitários

### Equações inteiras positivas.

Seja $x_1+x_2+x_3+x_4=11$

Vamos procurar o número de soluções **inteiras** e **positivas** desta equação.

Faremos $1+1+1+1+1+1+1+1+1+1+1=11$.
Como temos apenas 4 parcelas, vamos separar os números em 4

![[Pasted image 20220223124157.png]]

Temos 10 espaços entre os 1s e cada maneira de se escolher 3 lugares **para as barras** nos dá uma solução da equação.

Teorema: O número de soluções inteiras e positivas $X≥1$ da equação $x_1+x_2+...+x_n = m, m>0$ é dado por $C^{n-1}_{m-1}$.

Ex: O número de soluções inteiras e positivas $X≥1$ da equação $x_1+x_2+x_3+x_4+x_5 = 9$

Resposta: $C^{5-1}_{9-1} = C^{4}_{8} = \frac{8!}{4!4!} = 70$

### Equações inteiras não-negativas.

Seja $x_1+x_2=5$
Se exigirmos que a equação tenha apenas soluções inteiras, a quantidade de soluções será infinita.

Para tornar o número de soluções finito, devemos restringir o número de soluções:

Soluções positivas:

$C^{2-1}_{5-1} = C^{1}_{4} = \frac{4!}{1!3!} = 4$

Soluções não negativas (inclui o 0):

$C^{2-1}_{5+2-1} = C^{1}_{6} = \frac{6!}{1!5!} = 6$

Outro exemplo:

![[Pasted image 20220223132140.png]]

Teremos mais soluções.

Voltando ao exemplo $x_1+x_2+x_3+x_4=11$, como $X≥0$, faremos a seguinte mudança de variáveis: $y_1=x_1+1$ => $x_1=y_1-1$  e $y_1≥1$.

Substituindo, teremos:

$y_1-1+y_2-1+y_3-1+y_4-1=11$
$y_1+y_2+y_3+y_4=11+4 = 15$ , $y_i≥1$ e com esta, sabemos trabalhar.

Outro exemplo:

$0<x_1+x_2+x_3+x_4≤6$

Solução: Encontrar o número de soluções em inteiros positivos das equações:

$x_1+x_2+x_3+x_4=4...>m=4,n=4$ | $C^{n-1}_{m-1} = C^{4-1}_{4-1}=C^{3}_{3} = 1$

$x_1+x_2+x_3+x_4=5...>m=5,n=4$ | $C^{n-1}_{m-1} = C^{4-1}_{5-1}=C^{3}_{4} = 4$

$x_1+x_2+x_3+x_4=6...>m=6,n=4$ | $C^{n-1}_{m-1} = C^{4-1}_{6-1}=C^{3}_{5} = 10$

Total de soluções: 15
