# Combinação com repetição

Exemplo: De quantas maneiras podemos comprar 4 refrigerantes em um bar que vende 2 tipos de refrigerantes?
![[Pasted image 20220228074625.png]]
Observe que podemos resolver o problema utilizando Equações inteiras não negativas![[Equações lineares com coeficientes unitários#Equações inteiras não-negativas]]
Exemplo 2: Qual o número de maneiras de se colocar 7 letras em fila, com 3 a's, 2 b's e 2 c's?

Vamos escolher 3 lugares para as letras a's

**aa_a___**

O total é dado por $C_{7}^{3}$. Para cada configuração de 'a' em $C_{7}^{3}$, vamos escolher dentre os espaços restantes, 2 lugares para 'b'.

**aa_a_bb**

O total é dado por $C_{7-3}^{2} = C_{4}^{2}$. Agora fazemos para 'c'.

**aacacbb**

O total é $C_{4-2}^2=C_{2}^{2}=1$

Agora podemos multiplicar todos os valores
$C_{7}^{3}.C_{4}^{2}.C_{2}^{2} = \frac{7!}{3!2!2!}$

**Ou seja:** Perceba que o resultado pode ser obtido pondo o número total de espaços (7) dividido pelo número de objetos (3,2,2) fatorial.
