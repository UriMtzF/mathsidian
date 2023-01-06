---
{"dg-publish":true,"permalink":"/Teoría de números/Número complejo/","dgPassFrontmatter":true}
---

Los números complejos, denotados con $\mathbb{C}$, son una extensión de los [[Teoría de números/Número real\|números reales]]. Entre ambos conjuntos se cumple que $\mathbb{R}\subset\mathbb{C}$, es decir, $\mathbb{R}$ está contenido estrictamente en $\mathbb{C}$. Los números complejos se caracterizan por ser el conjunto que posee todas las raíces de los polinomios. Se representan por medio de la unión de un número real con un [[Teoría de números/Número imaginario\|Número imaginario]].

Se pueden representar estos números con distintas notaciones y de igual forma se pueden ejecutar operaciones con estos.

## Forma cartesiana

^108452

Esta es la forma más común de representar a los números complejos, un número comúnmente denominado $z$, está conformado por la suma de un número real y un imaginario, es decir: $$z=a+bi$$
Es posible encontrar números complejos sólo con parte imaginaria o real, de igual forma, se pueden tratar los números complejos en forma cartesiana cómo binomios, por lo que gran parte de las propiedades algebraicas aplican.
### Operaciones
Los números complejos sólo en esta forma se pueden sumar, restar y conjugar, también se pueden multiplicar y dividir. 
#### Suma
Para efectuar una adición de números complejos, se suman las partes reales y las imaginarias por separado respetando las reglas de álgebra y aritmética, se reescribe el número nuevo respetando la forma $z=a+bi$ 
#### Resta
Para el caso de la resta se realiza el mismo procedimiento que en la suma, teniendo cuidado de respetar las *leyes de los signos*.
#### Producto
Tratando el número como un binomio se puede efectuar producto de binomios simplificando los exponentes respetando las [[Teoría de números/Número imaginario#^b1f24c\|reglas de potencias de números imaginarios]], de igual forma se puede seguir la siguiente regla: $$(a+bi)\cdot (c+di)=(ac-bd)+(ad+bc)i$$
#### División
Tratando al número como un binomio se puede efectuar la división, sin embargo es más sencillo seguir la fórmula: $$\frac{a+bi}{c+di}=\frac{(ac+bd)+(bc-ad)i}{c^2+d^2}$$
#### Conjugado
Dado el número $z=a+bi$, el conjugado de $z$ denominado por $\overline{z}$ es otro número complejo definido por $\overline{z}=a-bi$
#### Módulo
En algunas representaciones gráficas es útil conocer el módulo o magnitud del número en cuestión, este se obtiene con: $$|z|=\sqrt{a^{2}+b^{2}}$$
## Forma polar

^c38c0d

La forma polar de un número complejo consta de dos componente llamados módulo y argumento: $$z=r\cos\theta+r\sin\theta=r\operatorname{cis}\theta$$
Es común usar la notación $\operatorname{cis}$ para acortar la suma de funciones trigonométricas.
>[!tip] Unidades del ángulo
>El ángulo puede estar escrito en grados sexagesimales o en radianes, por lo que se debe ser claro en las unidades que se estén usando

### Operaciones en la forma polar
Dados los números $z_{1}=r_{1}\operatorname{cis}\theta_{1}$ y $z_{2}=r_{2}\operatorname{cis}\theta_{2}$
#### Multiplicación
$$z_{1}\cdot z_{2}=(r_{1}\cdot r_{2})\operatorname{cis}(\theta_{1}+\theta_2)$$
#### División
$$\frac{z_{1}}{z_{2}}=\frac{r_{1}}{r_{2}}\operatorname{cis}(\theta_{1}-\theta_{2})$$
#### Potencia
$$z^{n}=r^{n}\operatorname{cis}(n\cdot \theta)$$
#### Raíz
Dependiendo del índice de la raíz, llamado $n$, se puede por lo tanto, obtener $n$ raíces de un número complejo usando la siguiente fórmula:
$$\sqrt[n]{z}=\sqrt[n]{r}\operatorname{cis}\frac{\theta+2\pi\cdot k}{n}$$
Dónde $k$ es un valor progresivo que comienza en cero y se detiene hasta que $k=n$, es decir, $k$, indica, la raíz menos uno, que se está obteniendo.
>[!warning] Unidades del ángulo
>En la fórmula se debe cambiar el valor de $2\pi$ por $360º$ en caso de que se estén usando grados sexagesimales.

### Conversión
Los números complejos no se pueden operar si se encuentran en otras formas o bien, puede ser conveniente operarlos en alguna otra forma. Los números polares se pueden convertir a forma cartesiana y viceversa.
#### Conversión de cartesiana a polar
Si se tiene un número de la forma $z=a+bi$ y se desea convertir a su forma polar, se debe obtener el módulo del número usando la fórmula anteriormente descrita.
Para obtener el argumento (el ángulo) se usa la tangente: $$\tan \theta=\frac{b}{a}$$
#### Conversión de polar a cartesiana
Dadas las funciones trigonométricas seno y coseno, se pueden determinar los valores de $a$ y $b$, así mismo la conversión es dependiente al cuadrante.
## Forma exponencial o de Euler

^fe6930

La forma exponencial describe una "equivalencia" a la forma polar con la particularidad que sólo usa ángulos en radianes, Euler estableció que; $e^{i\theta}=\cos\theta+\sin\theta i$, por consiguiente: $$z=re^{i\theta}$$
### Operaciones en la forma exponencial
Dados los números $z_{1}=e^{i\theta_{1}}$ y $z_{2}=e^{i\theta_{2}}$
#### Multiplicación
$$z_{1}\cdot z_{2}=(r_{1}\cdot r_{2})e^{i(\theta_{1}+\theta_{2})}$$
#### Divisón
$$\frac{z_{1}}{z_{2}}=\frac{r_{1}}{r_{2}}e^{i(\theta_{1}-\theta_{2})}$$
#### Potencia
$$z^{n}=r^{n}e^{i(n\cdot \theta)}$$
#### Raíz
Dependiendo del índice de la raíz, llamado $n$, se puede por lo tanto, obtener $n$ raíces de un número complejo usando la siguiente fórmula:
$$\sqrt[n]{z}=\sqrt[n]{r}e^{(\frac{\theta+2\pi k}{n})}$$
Dónde $k$ es un valor progresivo que comienza en cero y se detiene hasta que $k=n$, es decir, $k$, indica, la raíz menos uno, que se está obteniendo.
### Conversión
Dado que se tiene el valor del módulo del número se puede seguir el mismo procedimiento para convertir de la forma polar a la forma cartesiana, únicamente teniendo especial cuidado con las unidades del ángul (radianes).