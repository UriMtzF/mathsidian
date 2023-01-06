---
{"dg-publish":true,"permalink":"/Combinatoria/Permutación/"}
---

Una permutación es una disposición de sus miembros en una secuencia u orden lineal, o si el conjunto ya está ordenado, una variación del orden de este. Se puede representar con $nPr$, $P(n,r)$ o $Pr^{n}$
## Permutaciones sin repetición
Las permutaciones de $n$ elementos tomados $r$ a la vez $$nPr=\frac{n!}{(n-r)!}\text{ , si } n=r \ \text{, } nPr=n! $$
>[!example]- Ejemplo
>*Un banco ofrece un regalo a elegir entre 5 posibles regalos por cada cartilla. Un señor que tiene tres cartillas en dicho banco ¿de cuántas formas puede elegir el lote de tres obsequios si no le importa repetir regalos?* $$nPr=4!=24$$


## Permutaciones con repetición
Las permutaciones de $n$ elementos con elementos repetidos tomados todos a la vez $$PR_{n}^{x,y,z,...}=\frac{n!}{x!\cdot y!\cdot z!\cdot ...}$$
>[!example]- Ejemplo
>*¿Cuántos números distintos de 6 cifras se pueden escribir usando tres unos, dos cincos y un ocho?*$$PR_{6}^{3,2,1}=\frac{6!}{3!\cdot 2! \cdot 1!}=60$$
## Permutaciones circulares
Las permutaciones de $n$ objetos alrededor de un ciclo $$PC_{n}=(n-1)!$$
>[!example]- Ejemplo
>*¿De cuántas formas distintas pueden sentarse 10 personas en una mesa redonda?* $$PC_{10}=(10-1)!=362880$$

