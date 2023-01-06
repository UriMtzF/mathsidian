---
{"dg-publish":true,"permalink":"/Álgebra/Estructura algebráica/"}
---

Una estructura algebráica, también conocida como sistema algebráico, es una n-tupla $(a_{1},a_{2},...,a_{n})$, donde $a_{1}$ es un [[Lógica Matemática/Conjunto\|Conjunto]] dado no vacío, y $(a_{2},...,a_{n})$ un conjunto de operaciones aplicables a dicho conjunto.
## Principales estructuras algebráicas

^06643c

Con una ley de composición interna:
- Magma
- Semigrupo
- Monoide
- Grupo
- Grupo abeliano o conmutativo
Se pueden observar cómo se distinguen estas estructuras en el cuadro a continuación:
| Estructura     | Asociativa | Conmutativa | Neutro | Inverso | [[Álgebra/Ley de composición interna\|Operación Interna]] |
| -------------- | ---------- | ----------- | ------ | ------- | ------------------------------------------------- |
| Magma          |            |             |        |         | ✅                                                |
| Semigrupo      | ✅         |             |        |         | ✅                                                |
| Monoide        | ✅         |             | ✅     |         | ✅                                                |
| Grupo          | ✅         |             | ✅     | ✅      | ✅                                                |
| Grupo abeliano | ✅         | ✅          | ✅     | ✅      | ✅                                                  |

Con dos leyes de composición interna
- Anillo
- Anillo conmutativo
- Cuerpo o campo

Dados la terna ordenada $(A,\odot , \circledcirc)$, se pueden definir las anteriores estructuras
- $$\text{Anillo}\begin{cases}(a,\odot) \to \text{Grupo abeliano} \\ 
(a,\circledcirc) \to \text{Semigrupo} \\ \circledcirc \text{ distribuye a } \odot \end{cases}$$
- $$\text{Anillo conmutativo}\begin{cases}(a,\odot) \to \text{Grupo abeliano} \\ 
(a,\circledcirc) \to \text{Semigrupo y cumple conmutativa} \\ \circledcirc \text{ distribuye a } \odot \end{cases}$$
- $$\text{Cuerpo}\begin{cases}(a,\odot) \to \text{Grupo abeliano} \\ 
(a,\circledcirc) \to \text{Grupo abeliano} \\ \circledcirc \text{ distribuye a } \odot \end{cases}$$