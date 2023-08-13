---
{"dg-publish":true,"permalink":"/Análisis Matemático/Progresión/"}
---

Una progresión es una sucesión de números entre los cuales hay una ley de formación constante, se distinguen dos tipos.
>[!warning] Una sucesión no es una progresión
>Mientras que una sucesión es una secuencia de números u otros objetos matemáticos relacionados entre sí, por otro lado las progresiones cuentan con una ley de formación constante. Una progresión es una sucesión pero no viceversa.
>Una respuesta más extensa puede encontrarse en [Math Stack Exchange](https://math.stackexchange.com/questions/3530240/sequence-vs-progression) en inglés.

## Progresión aritmética
{ #2b7cc6}


Una progresión aritmética es una sucesión de números tales que la diferencia de cualquier par de término sucesivos de la secuencia es constante, dicha cantidad es llamada diferencia de la progresión, diferencia o distancia.

La diferencia puede definirse por la fórmula 
$$a_{n+1}-a_{n}=d$$
Al conocer el primer término $a_{1}$ y la diferencia $d$, se puede obtener cualquier enésimo término $a_{n}$ por medio de la fórmula: 
$$a_{n}=a_{1}+(n-1)d$$
Si se conocen dos términos cualesquiera $a_{m}$ y $a_n$ tal que $m<n$ se puede obtener
$$a_{n}=a_{m}-(m-n)d$$
### Suma
La suma de los primero $n$ términos de una progresión aritmética se le conoce cómo serie aritmética dada por la fórmula:
$$\sum _{i=1}^{n}a_{i}=\frac{n}{2}(a_{1}+a_{n})=\frac{n}{2}(2a_{1}+(n-1)d)$$
## Progresión geométrica
{ #865900}


Una progresión geométrica es una sucesión de números tales que cada término se obtiene de multiplicar el anterior a este por una constanta denominada razón.

Al conocer el primer término $a_1$, la razón $r$ y se denota $a_n$ a cualquier otro que se desee obtener: 
$$a_{n}=a_{1}\cdot r^{n-1}$$
### Suma
La suma de los primeros n-términos se puede calcular con la fórmula:
$$S_n=a_{1\cdot}\frac{r^{n}-a}{r-1}=\frac{a_{1}-ra_{n}}{1-r}$$