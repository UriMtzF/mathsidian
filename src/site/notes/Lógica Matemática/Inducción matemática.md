---
{"dg-publish":true,"permalink":"/Lógica Matemática/Inducción matemática/"}
---

La inducción es un razonamiento que permite demostrar proposiciones que dependen de una variable $n$ que toma una infinidad de [[Teoría de números/Número entero\|valores enteros]]. En términos simples la inducción matemática consiste en el siguiente razonamiento.

Dado un número entero $a$ que tiene la propiedad $P$, y el hecho de que si hasta cualquier número entero $n$ con la propiedad $P$ implique $n+1$ también la tiene, entonces los números enteros a partir de $a$ tienen la propiedad $P$

## Pasos para el uso de inducción matemática
1. Verificar que la proposición es válida o verdadera para el primer posible caso.
2. Asumir que la proposición es válida para $n=h$
3. Utilizando la proposición anterior probar que también es válida para el siguiente número $k+1$
>[!example]- Ejemplo
>$$P(n)=1+3+5+7+\cdots+(2n-1)=\sum\limits_{k=1}^{n}(2n-1)=n^2$$
>Se busca demostrar que 
>$$\sum\limits_{k=1}^{n}(2n-1)=(h+1)^{2}$$
> >[!warning] *Demostrar*
>Se usa la palabra demostrar como tal en el párrafo anterior debido a que es más fácil el uso de tal palabra, sin embargo el procedimiento a continuación busca demostrar el primer sumatorio mostrado empero se llegará al resultado del sumatorio anterior para verificar que es verdadero.
>
>*Para* $n=1$ (Paso 1)
>$$\begin{array}{rl}2(1)-1&=1^{2}\\1&=1\end{array}$$
>*Para* $n=h$ (Paso 2) 
>$$\sum\limits_{k=1}^{h}(2k-1)=k^2$$
>*Se agrega el siguiente número* $h+1$ 
>$$\begin{array}{rl}\sum\limits_{k=1}^{h+1}(2k-1)&=k^{2}+(1k-1)^{2}\\&=k^2+2k+2-1\\&=k^2+2k+1\\&=(k+1)^2\end{array}$$
>Por lo tanto se puede decir que la proposición anterior es verdadera

