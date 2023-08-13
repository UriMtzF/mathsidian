---
{"dg-publish":true,"permalink":"/Análisis Matemático/Función polinómica/"}
---

Una [[Definiciones/Función\|Función]] polinómica, es una relación entre un valor de entrada y un valor de salida calculado a partir de un polinomio.

Las funciones se pueden nombrar en base al grado del polinomio que contienen, así mismo cada una posee formas características al momento de graficarlas:
| Grado | Nombre             | Expresión              | Representación                        |
| ----- | ------------------ | ---------------------- | ------------------------------------- |
| 0     | Función constante  | $y=a$                  | Rectas horizontales o paralelas a $x$ |
| 1     | Función lineal     | $y=ax+b$               | Rectas oblicuas                       |
| 2     | Función cuadrática | $y=ax^{2}+bx+c$        | Parábolas                             |
| 3     | Función cúbica     | $y=ax^{3}+bx^{2}+cx+d$ | Curvas cúbicas                                      |
{ #cd88af}


## Raíces de un polinomio
Dado el [[Álgebra/Teorema fundamental del álgebra\|Teorema fundamental del álgebra]], se pueden obtener $n$ cantidad de raíces de todo polinomio según el grado $n$ de este.

Existen diversos métodos para encontrar las raíces de un polinomio
### Raíces de funciones de grado par
{ #e84a9c}


Los polinomios que cuyo grado es par son tratadas de forma especial ya que estos polinomios pueden generar raíces de orden par, las cuáles si son negativas se resuelven por medio de [[Teoría de números/Número complejo\|números complejos]].
#### Raíces de funciones cuadráticas
Dada la sencillez de las funciones cuadráticas, existen ciertas reglas que pueden ayudar a determinar la *naturaleza* de las raíces a partir del discriminante del polinomio.

Dado un polinomio cuadrático de la forma $p(x)=ax^{2}+bx+c$, el discriminante, representado por la letra delta $\Delta$, en las ecuaciones cuadráticas se puede obtener con la siguiente fórmula: 
$$\Delta=b^{2}-4ac$$
- Si $\Delta>0$, entonces $p(x)$ tiene dos raíces reales distintas.
- Si $\Delta = 0$, entonces $p(x)$ tiene dos raíces coincidentes reales.
- Si $\Delta<0$, entonces $p(x)$ no tiene raíces reales.