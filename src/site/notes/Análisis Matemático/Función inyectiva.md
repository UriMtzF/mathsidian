---
{"dg-publish":true,"permalink":"/Análisis Matemático/Función inyectiva/","dgPassFrontmatter":true}
---

Una función $f:X\to Y$ es inyectiva, uno a uno, si a elementos del conjunto $X$ ([[Análisis Matemático/Dominio\|Dominio]]) le correspoden elementos distintos del conjunto $Y$ ([[Análisis Matemático/Codominio\|Codominio]]) de $f$, es decir, cada elemento del conjunto $Y$ tiene a lo sumo una preimagen en $X$, o lo que es lo mismo, en el conjunto $X$ no puede haber dos o más elementos que tengan la misma [[Análisis Matemático/Imagen\|Imagen]]

>[!example] Ejemplo
>Dada la función $f:\mathbb{R}\to \mathbb{R}|f(x)=x^{2}$
>No es inyectiva, pues el valor 4 se puede obtener con $f(-2)$ y $f(2)$

Para probar que una función no es inyectiva, basta con hallar dos valores distintos del dominio, cuyas imágenes del codominio son iguales.

## Cardinalidad e inyectividad
Dados dos conjuntos $A$ y $B$, entre los cuales existe una función inyectiva $f:A\to B$, tienen cardinales que cumplen: $$\text{card}(A)\leq \text{card}(B)$$
Si además existe otra función inyectiva $g:B\to A$, entonces puede decirse que existe una aplicación [[Análisis Matemático/Función biyectiva\|biyectiva]] entre $A$ y $B$.