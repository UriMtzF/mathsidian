---
{"dg-publish":true,"permalink":"/Análisis Matemático/Dominio/"}
---

El dominio, conjunto de definición o conjunto de partida de una [[Definiciones/Función\|Función]] $f:X\rightarrow Y$ es el conjunto de existencia de ella misma, es decir, los valores para los cuáles la función está definida. Es el conjunto de todos los valores que puede transformar, se denota $\text{Dom}_{f}$, $\text{Dom}(f)$ o $D_{f}$. 
De manera formal: 
$$D_{f}=\{x\in X:\exists y\in Y:f(x)=y\}$$
## Propiedades
Dadas dos funciones reales:
$$\begin{array}{lr}f:X_{1}\rightarrow \mathbb{R}\\g:X_{2}\rightarrow \mathbb{R}\end{array}$$
Se dan las siguiente propiedades:
- $D_{(f+g)}=X_{1}\cap X_{2}$
- $D_{(f-g)}=X_{1}\cap X_{2}$
- $D_{(f\cdot g)}=X_{1}\cap X_{2}$
- $D_{(f/g)}=\{x\in(X_{1}\cap X_{2})|g(x)\neq 0\}$

## Cálculo del dominio
Para el cálculo del dominio de una función real, es necesario conocer las restricciones en el cuerpo real, es decir, ciertas condiciones conocidas para las cuales una función no está definida, p. ej:

**Logaritmo de una función**
Los logaritmos no están definidos para números negativos o cero, por lo tanto toda función contenida en un logaritmo debe ser estricamente mayor a cero.

**Fracciones**
Debido a que la división entre cero no está definida, cualquier función contenida en una fracción debe tener un denominador distinto a cero

**Raíces**
En el campo de los reales, no están definidas las raíces negativas de orden par, por lo tanto, cualquier función contenida en una raíz de orden par debe ser estrictamente mayor o igual a cero.