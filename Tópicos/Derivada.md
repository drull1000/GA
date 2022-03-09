# Derivada

> A derivada é denotada por um sinal de '

## Taxa de variação instantânea

Pegamos 2 pontos e aproximamos o ponto final do inicial como se fosse um limite.

Ex: calcular a variação populacional em um certo instante.

> $f'(a)= \lim _b \rightarrow _a \frac{f(b)-f(a)}{b-a}$

ou, podemos fazer com

Taxa de variação instantânea:

> $\lim _h \rightarrow _0= \frac{f(a+h)-f(a)}{h}$

onde H é o tempo.

---

Calcular a derivada da função $f(x)=2x-1$, no ponto $x=3$

![[Pasted image 20220305115111.png]]

---

## Regras de derivação

1. **Regra da potência**

   A potência n “cai” quando derivamos uma função potência.  Por exemplo, a derivada de $f(x) = x²$ é $f'(x) = 2x$.

   ![[Pasted image 20220306190859.png]]

   Basicamente põe o expoente no início multiplicando e subtrai 1 do expoente

2. **Regra da multiplicação por constante**

   A derivada de uma constante vezes uma função é a constante vezes a derivada da função.

   ![[Pasted image 20220306190828.png]]

   ![[Pasted image 20220306191003.png]]

3. **Regra da soma/diferença**

   A derivada de uma soma de duas funções f(x) e g(x) é a soma das derivadas de f(x) e g(x).

   ![[Pasted image 20220306190708.png]]

   Por exemplo, seja $h(x) = 3x + 5x²$.
   A derivada de $h(x)$ é $h'(x) = 3 + 10x$.

4. **Regra da derivada da função exponencial natural**

   A derivada de uma exponencial é ela mesma

5. **Regra do produto**

   A regra do produto diz que a derivada de um produto de duas funções é a primeira função vezes a derivada da segunda função mais a segunda função vezes a derivada da primeira função.

   ![[Pasted image 20220306191842.png]]

6. **Regra do quociente**

   A Regra do Quociente diz que a derivada de um quociente é o denominador vezes a derivada do numerador menos o numerador vezes a derivada do denominador, todos divididos pelo quadrado do denominador.

   ![[Pasted image 20220306191753.png]]

7. **Regra da raiz**

   A regra da raiz diz que a derivada de uma raiz é igual ao X elevado pelo termo da raiz invertido.

   ![[Pasted image 20220308110306.png]]
   Com exemplos melhores:

   ![[Pasted image 20220308110429.png]]
   ![[Pasted image 20220308110740.png]]

8. **Regra trigonométrica**
   - Derivada de Sen(x) é Cos(x)
   - Derivada de Cos(x) é -Sen(x)
   - Derivada de Tg(x) é Sec²(x)
   - Derivada de Cotg(x) é -Cossec²(x)
   - Derivada de Sec(x) é Sec(x)Tg(x)
   - Derivada de Cossec(x) é -Cossec(x)Cotg(x)

---

> Se f é derivável no ponto p então f é contínua no ponto p.

## Verificar se a função é derivável no ponto x

1. Ver se f é contínua (existe) no ponto x
2. Ver se existem limites com x tendendo ao ponto (pela esquerda e direita) e se tem o mesmo valor de f(x)
