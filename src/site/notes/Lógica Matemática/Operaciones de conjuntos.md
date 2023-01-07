---
{"dg-publish":true,"permalink":"/Lógica Matemática/Operaciones de conjuntos/"}
---

Los [[Lógica Matemática/Conjunto\|conjuntos]] se pueden operar entre sí. 
Si se tiene un conjunto no vacío $A$ y otro $B$, se definen las siguientes operaciones:
## Unión
Son todos los elementos que pertecen al menos a uno de los conjuntos $A$ y $B$. 
$$A\cup B=\{x|x\in A \lor x\in B\}$$
## Intersección
Son todos los elementos comunes de $A$ y $B$. 
$$A\cap B=\{x|x\in A\land x\in B\}$$
## Diferencia
Son todos los elementos que resultan de eliminar todos los elementos de $A$ que esten en $B$. 
$$\begin{array}{lr}A-B=\{x|x\in A \land x\notin B\} \\ A\textbackslash B=\{x|x\in A \land x\notin B\}\end{array}$$
## Complemento
Son todos los elementos que pertenecen a un [[Lógica Matemática/Conjunto#^d89a8f\|conjunto universal]] que no están contenidos en $A$. 
$$A^c=\{x|x\in U\land x\notin A\}$$
## Diferencia simétrica
Son todos los elementos que pertecen a $A$ o a $B$ pero no a ambos a la vez.
$$\begin{array}{lr}A\Delta B=\{x|x\in A \textbackslash B\lor x\in B\textbackslash A\}\\ A \Delta B=\{(A-B)\cup(B-A)\} \end{array}$$
## [[Lógica Matemática/Producto Cartesiano\|Producto Cartesiano]]

