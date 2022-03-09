# Cálculo 1

# Pré-requisitos

Começamos a matéria precisando de um conhecimento sólido de funções.![[Funções]]

# Limites

## Limites laterais

Caso os limites laterais sejam diferentes, isso significa que eles não existem.

## **Propriedades e teoremas de limites**

- Soma dos limites = limite das somas. Isto se aplica para as outras operações.

---

- Se o expoente for par, o limite será positivo.

  $\lim_{x\to-\infty}x⁵=-\infty$

  $\lim_{x\to-\infty}x⁴=+\infty$

---

- Teorema do monômio dominante

  $\lim_{x\to\infty}\frac{3x⁴}{x³+5x}=3x$

  - Quando o limite tender ao infinito e estivermos trabalhando com monômios, podemos considerar apenas o termo de maior grau. (Basicamente cortamos todos os X)

---

- Caso seja uma fração tendendo à $-\infty$, trataremos de módulo de X

  $\lim_{x\to-\infty}\frac{\sqrt{x²+2}}{3x+6}=\frac{|x|}{3x}=-\frac{1}{3}$

---

- Continuidade é quando uma [função](Funções.md) pode ser desenhada “sem tirar o lápis do papel”.

---

- Teorema do confronto:
  - quando houver um limite tendendo à 0 de um produto com uma função limitada (seno, cosseno, etc...) a resposta é 0
  - Funções trigonométricas são limitadas pois só vão de 0 até 1.
  $\lim_{x\to0}x²-sen(\frac{1}{x²})=0$

---

- Mudança de variável:

  - Quando trabalhamos com limites que possuem valores difíceis de serem trabalhados, podemos fazer uma mudança de variáveis.

  - Exemplo:

  $\lim_{x\to1}\frac{\sqrt{x²+3}-2}{x²-1}$

  - Podemos nos livrar da raiz quadrada igualando ela à U.

  1. $U = \sqrt{x²+3}$ , portanto, $X²=U²-3$
  2. Fazemos a substituição: $\lim_{u\to2}\frac{u-2}{u²-3-1}$ e o resultado será $\frac14$

---

- Bisu para calcular um limite na seguinte situação:

  $\lim_{x+\infty} \frac{\sqrt{x²+4}}{x+4}$

  - Podemos por o numerador em evidência em relação ao X

  $\lim_{x+\infty} \frac{\sqrt{x².(1+\frac{4}{x²})}}{x+4}$

  - e depois podemos separar o numerador em duas raízes para cada termo.

## Assíntotas

---

Assíntotas são formadas quando os limites tendem para o infinito.
![[Pasted image 20220220121449.png]]

**Calcular assíntota horizontal:**

$\lim_{x\to+-\infty} f(x) =L$

Calcule os limites laterais, tendendo à mais ou menos infinito

**Calcular assíntota vertical:**

$\lim_{x\to\infty} f(x) =+\infty$

Calcule os valores de X, tendendo à 0 pela direita e esquerda.

# Limites fundamentais

É sempre importante tentar fazer manipulações algébricas nos limites para tentar chegar até estes limites fundamentais:

![[Limite fundamental de Euler]]

![[Limite fundamental trigonométrico]]

![[Limite fundamental exponencial]]

![[Derivada]]
