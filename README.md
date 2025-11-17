# Documentación de Ejercicios - Giovana Ruby Díaz Anduze

## Información general
- **Tecnológico de Software**
- **Materia:** Fundamentos de Álgebra
- **Tema:** Determinantes
- **Fecha:** 18 de noviembre de 2025
- **Alumno:** Giovana Ruby Díaz Anduze
- **Grupo:** 1A
- **Actividad \#18 - Documentación de Ejercicios con Git Branches**

---
# TÍTULO: DOCUMENTACIÓN DE EJERCICIOS CON GIT BRANCHES
---
Objetivo de la actividad: documentar las soluciones y el proceso de los ejercicios realizados en clase utilizando el formato Markdown y siguiendo la estructura de un archivo README.md. Además, practicarán el uso de branches (ramas) en Git, una habilidad esencial para el trabajo colaborativo en desarrollo de software.

---
## EJERCICIOS REALIZADOS
---
Ejercicio 1: Determinante de la matriz A
---
Encontrar A: Calcular la determinante de la siguiente matriz:
---
$$ A =
\begin{pmatrix}
4 & 5 \\
-3 & 2 \\
\end{pmatrix}
$$

#### Respuesta
La determinante de la matriz es: **[23]**

#### Procedimiento
1. **Identificar el tipo de matriz:**
  La matriz es de tamaño **2x2**
     
3. **Asignar los valores**
- a = 4
- b = 5
- c = -3
- d = 2 

  
4. **Realizar productos de ambos términos**
- det(A) = ad - bc
- det(A) = [4 x 2] - [-3 x 5]

5. **Realizar suma**
- det(A) = (8) + (15)   
- det(A) = 23

    - *Nota:* Restar un número negativo es equivalente a sumar su valor absoluto, por eso \(8 - (-15) = 23\).

---
Ejercicio 2: Determinante de la matriz B
---
Encontrar B: Calcular la determinante de la siguiente matriz:
---
$$ B =
\begin{pmatrix}
3 & 5 & 7 \\
0 & -3 & 1 \\
0 & 0 & -9 \\
\end{pmatrix}
$$

#### Respuesta
La determinante de la matriz es: **[81]**

#### Procedimiento
1. **Identificar el tipo de matriz:**
  La matriz es **triángular superior**, porque todos los valores **debajo de la diagonal principal son 0**.

2. **Aplicar la regla de determinantes para matrices triángulares:**
  En matrices triangulares (superiores o inferiores), el determinante es simplemente el **producto de los elementos de la diagonal principal**.

  - det (B) = (3)(-3)(9)
  
3. **Multiplicar paso por paso:**
  - [3 x -3] = -9
  - [-9 x -9] = 81

    - *Nota:* Este método es mucho más rápido que usar Sarrus o cofactores, pero solo aplica cuando la matriz es triangular.

---
Ejercicio 3: Determinante de la matriz C
---
Encontrar C: Calcular la determinante de la siguiente matriz:
---
$$ C =
\begin{pmatrix}
8 & 7 & 6 \\
15 & 2 & 3 \\
2 & 4 & 10 \\
\end{pmatrix}
$$

#### Respuesta
 La determinante de la matriz es: **[-608]**

#### Procedimiento
1. **Identificar la matriz**
- La mtriz es de tamaño **3x3**, por lo que podemos usar la **Regla de Sarrus**.

2. **Repetir las dos primeras columnas de la matriz**

$$ C =
\begin{pmatrix}
8 & 7 & 6 \\
15 & 2 & 3 \\
2 & 4 & 10 \\
8 & 7 & 6 \\
15 & 2 & 3 \\
\end{pmatrix}
$$

3. **Multiplicar las diagonales que se van hacia abajo**
- **Primera diagonal:** [8 x 2 x 10] = 160
- **Segunda diagonal:** [15 x 4 x 6] = 360
- **Tercera diagonal:** [2 x 4 x 3] = 42

4. **Multiplicar las diagonales que van hacia arriba**
- **Primera diagonal:** [2 x 2 x 6] = -24
- **Segunda diagonal:** [8 x 4 x 3] = -96
- **Tercera diagonal:** [15 x 7 x 10] = -1050

5. **Realizar la resta de los resultados**
- 562 - 1170 = -608

    - *Nota:* En la Regla de Sarrus, **las diagonales que van hacia arriba** se **restan** porque representan los términos negativos de la expansión del determinante. Por eso su producto siempre se sustrae del total.

---
Ejercicio 4: Determinante de la matriz BC
---
Encontrar BC: Calcular la determinante de la siguiente matriz:
---
Tenemos las matricez B y C:

$$ B =
\begin{pmatrix}
3 & 5 & 7 \\
0 & -3 & 1 \\
0 & 0 & -9 \\
\end{pmatrix}
$$

$$ C =
\begin{pmatrix}
8 & 7 & 6 \\
15 & 2 & 3 \\
2 & 4 & 10 \\
\end{pmatrix}
$$

#### Respuesta
 La determinante de la matriz es: **[-49248]**

#### Procedimiento
1. **Multiplicar las matrices B x C**
- Fila 1:
    - Columna 1: 3(8) + 5(15) + 7(2) = 24 + 75 + 14 = 113
    - Columna 2: 3(7) + 5(2) + 7(4) = 21 + 10 + 28 = 59
    - Columna 3: 3(6) + 5(3) + 7(10) = 18 + 15 +70 = 103
- Fila 2:
    - Columna 1: 0(8) + (-3)(15) + 1(2) = -45 + 2 = -43
    - Columna 2: 0(7) + (-3)(2) + 1(4) = -6 + 4 = -2
    - Columna 3: 0(6) + (-3)(3) + (1)(10) = -9 + 10 = 1
- Fila 3:
    - Columna 1: 0(8) + 0(15) + (-9)(2) = -18
    - Columna 2: 0(7) + 0(2) + (-9)(4) = -36
    - Columna 3: 0(6) + 0(3) + (-9)(10) = -90

**Así queda la matriz**

$$ BC =
\begin{pmatrix}
113 & 59 & 103 \\
-43 & -2 & 1 \\
-18 & -36 & -90 \\
\end{pmatrix}
$$

2. **Repetir las dos primeras columnas de la matriz**

$$ BC =
\begin{pmatrix}
113 & 59 & 103 \\
-43 & -2 & 1 \\
-18 & -36 & -90 \\
113 & 59 & 103 \\
-43 & -2 & 1 \\
\end{pmatrix}
$$

3. **Multiplicar las diagonales que se van hacia abajo**
- **Primera diagonal:** [113 x -2 x -90] = 20340
- **Segunda diagonal:** [-43 x -36 x 103] = 159444
- **Tercera diagonal:** [-18 x 59 x 1] = -1062

4. **Multiplicar las diagonales que van hacia arriba**
- **Primera diagonal:** [-43 x 59 x -90] = 228330
- **Segunda diagonal:** [113 x -36 x 1] = -4068
- **Tercera diagonal:** [-18 x -2 x 103] = 3708

5. **Sumar ambas diagonales**
- [20340 + 159444 - 1062] = 178722
- [228330 - 4068 + 3708] = 227970

6. **Restar la suma de las diagonales**
- det(BC) = 178722 - 227970 = -49248

  - *Nota:* Las diagonales que suben se restan porque en la regla de Sarrus representan la parte “negativa” del determinante, y así se respeta el signo correcto.





