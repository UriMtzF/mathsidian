---
{"dg-publish":true,"permalink":"/Álgebra/Regla de Ruffini/"}
---

La regla de Ruffini o división sintética facilita el cálculo rápido de la división de cualquier polinomio entre un binomio de la forma $(x-r)$. También permite localizar las raíces de un polinomio y factorizarlo en binomios de la forma $(x-r)$ siendo $r$ un [[Teoría de números/Número entero\|Número entero]]

## Algoritmo
Dado un polinomio cualquiera de la forma $P(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\cdots +a_{1}x+a_{0}$, que será el dividendo, y un binomio de la forma $Q(x)=x-r$, que será el divisor, se procede de la siguiente forma para obtener un cociente $R(x)$ y un residuo o resto $s$:
1. Se trazan dos líneas a modo de ejes y se escriben únicamente los coeficientes de $P(x)$ ordenados, según el grado del término, de mayor a menor, respetando el signo y colocando ceros en aquellos términos que no estén presentes. Se escribe el divisor ($r$) del lado izquierdo, segundo renglón y se escribe el primer coeficiente de $P(x)$, en el reglón inferior: 
$$\begin{array}{c|ccccc}{}&a_{n}&a_{n-1}&\dots &a_{1}&a_{0}\\r&{}&{}&{}&{}&{}\\\hline {}&b_{n-1}=a_{n}&{}&{}&{}&{}\\\end{array}$$ 
>[!warning]- Valor de $r$ (O el binomio está en la forma $(x+r)$)
>Dado el binomio de la forma $(x-r)$ se reescribe $r$ en el algortimo directamente, sin embargo, si el binomio se encuentra en la forma $(x+r)$, debe transformarse a la forma $(x-r)$, esto se puede lograr factorizando el múltiplo negativo, es decir $(x+r)=(x-(-r))$, es en este caso entonces, donde se debería escribir el término $-r$ para respetar la forma que este algoritmo exige.

3. Se multiplica $a_{n}$ por $r$ y se escribe debajo de $a_{n-1}$: 
$$\begin{array}{c|ccccc}{}&a_{n}&a_{n-1}&\dots &a_{1}&a_{0}\\r&{}&b_{n-1}\,r&{}&{}&{}\\\hline {}&b_{n-1}=a_{n}&{}&{}&{}&{}\\\end{array}$$
4. Se suma el valor obtenido anteriormente con el que está en la misma columna y se escribe el resultado debajo de este: 
$$\begin{array}{c|ccccc}{}&a_{n}&a_{n-1}&\dots &a_{1}&a_{0}\\r&{}&b_{n-1}\,r&{}&{}&{}\\\hline {}&b_{n-1}=a_{n}&b_{n-2}=a_{n-1}+b_{n-1}\,r&{}&{}&{}\\\end{array}$$
5. El proceso se repite hasta llegar a la última columna: 
$$\begin{array}{c|ccccc}{}&a_{n}&a_{n-1}&\dots &a_{1}&a_{0}\\r&{}&b_{n-1}\,r&\dots &b_{1}\,r&b_{0}\,r\\\hline {}&b_{n-1}=a_{n}&b_{n-2}=a_{n-1}+b_{n-1}\,r&\dots &b_{0}=a_{1}+b_{1}\,r&|\underline{s=a_{0}+b_{0}r}\,\\{}&\mathrm {Coef.} &{}&{}&{}&\mathrm {Resto}\end{array}$$
El cociente resultante $R(x)$, es de un grado menor que $P(x)$ y sus coeficientes son los valores marcados con $b$, es decir: 
$$R(x)=b_{n-1}x^{n-1}+b_{n-2}x^{n-2}+\dots+b_{1}x+b_{0}$$
El polinomio original (el dividendo) se puede reescribir con la forma: 
$$P(x)=Q(x)R(x)+s$$

>[!example]- Ejemplo
>Dados $P(x)=2x^{3}+3x^{2}-4$ y $Q(x)=x+1$ la división de $P(x)\div Q(x)$ se hace de la siguiente forma:
>1. Se escribe el divisor en la forma $(x-r)$, es decir $Q(x)=x+1=x-(-1)$, se escriben únicamente los coeficientes del polinomio $P(x)$, el valor de $r$ (en este caso $-1$) y el del coeficiente con el grado más alto en el siguiente arreglo: 
> $$\begin{array}{c|cccc}{}&2&3&0&-4\\-1&{}&{}&{}&{}\\\hline {}&2&{}&{}&{}\\\end{array}$$
>2. Se multiplica el valor del divisor ($r$) por el coeficiente escrito en el último renglón ($2$) y se escribe el resultado en la próxima columna a la derecha en la misma fila que el divisor, es decir:
> $$\begin{array}{c|rrrr}{}&2&3&0&-4\\-1&{}&{-2}&{}&{}\\\hline {}&2&{}&{}&{}\\\end{array}$$
>3. Se suma la columna con el número generado: 
> $$\begin{array}{c|rrrr}{}&2&3&0&-4\\-1&{}&{-2}&{}&{}\\\hline {}&2&{1}&{}&{}\\\end{array}$$
>5. Se repite el procedimiento hasta llegar a la última columna: 
> $$\begin{array}{c|rrrr}{}&2&3&0&-4\\-1&{}&{-2}&{-1}&{1}\\\hline {}&2&{1}&{-1}&|\underline{-3}\\{}&\mathrm {Coef.} &{}&{}&\mathrm {Resto} \end{array}$$

Reescribiendo el polinomio $P(x)$ con los valores obtenidos: 
$$P(x)=(x+1)(2x^{2}+x-1)-3=2x^{3}+3x^{2}-4$$
