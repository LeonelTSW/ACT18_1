Tecnológico de Software
Materia: Fundamentos de Álgebra
Alumno: Dylan Vázquez Soriano
Fecha: 18/11/2025
Actividad #18
DOCUMENTACIÓN DE EJERCICIOS CON GIT BRANCHES

Objetivo: Registrar el desarrollo y solución de los ejercicios trabajados en clase utilizando formato Markdown para simular un archivo README.md. Además, se busca practicar el manejo de ramas (branches) en Git, una habilidad fundamental para proyectos colaborativos.

EJERCICIOS REALIZADOS
Ejercicio 1: Determinante de la matriz A

Calcular el determinante de la matriz:

𝐴
=
(
4
	
5


−
3
	
2
)
A=(
4
−3
	​

5
2
	​

)
Respuesta:

La determinante es 23.

Procedimiento:

Reconocer el tipo de matriz: es una matriz 2×2.

Identificar sus elementos:

𝑎
=
4
a=4

𝑏
=
5
b=5

𝑐
=
−
3
c=−3

𝑑
=
2
d=2

Aplicar la fórmula del determinante para matrices 2x2:

det
⁡
(
𝐴
)
=
𝑎
𝑑
−
𝑏
𝑐
det(A)=ad−bc

Sustituir:

det
⁡
(
𝐴
)
=
4
(
2
)
−
[
−
3
(
5
)
]
det(A)=4(2)−[−3(5)]

Realizar las operaciones:

8
+
15
=
23
8+15=23

Nota: Restar un número negativo equivale a sumar su opuesto.

Ejercicio 2: Determinante de la matriz B

Dada la matriz:

𝐵
=
(
3
	
5
	
7


0
	
−
3
	
1


0
	
0
	
−
9
)
B=
	​

3
0
0
	​

5
−3
0
	​

7
1
−9
	​

	​

Respuesta:

La determinante es 81.

Procedimiento:

Observar la estructura: se trata de una matriz triangular superior, ya que todos los valores debajo de la diagonal principal son cero.

Aplicar la regla para matrices triangulares: su determinante es el producto de los elementos en la diagonal principal.

det
⁡
(
𝐵
)
=
(
3
)
(
−
3
)
(
−
9
)
det(B)=(3)(−3)(−9)

Multiplicar paso a paso:

3
×
−
3
=
−
9
3×−3=−9

−
9
×
−
9
=
81
−9×−9=81

Nota: Este método es más eficiente que Sarrus o cofactores, pero solo se aplica a matrices triangulares.

Ejercicio 3: Determinante de la matriz C

Calcular el determinante de:

𝐶
=
(
8
	
7
	
6


15
	
2
	
3


2
	
4
	
10
)
C=
	​

8
15
2
	​

7
2
4
	​

6
3
10
	​

	​

Respuesta:

El determinante es –608.

Procedimiento:

Identificar que se trata de una matriz 3×3, por lo que se usa la Regla de Sarrus.

Repetir las dos primeras columnas para aplicar el método.

Multiplicar las diagonales descendentes:

8
×
2
×
10
=
160
8×2×10=160

15
×
4
×
6
=
360
15×4×6=360

2
×
4
×
3
=
42
2×4×3=42

Multiplicar las diagonales ascendentes:

2
×
2
×
6
=
−
24
2×2×6=−24

8
×
4
×
3
=
−
96
8×4×3=−96

15
×
7
×
10
=
−
1050
15×7×10=−1050

Sumar los productos de cada grupo:

Descendentes:

160
+
360
+
42
=
562
160+360+42=562

Ascendentes:

−
24
−
96
−
1050
=
−
1170
−24−96−1050=−1170

Restar:

562
−
1170
=
−
608
562−1170=−608

Nota: Las diagonales que van hacia arriba representan la parte negativa de la expansión del determinante.

Ejercicio 4: Determinante de la matriz BC

Dadas las matrices:

𝐵
=
(
3
	
5
	
7


0
	
−
3
	
1


0
	
0
	
−
9
)
𝐶
=
(
8
	
7
	
6


15
	
2
	
3


2
	
4
	
10
)
B=
	​

3
0
0
	​

5
−3
0
	​

7
1
−9
	​

	​

C=
	​

8
15
2
	​

7
2
4
	​

6
3
10
	​

	​

Respuesta:

El determinante de 
𝐵
𝐶
BC es –49,248.

Procedimiento:
1. Multiplicar B × C

Fila 1:

Columna 1: 
3
(
8
)
+
5
(
15
)
+
7
(
2
)
=
113
3(8)+5(15)+7(2)=113

Columna 2: 
3
(
7
)
+
5
(
2
)
+
7
(
4
)
=
59
3(7)+5(2)+7(4)=59

Columna 3: 
3
(
6
)
+
5
(
3
)
+
7
(
10
)
=
103
3(6)+5(3)+7(10)=103

Fila 2:

Columna 1: 
−
45
+
2
=
−
43
−45+2=−43

Columna 2: 
−
6
+
4
=
−
2
−6+4=−2

Columna 3: 
−
9
+
10
=
1
−9+10=1

Fila 3:

Columna 1: 
−
18
−18

Columna 2: 
−
36
−36

Columna 3: 
−
90
−90

La matriz resultante es:

𝐵
𝐶
=
(
113
	
59
	
103


−
43
	
−
2
	
1


−
18
	
−
36
	
−
90
)
BC=
	​

113
−43
−18
	​

59
−2
−36
	​

103
1
−90
	​

	​

2. Aplicar la Regla de Sarrus

Diagonales descendentes:

113
×
(
−
2
)
×
(
−
90
)
=
20340
113×(−2)×(−90)=20340

−
43
×
(
−
36
)
×
103
=
159444
−43×(−36)×103=159444

−
18
×
59
×
1
=
−
1062
−18×59×1=−1062

Diagonales ascendentes:

−
43
×
59
×
(
−
90
)
=
228330
−43×59×(−90)=228330

113
×
(
−
36
)
×
1
=
−
4068
113×(−36)×1=−4068

−
18
×
(
−
2
)
×
103
=
3708
−18×(−2)×103=3708

Sumas:

Descendentes: 
20340
+
159444
−
1062
=
178722
20340+159444−1062=178722

Ascendentes: 
228330
−
4068
+
3708
=
227970
228330−4068+3708=227970

Resta final:

det
⁡
(
𝐵
𝐶
)
=
178722
−
227970
=
−
49248
det(BC)=178722−227970=−49248

Nota: Igual que antes, las diagonales ascendentes constituyen la parte que se sustrae según la regla de Sarrus.
