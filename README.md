## Información general
- **Materia:** Fundamentos de Álgebra
- **Tema:** Ecuaciones de primer grado
- **Fecha:** Mérida, Yucatán a 3 de diciembre de 2025
- **Estudiante:** Giovana Ruby Díaz Anduze
- **Grupo:** 1° A
- **Actividad \#22 - última documentación**

---
# TÍTULO: DOCUMENTACIÓN DE ECUACIONES DE PRIMER GRADO
---
**Objetivo de la actividad:** 

---
## EJERCICIO 1
---

## Sistema

$$
\begin{cases}
x + y + z = 6\\
2x - y + z = 3\\
x + 2y - z = 2
\end{cases}
$$

## Matriz aumentada (Gauss)

$$
\begin{pmatrix}
1 & 1 & 1 & 6\\
2 & -1 & 1 & 3\\
1 & 2 & -1 & 2
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 1 & 1 & 6\\
0 & -3 & -1 & -9\\
0 & 1 & -2 & -4
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 1 & 1 & 6\\
0 & -3 & -1 & -9\\
0 & 0 & -7 & -21
\end{pmatrix}
$$

## Resultado
$$
x=1,\quad y=2,\quad z=3
$$

---

# Gauss–Jordan

$$
\begin{pmatrix}
1 & 1 & 1 & 6\\
0 & -3 & -1 & -9\\
0 & 0 & -7 & -21
\end{pmatrix}
\rightarrow
\begin{pmatrix}
1 & 0 & 0 & 1\\
0 & 1 & 0 & 2\\
0 & 0 & 1 & 3
\end{pmatrix}
$$

## Resultado

$$
x=1,\quad y=2,\quad z=3
$$

---

# Matriz Inversa (AX = B)

### Matrices

$$
A=
\begin{pmatrix}
1 & 1 & 1\\
2 & -1 & 1\\
1 & 2 & -1
\end{pmatrix},
\qquad
B=
\begin{pmatrix}
6\\3\\2
\end{pmatrix}
$$

### Resultado
$$
X = A^{-1}B =
\begin{pmatrix}
1\\2\\3
\end{pmatrix}
$$

---

# Cofactores / Adjunta

$$
\det(A)=7
$$

$$
A^{-1} = \frac{1}{7}\,\text{adj}(A)
$$

### Resultado
$$
\begin{pmatrix}
1\\2\\3
\end{pmatrix}
$$

---

# Regla de Cramer

$$
\det(A)=7,\qquad  
\det(D_x)=7,\qquad  
\det(D_y)=14,\qquad  
\det(D_z)=21
$$

### Resultado

$$
x=1,\quad y=2,\quad z=3
$$

---


# Ejercicio 2

## a)
$$
\begin{cases}
x+y=3\\
2x+2y=6
\end{cases}
$$

**Conclusión:**  
Tiene infinitas soluciones.

---

## b)
$$
\begin{cases}
x+y=3\\
2x+2y=7
\end{cases}
$$

**Conclusión:**  
No tiene solución.

---

## c)
$$
\begin{cases}
x+y=3\\
x-y=1
\end{cases}
$$

**Conclusión:**  
Solución única:

$$
(x,y)=(2,1)
$$

---
# Ejercicio 3

## Sistema

$$
\begin{cases}
x+y+z+w=10\\
2x+y-z+w=5\\
x-y+z-w=1\\
x+y-z+2w=8
\end{cases}
$$

## Matriz reducida (Gauss–Jordan)

$$
\begin{pmatrix}
1 & 0 & 0 & 0 & 0\\
0 & 1 & 0 & 0 & -\frac{5}{2}\\
0 & 0 & 1 & 0 & \frac{7}{2}\\
0 & 0 & 0 & 1 & 5
\end{pmatrix}
$$

## Resultado

$$
x=0,\quad
y=-\frac{5}{2},\quad
z=\frac{7}{2},\quad
w=5
$$

---
