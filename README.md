## Algebra
# Fundamentos de Programación - Práctica 1

## Información del Estudiante

- *Nombre:* Euruviel Marquez Martinez 
- *Grupo:* [C]
- *Cuatrimestre:* Primer Cuatrimestre
- *Carrera:* TSU en Desarrollo e Innovación de Software
- *Profesor:* Jorge Javier Pedrozo Romero

Identifica el tipo de cada matriz:

# 📘 Matrices

Este documento contiene ejemplos y ejercicios básicos sobre **tipos de matrices** y **operaciones matriciales**.

---

## 🔹 Tipos de Matrices

### Matriz Identidad
\[
A = 
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
\]

### Matriz Diagonal
\[
B = 
\begin{bmatrix}
3 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 5
\end{bmatrix}
\]

### Matriz Simétrica
\[
C = 
\begin{bmatrix}
2 & 1 & 4 \\
1 & 3 & 5 \\
4 & 5 & 6
\end{bmatrix}
\]

### Matriz Triangular Superior
\[
D = 
\begin{bmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6
\end{bmatrix}
\]

---

## 🧮 Ejercicios

### a) \( A + B \)
\[
A + B = 
\begin{bmatrix}
1 + (-1) \\
2 + 7
\end{bmatrix}
=
\begin{bmatrix}
-1 \\
7
\end{bmatrix}
\]

---

### b) \( 2A - B \)
\[
2A - B = 
\begin{bmatrix}
4 & -2 \\
6 & 4
\end{bmatrix}
-
\begin{bmatrix}
5 & 2 \\
-1 & 3
\end{bmatrix}
=
\begin{bmatrix}
-1 & -4 \\
7 & 1
\end{bmatrix}
\]
**Resultado final:**  
\[
\begin{bmatrix}
2 & 7 \\
0 & 5
\end{bmatrix}
\]

---

### c) \( A \times B \)
\[
A = 
\begin{bmatrix}
2 & 1 \\
1 & 3
\end{bmatrix},
\quad
B = 
\begin{bmatrix}
5 & 3 \\
4 & 1
\end{bmatrix}
\]

\[
A \times B =
\begin{bmatrix}
(2×5 + 1×4) & (2×3 + 1×1) \\
(1×5 + 3×4) & (1×3 + 3×1)
\end{bmatrix}
=
\begin{bmatrix}
14 & 7 \\
17 & 6
\end{bmatrix}
\]

**Resultado:**  
\[
\begin{bmatrix}
11 & 11 \\
11 & 18
\end{bmatrix}
\]

---

### d) \( 3B \times A \)
\[
3B \times A =
\begin{bmatrix}
5 & 2 \\
2 & 3
\end{bmatrix}
\times
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
=
\begin{bmatrix}
11 & 16 \\
13 & 18
\end{bmatrix}
\]

**Resultado:**  
\[
\begin{bmatrix}
15 & 3 \\
7 & 13
\end{bmatrix}
\]

---

## ✏️ Autor

**MARQUEZ MARTÍNEZ ERUVIEL — Grupo 2103-B**

---

## 📅 Contenido

- Conceptos básicos de matrices
- Tipos de matrices (identidad, diagonal, simétrica, triangular)
- Operaciones matriciales (suma, resta, multiplicación, escalar)
- Ejercicios resueltos paso a paso
