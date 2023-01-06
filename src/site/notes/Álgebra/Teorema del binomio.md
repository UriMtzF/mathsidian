---
{"dg-publish":true,"permalink":"/Álgebra/Teorema del binomio/"}
---

El teorema del binomio es una fórmula que proporciona el desarrollo de la $n$-ésima potencia de un binomio, siendo $n\in \mathbb{Z}^{+}$. De acuerdo con el teorema es posible expandir la potencia $(x+y)^{n}$ en una suma que implica términos de la forma $ax^{b}y^{c}$, donde los exponentes $b,c \in \mathbb{N}$, es decir son [[Teoría de números/Número natural\|números naturales]] con $b+c=n$ y el coeficiente $a$ de cada término un [[Teoría de números/Número entero\|Número entero]] positivo que depende de $n$ y $b$. 

De forma matemática: $$ \begin{aligned}(x+y)^{n}&=\sum _{k=0}^{n}{n \choose k}x^{n-k}y^{k}\\&={n \choose 0}x^{n}+{n \choose 1}x^{n-1}y+{n \choose 2}x^{n-2}y^{2}+\cdots +{n \choose n-1}xy^{n-1}+{n \choose n}y^{n}\end{aligned}$$ ^371339
## Término general

^25185e

Se puede obtener únicamente un término denominado $k$-ésimo término, para calcularlo se emplea la siguiente fórmula: $$\text{Término }k=T_k=\binom{n}{k-1}a^{n-(k-1)}b^{k-1}$$