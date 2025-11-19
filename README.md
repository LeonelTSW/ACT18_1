
# Tecnológico de Software  
## Materia: Fundamentos de Álgebra  
## Alumno: **Leonel Zapata Angulo**  
## Actividad #18 – Documentación con Git Branches

---

## EJERCICIOS REALIZADOS

---

# Ejercicio 1: Determinante de la matriz A

Calcular la determinante de la matriz:

$$
A =
\begin{pmatrix}
4 & 5 \\
-3 & 2 \\
\end{pmatrix}
$$

### Respuesta:
$$
\det(A) = 23
$$

### Procedimiento

Es una matriz 2×2, aplicamos:

$$
\det(A) = ad - bc
$$

Asignación:

- a = 4  
- b = 5  
- c = -3  
- d = 2  

Sustituyendo:

$$
\det(A) = (4)(2) - [(-3)(5)]
$$

$$
\det(A) = 8 + 15 = 23
$$

---

# Ejercicio 2: Determinante de la matriz B

$$
B =
\begin{pmatrix}
3 & 5 & 7 \\
0 & -3 & 1 \\
0 & 0 & -9 \\
\end{pmatrix}
$$

### Respuesta:
$$
\det(B) = 81
$$

### Procedimiento

Es una matriz triangular superior. Su determinante es el producto de la diagonal principal:

$$
\det(B) = (3)(-3)(-9)
$$

Operando:

- 3×−3 = −9  
- −9×−9 = 81  

---

# Ejercicio 3: Determinante de la matriz C

$$
C =
\begin{pmatrix}
8 & 7 & 6 \\
15 & 2 & 3 \\
2 & 4 & 10 \\
\end{pmatrix}
$$

### Respuesta:
$$
\det(C) = -608
$$

### Procedimiento

Aplicamos la Regla de Sarrus.

### Diagonales que bajan:

- 8×2×10 = 160  
- 15×4×6 = 360  
- 2×4×3 = 42  

Suma:
$$
160 + 360 + 42 = 562
$$

### Diagonales que suben:

- 2×2×6 = -24  
- 8×4×3 = -96  
- 15×7×10 = -1050  

Suma:
$$
-24 - 96 - 1050 = -1170
$$

### Resultado:

$$
562 - 1170 = -608
$$

---

# Ejercicio 4: Determinante de la matriz BC

Matrices:

$$
B =
\begin{pmatrix}
3 & 5 & 7 \\
0 & -3 & 1 \\
0 & 0 & -9 \\
\end{pmatrix}
\quad
C =
\begin{pmatrix}
8 & 7 & 6 \\
15 & 2 & 3 \\
2 & 4 & 10 \\
\end{pmatrix}
$$

---

## 1. Multiplicación BC

$$
BC =
\begin{pmatrix}
113 & 59 & 103 \\
-43 & -2 & 1 \\
-18 & -36 & -90 \\
\end{pmatrix}
$$

---

## 2. Regla de Sarrus

### Diagonales que bajan:

- 113×−2×−90 = 20340  
- −43×−36×103 = 159444  
- −18×59×1 = −1062  

Suma:
$$
178722
$$

### Diagonales que suben:

- −43×59×−90 = 228330  
- 113×−36×1 = −4068  
- −18×−2×103 = 3708  

Suma:
$$
227970
$$

### Resultado final:

$$
\det(BC) = 178722 - 227970 = -49248
$$
