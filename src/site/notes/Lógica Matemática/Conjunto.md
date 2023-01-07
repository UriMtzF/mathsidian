---
{"dg-publish":true,"permalink":"/Lógica Matemática/Conjunto/"}
---

Un conjunto es cualquier colección de elementos considerada en si misma como un objeto.
Los conjuntos se pueden representar de manera gráfica con [[Lógica Matemática/Diagrama de Venn\|Diagramas de Venn]]

## Cardinalidad
La cardinalidad de un conjunto indica su tamaño y se denota por $|A|$, $\text{card}(A)$ o $\#A$. Se pueden señalar dos cardinalidades especiales:

### Cardinalidad infinita
Se trata de un conjunto de objetos infinitos, p. ej. todos los números.

### Cardinalidad cero
También llamado conjunto vacío, se trata de un conjunto que carece de elementos. Representado por el símbolo $\emptyset$

## Determinación
Los conjuntos poseen una notación especial, esta notación se puede separar en:

### Determinación por extensión
Dado un conjunto finito de elementos, se especifican todos los elementos que forman al objeto, p. ej. 
$$\begin{array}{lr}A=\{a,e,i,o,u\} \\ B=\{2,4,6,8,10\} \end{array}$$

### Determinación por comprensión
Se especifica una propiedad que caracteriza a todos los elementos, p. ej. 
$$\begin{array}{lr}A=\{\text{Todas las vocales}\}\\ B=\{x:x=2n|n\in \mathbb{N}\} \end{array}$$
## Conjunto universal

^d89a8f

Sean $n$ cantidad de conjuntos con al menos uno no vacío, todos los elementos de estos conjuntos pertenecen a un conjunto fijo llamado conjunto universal.
## Subconjunto
Dado un conjunto $A$, un subconjuto $B$ es aquel contiene algunos elementos del conjunto $A$.
### Número de sunconjuntos de un conjunto
Si se toman todos los elementos de un conjunto $A$ y se ordenan en todas las [[Combinatoria/Permutación\|combinaciones]] posibles se pueden formar $m$ subconjuntos incluyendo al conjunto mismo y el vacío. $m$ está definido por: 
$$m=2^n$$

>[!warning] Combinación cómo lenguaje común
>La definición de combinación usada aquí refiere en realidad a las [[Combinatoria/Permutación\|permutaciones]], sin embargo en el lenguaje común es normal usarlos de forma indistinta. Los conjuntos no toman en cuenta el orden de acomodamiento de sus elementos por lo que se debe usar la definición de permutaciones en lugar de combinaciones matemáticas.


## Propiedades de conjuntos

^ce7e26

En la teoría de conjuntos axiomática estándar, por el axioma de extensionalidad, dos conjuntos son iguales si tienen los mismos elementos: por lo tanto solo puede haber un conjunto sin ningún elemento. Por consiguiente se habla de "*el conjunto vacío*" en lugar de "*un conjunto vacío*"
### Para todo conjunto $A$
- El conjunto vacío es un subconjunto de A
$$\forall A:\emptyset\subseteq A$$
- La unión de $A$ con el conjunto vacío es $A$ 
$$\forall A:A\cup\emptyset =A$$
- La intersección de $A$ con el conjunto vacío es el conjunto vacío
$$\forall A:A\cap\emptyset =\emptyset$$
- El [[Lógica Matemática/Producto Cartesiano\|producto cartesiano]] de $A$ y el conjunto vacío es el conjunto vacío
$$\forall A:A\times \emptyset =\emptyset$$
### Para el conjunto vacío
- Su único subconjunto es el propio conjunto vacío 
$$\forall A:A\subseteq\emptyset\Rightarrow A=\emptyset$$
- El conjunto potencia del conjunto vacío es el conjunto que contiene únicamente el conjunto vacío
$$2^{\emptyset}=\{\emptyset\}$$
- Su número de elementos (cardinalidad) es cero
$$n(\emptyset)=0$$
## Conjuntos disjuntos

^383003

Dos conjuntos $A$ y $B$ no vacíos son disjuntos o ajenos si no tienen elementos en común, de manera formal: 
$$A\cap B=\emptyset$$