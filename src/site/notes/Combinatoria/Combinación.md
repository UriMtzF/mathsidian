---
{"dg-publish":true,"permalink":"/Combinatoria/Combinación/","dgPassFrontmatter":true}
---

Los coeficientes binomiales, números combinatorios o combinaciones son números estudiados en combinatoria que corresponden al número de formas en que se puede extraer subconjuntos a partir de un conjunto dado.

Se suele denotar por $nCr$, $C(n,r)$, $Cr^{n}$, $C_{n}^{r}$ o $\binom{n}{r}$

## Combinaciones sin repetición
Las combinaciones de $n$ elementos tomados $r$ posibles muestras sin orden de $r$ elementos distintos que se puedan extraer de un conjunto de $n$ elementos ($r\leq n$) $$nCr=\frac{n!}{r!\cdot (n-r)!}$$
>[!example]- Ejemplo
>En una reunión de 8 personas debe nombrarse una comisión formada por dos de ellas. ¿Cuántas comisiones distintas podrían nombrarse?
>$$8C2=\frac{8!}{2!\cdot 6!}=28$$
## Combinaciones con repetición
Las combinaciones con repetición de $n$ elementos tomados $r$ posibles muestras no ordenadas de $r$ elementos no necesariamente distintos que se pueden extraer de un conjunto de $n$ elementos.
$$CR_n^r=nCRr=\binom{n+r-1}{r}$$
>[!example]- Ejemplo
>*Un banco ofrece un regalo a elegir entre 5 posibles regalos por cada cartilla. Un señor que tiene tres cartillas en dicho banco ¿de cuántas formas puede elegir el lote de tres obsequios si no le importa repetir regalos?*
>$$CR_{5}^{3}=\binom{5+3-1}{3}=\binom{7}{3}=35$$

>[!tip] Diferencia con permutación
>En términos sencillos una combinación no toma en cuenta el orden en el que se toman los elementos.

