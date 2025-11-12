# Tecnológico de Software
## Materia: Fundamentos de álgebra
## Alumno: Giovana Ruby Díaz Anduze
## Actividad \#16 - Matrices doc

---
### Identificación de matrices

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

MUESTRA

Calcula la suma de A y B

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$

$$ A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$

---
# EJERCICIOS DE MATRICES
---
---
Ejercicio 1: Clasificar matrices
---
$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

Tipo de matriz:
- Identidad porque todos los elementos de la diagonal son 1.

$$ B =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
$$

Tipo de matriz:
- Diagonal porque todos los elementos fuera de la diagonal son ceros.

$$ C =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

Tipo de matriz:
- Simétrica porque los elementos tanto arriba como abajo de la diagonal son iguales.

$$ D =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
$$

Tipo de matriz:
- Triángulas superior porque todos los elementos debajo de la diagonal son cero.

---
Ejercicio 2: operaciones básicas
---

$$ A =
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

- Calcula:

A) A + B 

$$ A + B =
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$

B) 2A - B

$$ 2A - B =
\begin{pmatrix}
1 & 0 \\
7 & 5 \\
\end{pmatrix}
$$

C) AB

$$ AB =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$

D) BA

$$ BA =
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$

E) A^T

$$ A^T =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$

---
Ejercicio 3: Multiplicación de cadena
---

$$ A =
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix}
$$

$$ C =
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

- Demuestra que: (AB)C = A(BC)
---
# (AB)C:
- AB:

$$ AB =
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$

- (AB)C:

$$ (AB)C =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

# A(BC):
- BC:

$$ (BC) =
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$

- A(BC):

$$ A(BC) =
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$

# RESPUESTA: SÍ DAN LO MISMO
