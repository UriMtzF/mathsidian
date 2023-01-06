---
{"dg-publish":true,"permalink":"/Álgebra/Sistema de ecuaciones lineales/"}
---

Un sistema algebraico de ecuaciones lineales, también conocido como sistema lineal de ecuaciones, ecuaciones simultáneas o simplemente sistema lineal, es un un conjunto de ecuaciones con más de una incógnita que conforman un problema matemático que consiste en encontrar los valores de las incógnitas que satisfacen dichas operaciones, en donde cada ecuación es de primer grado.

## Tipos de sistema lineales
Los sistemas se pueden clasificar según la cantidad de soluciones que puedan presentar, se pueden presentar los siguientes casos:
- **Sistema compatible** si tiene solución, además se pueden distinguir,
	- **Sistema compatible determinado** cuando sólo tiene una única solución.
	- **Sistema compatible indeterminado** cuando admite un conjunto infinito de soluciones.
- **Sistema incompatible** si no tiene solución.

>[!tip] Relación incógnitas-ecuaciones
>Los sistemas de ecuaciones comúnmente tienen la misma cantidad de ecuaciones que de incógnitas (sistemas de 2 ecuaciones x (por) 2 incógnitas (2x2)), sin embargo se pueden dar casos en los que haya más incógnitas que ecuaciones o viceversa lo cual genera, en ocasiones, sistemas imposibles de resolver. 
>Para conocer si se puede resolver un sistema de ecuaciones se puede recurrir a la razón "ecuaciones $\geq$ incógnitas", es decir, si un sistema tiene el mismo número o mayor de ecuaciones que de incógnitas es muy probable que se pueda resolver.


## Resolución de sistemas de ecuaciones lineales
### Método gráfico
>[!warning] Límites del método gráfico
>El método gráfico es sumamente útil para la comprensión de los sistemas de ecuaciones, sin embargo este sólo funciona (en papel) hasta sistemas de ecuaciones de dos incógnitas. Con ayuda de software moderno se puede lograr más fácilmente resolver sistemas de hasta tres incógnitas. 

>[!tip] Software graficador
>Si se cuenta con un software que sea capaz de hacer gráficas a partir de [[Definiciones/Función\|funciones]] es preferible usarlo ya que ahorrará pasos.

1. Se escoge una de las incógnitas de las ecuaciones y se despeja en cada una.
2. Se construye una tabla de valores en base a las ecuaciones anteriormente obtenidas.
3. Se representan en un eje coordenado los puntos de cada ecuación y se trazan las rectas.
4. Se determinan las soluciones:
	1. Si las rectas se intersectan, las coordenadas del punto de intersección son los valores de solución (comúnmente $x,y$).
	2. Si ambas rectas son coincidentes, es decir, una está sobre la otra, el sistema tiene un número infinito de soluciones.
	3. Si las rectas son paralelas, el sistema no tiene solución en los [[Teoría de números/Número real\|números reales]]

### Método de sustitución
El método de sustitución consiste en despejar de una de las ecuaciones, cualquier incógnita, normalmente la más sencilla de despejar, a continuación, sustituir su valor en la otra ecuación. En la nueva ecuación se despeja la incógnita restante y se sustituye su valor en alguna de las ecuaciones originales para conocer el valor de la incógnita inicialmente despejada.

Para el caso de sistemas de más de dos ecuaciones, el valor de la incógnita despejada debe ser sustituida en el resto de ecuaciones, dando lugar a un nuevo sistema de ecuaciones al cuál se le puede aplicar el mismo proceso hasta obtener una ecuación con una única incógnita.

### Método de igualación
Se puede entender al método de igualación cómo un paso que puede simplificar al método de sustitución. Una vez se tienen un par de ecuaciones despejadas respecto de una incógnita se pueden igualar y con cualquier otro proceso algebraico conocido se puede resolver para obtener la otra incógnita.

>[!tip] Más incógnitas y ecuaciones
>Si se realiza este método con sistema con más de 2 ecuaciones e incógnitas se puede llegar a ecuaciones más complicadas de resolver o simplemente sin solución, es preferible combinar este método con otros.

### Reducción
>[!warning] Únicamente para ecuaciones de 2x2
>Este método sólo funciona en sistemas que poseen dos ecuaciones y dos incógnitas, puede ayudar en otros tipos de sistemas y en casos sumamente específicos.

Si un sistema posee dos ecuaciones que contengan una incógnita de igual coeficiente pero distinto signo, se puede proceder con este método. Se ordenan las ecuaciones a forma de suma, es decir, ordenando en una columa aquellos términos que contengan la misma incógnita, en la siguiente la próxima incógnita y al final el término sin incógnita.

Una vez ordenados se suman, si se cumplió la condición anterior, debe quedar una tercera ecuación con una sola variable la cual se puede despejar, una vez obtenido su valor se sustituye en cualquiera de las ecuaciones originales obteniendo el valor de la incógnita restante.
### Método de eliminación de Gauss
#### Método de eliminación de Gauss-Jordan
### Regla de Cramer