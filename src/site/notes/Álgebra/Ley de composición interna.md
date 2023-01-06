---
{"dg-publish":true,"permalink":"/Álgebra/Ley de composición interna/"}
---

Dado un conjunto $A$ y una operación interna $\odot$, que se representa con el par $(A,\odot)$, se dice que $\odot$ es una ley de composición interna en $A$ cuando es una aplicación de la forma:
$$\begin{array}{rccl}\odot :&A\times A&\longrightarrow &A\\&(a,b)&\longmapsto &c=a\odot b\end{array}$$
Una ley de composición interna asigna a cada par ordenado $(a,b)$, ambas pertenecientes al conjunto $A$, un tercer elemento $c$ también contenido en $A$. El elemento $c$ es único para cada par ordenado, formalmente expresado como:
$$\forall(a,b)\in A\times A, \ \exists!c\in A: \ c=a\odot b$$
Algunos ejemplos de ley de composición interna son:
- La suma de dos números naturales
- La multiplicación de dos números racionales
## Propiedades de una ley de composición interna
Dado un conjunto **A** no vacío y definida una aplicación de **A** por **A** sobre **A**, donde a cada par ordenado (**a**,**b**) se le asigna un valor **c** de **A**, que representamos: $(A,\odot )$
$$\begin{array}{rccl}\odot :&A\times A&\longrightarrow &A\\&(a,b)&\longmapsto &c=a\odot b\end{array}$$
### Conmutatividad
Se dice que esta ley de composición interna $(A,\odot)$, tiene la propiedad conmutativa si:$$\forall a,b\in A: a\odot b=b\odot a$$
### Asociatividad
Se dice que esta ley de composición interna $(A,\odot)$, tiene la propiedad asociativa si: $$\forall a,b,c\in A: (a\odot b)\odot c=a\odot(b\odot c)$$
### Elemento neutro
Para todo conjunto $A$, no vacío, dotado de una ley de composición interna $(A,\odot)$, se dice que este conjunto, con esta ley de composición interna, tiene elemento neutro: $e$, si se cumple que: $$\forall a\in A, \ \exists e \in A: a\odot e=e\odot a=a$$
### Elemento simétrico
Para un conjunto $A$, no vacío, dotado por una ley de composición interna $(A,\odot)$, se dice tiene elemento simétrico si tiene elemento simétrico por la izquierda y por la derecha, si se expresa del siguiente modo: $$\forall a\in A, \exists\overline{a}\in A: a\odot\overline{a}=\overline{a}\odot a=e$$
## Propiedades de dos leyes de composición interna
Dado un conjunto $A$ no vacío y definidas dos aplicación de $A$ por $A$ sobre $A$, donde a cada par ordenado $(a,b)$ se le asigna un valor $c$ de $A$, con la primera ley de composición que representamos: $(A,\odot )$ y un valor $d$ de $A$, con la segunda ley de composición, que representamos $(A,\circledcirc )$
$$\begin{array}{rccl}\odot :&A\times A&\longrightarrow &A\\&(a,b)&\longmapsto &c=a\odot b\end{array}\quad \quad \quad \begin{array}{rccl}\circledcirc :&A\times A&\longrightarrow &A\\&(a,b)&\longmapsto &d=a\circledcirc b\end{array}$$
Pueden tener las siguientes propiedades:
### Distributividad
Dado un conjunto $A$, no vacío, en el que se han definido dos leyes de composición internas, que denotamos: $(A,\odot,\circledcirc)$, tiene la propiedad distributiva sobre la segunda si es distributiva por la izquierda y por la derecha.
#### Distributividad por la izquierda
Para un conjunto $A$, no vacío, con dos leyes de composición internas: $(A,\odot ,\circledcirc)$, la primera es distributiva por la izquierda sobre la segunda si: $$\forall a,b,c\in A: a\odot(b\circledcirc c)=(a\odot b)\circledcirc(a\odot c)$$
#### Distributividad por la derecha
Para un conjunto $A$, no vacío, con dos leyes de composición internas: $(A,\odot ,\circledcirc)$, la primera es distributiva por la derecha sobre la segunda si: $$\forall a,b,c\in A:a\circledcirc(b\odot c)=(a\odot c)\circledcirc (b\odot c)$$
