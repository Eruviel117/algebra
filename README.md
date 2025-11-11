## Algebra
# Fundamentos de Programación - Práctica 1

## Información del Estudiante

- *Nombre:* Euruviel Marquez Martinez 
- *Grupo:* [C]
- *Cuatrimestre:* Primer Cuatrimestre
- *Carrera:* TSU en Desarrollo e Innovación de Software
- *Profesor:* Jorge Javier Pedrozo Romero

-----------
# EJERCICIO 1 
Identifica el tipo de cada matriz:

$$ **A** =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

$$ **B** =
\begin{pmatrix}
3 & 0 & 0 \\
0 & -2 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
$$

$$ **C** =
\begin{pmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ **D** =
\begin{pmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6 \\
\end{pmatrix}
$$

##Respuesta 

A = identidad 
B = Matriz Diagonal 
C = Matriz simetria 
D = Matriz triangular superior 
----------
# EJERCICIO 2

$$ **A** = 
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix},
\qquad
**B** = 
\begin{pmatrix}
5 & 2 \\
-1 & 3 \\
\end{pmatrix}
$$

a) A + B 
Se suma los elementos que ocuparn la misma posicion 

$$ **A +B** =
\begin{pmatrix}
7 & 1 \\
2 & 7 \\
\end{pmatrix}
$$


b) 2A - B 

Se multiplican los elementos de la matriz A por dos y se restan a los resta los elementos correspondiente de la matriz B

$$ **2A-B** =
\begin{pmatrix}
2 & 7 \\
0 & 5 \\
\end{pmatrix}
$$



c) A * B 

Cada elemento del resultado se obtiene multiplicando fila de A por columna de B 

$$ **AxB** =
\begin{pmatrix}
11 & 1 \\
11 & 18 \\
\end{pmatrix}
$$
  
d) B * A 

Cada elemento del resultado se obtiene multiplicando fila de B por columna de A

$$ **BxA** =
\begin{pmatrix}
16 & 3 \\
7 & 13 \\
\end{pmatrix}
$$


e) A^T

Se cambian la posicion de los columnas por los valores de las filas 

$$ **BxA** =
\begin{pmatrix}
2 & 3 \\
-1 & 4 \\
\end{pmatrix}
$$

-----------------
# EJERCICIO 3 Multiplicación en Cadena


** Las matrices:**

$$ **A** = 
\begin{pmatrix}
1 & 2 \\
3 & 4 \\
\end{pmatrix},
\qquad
**B** = 
\begin{pmatrix}
2 & 0 \\
1 & 3 \\
\end{pmatrix},
\qquad
**C** = 
\begin{pmatrix}
1 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

** Objetivo: verificar que (AB)C = A (BC)**

Realiamos las operaciones de multiplicacion de AB 



$$ **AB** =
\begin{pmatrix}
1(2) + 2(1) & 1(0) + 2(3) \\
3(2) + 4(1) & 3(0) + 3(4) \\
\end{pmatrix} =
\begin{pmatrix}
2 + 2 & 0 + 6 \\
6 + 4 & 0 + 12 \\
\end{pmatrix} = 
\begin{pmatrix}
4 & 6 \\
10 & 12 \\
\end{pmatrix}
$$


Con el resultado de AB se multiplica con C para completar la primera matriz 


$$ **(AB)C** =
\begin{pmatrix}
4(1) + 6(0) & 4(1) + 6(2) \\
10(1) + 12(0) & 10(1) + 12(2) \\
\end{pmatrix} =
\begin{pmatrix}
4 + 0 & 4 + 12 \\
10 + 0 & 10 + 24 \\
\end{pmatrix} = 
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$



Realizamos la opreacion para obtener el resultado de A(BC)


$$ **BC** =
\begin{pmatrix}
2(1) + 0(0) & 2(1) + 0(2) \\
1(1) + 3(0) & 1(1) + 3(2) \\
\end{pmatrix} =
\begin{pmatrix}
2 + 0 & 2 + 0 \\
1 + 0 & 1 + 6 \\
\end{pmatrix} = 
\begin{pmatrix}
2 & 2 \\
1 & 7 \\
\end{pmatrix}
$$


Multiplicamos A * BC  


$$ **A(BC)** =
\begin{pmatrix}
1(2) + 2(1) & 1(2) + 2(7) \\
3(2) + 4(1) & 3(2) + 4(7) \\
\end{pmatrix} =
\begin{pmatrix}
2 + 2 & 2 + 14 \\
6 + 4 & 6 + 28 \\
\end{pmatrix} = 
\begin{pmatrix}
4 & 16 \\
10 & 34 \\
\end{pmatrix}
$$



## Autor

**MARQUEZ MARTÍNEZ ERUVIEL — Grupo 1C**

---

## Contenido

- Conceptos básicos de matrices
- Tipos de matrices (identidad, diagonal, simétrica, triangular)
- Operaciones matriciales (suma, resta, multiplicación, escalar)
- Ejercicios resueltos paso a paso
