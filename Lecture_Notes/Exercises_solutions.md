# Ćwiczenia 2024/2025

## 1. Podstawowe operacje na macierzach

Dla poniższych macierzy:

$$
\mathbf{A}=
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\quad
\mathbf{C}=
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
\qquad
\mathbf{D}=
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6 
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
1 & 2\\
4 & 5\\
7 & 8
\end{pmatrix}
$$

### 1. Oblicz: 

- $\mathbf{A} + \mathbf{B}$:

$$

\mathbf{A} + \mathbf{B} =
\begin{pmatrix}
1 & 2 \\
3 & 4 
\end{pmatrix}
+
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
=
\begin{pmatrix}
1+5 & 2+6 \\
3+7 & 4+8
\end{pmatrix}
=
\begin{pmatrix}
6 & 8 \\
10 & 12
\end{pmatrix}

$$

- $\mathbf{B} - \mathbf{A}$:

$$
\mathbf{B} - \mathbf{A} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
-
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
=
\begin{pmatrix}
5-1 & 6-2 \\
7-3 & 8-4
\end{pmatrix}
=
\begin{pmatrix}
4 & 4 \\
4 & 4
\end{pmatrix}
$$

- $\mathbf{A} + \mathbf{C}$:

$$
\mathbf{A} + \mathbf{C} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
+
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
=
\begin{pmatrix}
1 + (-1) & 2 + 2 \\
3 + 3 & 4 + 0
\end{pmatrix}
=
\begin{pmatrix}
0 & 4 \\
6 & 4
\end{pmatrix}
$$

- $\mathbf{D} + \mathbf{E}$:

$$
\mathbf{D} + \mathbf{E} =
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
+
\begin{pmatrix}
1 & 2 \\
4 & 5 \\
7 & 8
\end{pmatrix}
$$

Nie można dodać tych macierzy, ponieważ mają różne rozmiary.

### 2. Oblicz:

- $\frac{1}{2}\mathbf{A}$:

$$
\frac{1}{2} \mathbf{A} =
\frac{1}{2}
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
=
\begin{pmatrix}
\frac{1}{2} & 1 \\
\frac{3}{2} & 2
\end{pmatrix}
$$

- $2\mathbf{B}$:

$$
2\mathbf{B} =
2 \cdot
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
=
\begin{pmatrix}
10 & 12 \\
14 & 16
\end{pmatrix}
$$

- $-3\mathbf{C}$:

$$
-3\mathbf{C} =
-3 \cdot
\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
=
\begin{pmatrix}
3 & -6 \\
-9 & 0
\end{pmatrix}
$$

- $4\mathbf{D}$:

$$
4\mathbf{D} =
4 \cdot
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
=
\begin{pmatrix}
-4 & 8 & 12 \\
16 & 0 & 24
\end{pmatrix}
$$

### 3. Oblicz iloczyny:

- $\mathbf{A} \cdot \mathbf{B}$:

$$
\mathbf{A} \cdot \mathbf{B} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\cdot
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
=
\begin{pmatrix}
1\cdot5 + 2\cdot7 & 1\cdot6 + 2\cdot8 \\
3\cdot5 + 4\cdot7 & 3\cdot6 + 4\cdot8
\end{pmatrix}
=
\begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

- $\mathbf{B} \cdot \mathbf{A}$:

$$
\mathbf{B} \cdot \mathbf{A} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
\cdot
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
=
\begin{pmatrix}
5\cdot1 + 6\cdot3 & 5\cdot2 + 6\cdot4 \\
7\cdot1 + 8\cdot3 & 7\cdot2 + 8\cdot4
\end{pmatrix}
=
\begin{pmatrix}
23 & 34 \\
31 & 46
\end{pmatrix}
$$

- $\mathbf{A} \cdot \mathbf{D}$:

$$
\mathbf{A} \cdot \mathbf{D} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\cdot
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
=
\begin{pmatrix}
1\cdot(-1) + 2\cdot4 & 1\cdot2 + 2\cdot0 & 1\cdot3 + 2\cdot6 \\
3\cdot(-1) + 4\cdot4 & 3\cdot2 + 4\cdot0 & 3\cdot3 + 4\cdot6
\end{pmatrix}
=
\begin{pmatrix}
7 & 2 & 15 \\
13 & 6 & 39
\end{pmatrix}
$$

- $\mathbf{D} \cdot \mathbf{E}$:

$$
\mathbf{D} \cdot \mathbf{E} =
\begin{pmatrix}
-1 & 2 & 3 \\
4 & 0 & 6
\end{pmatrix}
\cdot
\begin{pmatrix}
1 & 2 \\
4 & 5 \\
7 & 8
\end{pmatrix}
$$

Nie można wykonać tego mnożenia, ponieważ macierze mają różne rozmiary.

## 2. Wyznaczniki macierzy 2x2 i 3x3

### 2x2 Macierze:

- Wyznacznik macierzy $\mathbf{A}$:

$$
\det(\mathbf{A}) = 
\det\begin{pmatrix}
2 & 3 \\
1 & 4
\end{pmatrix}
= 2\cdot4 - 3\cdot1 = 8 - 3 = 5
$$

- Wyznacznik macierzy $\mathbf{B}$:

$$
\det(\mathbf{B}) = 
\det\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
= 5\cdot8 - 6\cdot7 = 40 - 42 = -2
$$

- Wyznacznik macierzy $\mathbf{C}$:

$$
\det(\mathbf{C}) = 
\det\begin{pmatrix}
-1 & 2 \\
3 & 0
\end{pmatrix}
= (-1)\cdot0 - 2\cdot3 = 0 - 6 = -6
$$

### 3x3 Macierze:

- Wyznacznik macierzy $\mathbf{D}$:

$$
\det(\mathbf{D}) = 
\det\begin{pmatrix}
1 & 0 & 2 \\
-1 & 3 & 1 \\
2 & 4 & -2
\end{pmatrix}
= 1\cdot\det\begin{pmatrix} 3 & 1 \\ 4 & -2 \end{pmatrix} - 0 + 2\cdot\det\begin{pmatrix} -1 & 3 \\ 2 & 4 \end{pmatrix}
$$

Obliczając wyznaczniki 2x2:

$$
\det\begin{pmatrix} 3 & 1 \\ 4 & -2 \end{pmatrix} = 3\cdot(-2) - 1\cdot4 = -6 - 4 = -10
$$

$$
\det\begin{pmatrix} -1 & 3 \\ 2 & 4 \end{pmatrix} = -1\cdot4 - 3\cdot2 = -4 - 6 = -10
$$

Zatem:

$$
\det(\mathbf{D}) = 1\cdot(-10) - 0 + 2\cdot(-10) = -10 + (-20) = -30
$$

- Wyznacznik macierzy $\mathbf{E}$:

$$
\det(\mathbf{E}) = 
\det\begin{pmatrix}
3 & 1 & -1 \\
0 & 2 & 4 \\
5 & 3 & 2
\end{pmatrix}
$$

Obliczenia dla tej macierzy są bardziej złożone i wymagałyby rozszerzonej metody rozwinięcia Laplace'a.

- Wyznacznik macierzy $\mathbf{F}$:

$$
\det(\mathbf{F}) = 
\det\begin{pmatrix}
2 & -3 & 1 \\
1 & 4 & -2 \\
1 & 5 & 3
\end{pmatrix}
$$

Podobnie jak w przypadku poprzedniej macierzy, wyznaczanie wyznacznika będzie wymagało podobnej metody.

## 3. Wyznaczniki za pomocą rozwinięcia Laplace'a

**To zadanie jest wciąż w toku i wymaga dalszego rozwiązywania.**

## 4. Macierz odwrotna

### 4.1 Oblicz macierz odwrotną

- Dla macierzy $ \mathbf{A} $:

$$
\mathbf{A}^{-1} =
\frac{1}{\det(\mathbf{A})}
\begin{pmatrix}
d & -b \\
-c & a
\end{pmatrix}
$$

Gdzie:

$$
\det(\mathbf{A}) = ad - bc
$$

Podstawiając do wzoru macierz $\mathbf{A}$:

$$
\mathbf{A} =
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
$$

## 5. Inne operacje macierzy

### 5.1 Transponowanie macierzy

$$
\mathbf{A}^T =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
^T
=
\begin{pmatrix}
1 & 3 \\
2 & 4
\end{pmatrix}
$$

### 5.2 Mnożenie przez skalar

$$
k\mathbf{A} =
3 \cdot
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
=
\begin{pmatrix}
3 & 6 \\
9 & 12
\end{pmatrix}
$$

### 5.3 Właściwości macierzy

- Macierz jednostkowa:

$$
\mathbf{I}_2 =
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$

- Macierz diagonalna:

$$
\mathbf{D} =
\begin{pmatrix}
1 & 0 \\
0 & 2
\end{pmatrix}
$$

## 6. Układy równań liniowych

### 6.1 Rozwiązywanie układów równań

$$
\mathbf{A} \mathbf{x} = \mathbf{b}
$$

Gdzie:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix},
\mathbf{b} =
\begin{pmatrix}
5 \\
6
\end{pmatrix}
$$

Rozwiązanie można uzyskać za pomocą macierzy odwrotnej:

$$
\mathbf{x} = \mathbf{A}^{-1} \mathbf{b}
$$

## 7. Determinanty i macierze odwrotne

### 7.1 Obliczanie macierzy odwrotnej i wyznaczników

- Dla układu 3x3 można użyć metody Gaussa, rozwinięcia Laplace'a, lub wzoru na macierz odwrotną, zależnie od rozmiaru układu.
## 8. Rozwiązywanie układów równań liniowych za pomocą macierzy odwrotnej

### 8.1 Przykład rozwiązywania układu równań

Mamy układ równań:

$$
\mathbf{A} \mathbf{x} = \mathbf{b}
$$

Gdzie:

$$
\mathbf{A} =
\begin{pmatrix}
2 & 1 \\
3 & 4
\end{pmatrix}
\quad \text{oraz} \quad
\mathbf{b} =
\begin{pmatrix}
5 \\
6
\end{pmatrix}
$$

Aby znaleźć rozwiązanie $\mathbf{x}$, musimy obliczyć macierz odwrotną $\mathbf{A}^{-1}$:

$$
\mathbf{x} = \mathbf{A}^{-1} \mathbf{b}
$$

Zatem najpierw obliczamy wyznacznik macierzy $\mathbf{A}$:

$$
\det(\mathbf{A}) = 2\cdot4 - 1\cdot3 = 8 - 3 = 5
$$

Teraz obliczamy macierz odwrotną:

$$
\mathbf{A}^{-1} = \frac{1}{\det(\mathbf{A})}
\begin{pmatrix}
d & -b \\
-c & a
\end{pmatrix}
=
\frac{1}{5}
\begin{pmatrix}
4 & -1 \\
-3 & 2
\end{pmatrix}
$$

Teraz mnożymy $\mathbf{A}^{-1}$ przez wektor $\mathbf{b}$:

$$
\mathbf{x} = \frac{1}{5}
\begin{pmatrix}
4 & -1 \\
-3 & 2
\end{pmatrix}
\begin{pmatrix}
5 \\
6
\end{pmatrix}
=
\frac{1}{5}
\begin{pmatrix}
4\cdot5 + (-1)\cdot6 \\
(-3)\cdot5 + 2\cdot6
\end{pmatrix}
=
\frac{1}{5}
\begin{pmatrix}
20 - 6 \\
-15 + 12
\end{pmatrix}
=
\frac{1}{5}
\begin{pmatrix}
14 \\
-3
\end{pmatrix}
$$

Zatem:

$$
\mathbf{x} =
\begin{pmatrix}
\frac{14}{5} \\
\frac{-3}{5}
\end{pmatrix}
$$

## 9. Mnożenie macierzy przez skalar

### 9.1 Przykład mnożenia przez skalar

Dla macierzy:

$$
\mathbf{A} =
\begin{pmatrix}
3 & -1 \\
2 & 5
\end{pmatrix}
$$

Obliczmy $2\mathbf{A}$:

$$
2\mathbf{A} =
2 \cdot
\begin{pmatrix}
3 & -1 \\
2 & 5
\end{pmatrix}
=
\begin{pmatrix}
6 & -2 \\
4 & 10
\end{pmatrix}
$$

## 10. Macierz jednostkowa

### 10.1 Macierz jednostkowa

Macierz jednostkowa $ \mathbf{I}_n $ jest macierzą kwadratową, w której wszystkie elementy na głównej przekątnej są równe 1, a pozostałe elementy są równe 0. 

Przykład dla macierzy 2x2:

$$
\mathbf{I}_2 =
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$

Dla macierzy 3x3:

$$
\mathbf{I}_3 =
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{pmatrix}
$$

### 10.2 Właściwości macierzy jednostkowej

- Mnożenie jakiejkolwiek macierzy przez macierz jednostkową nie zmienia jej wartości:

$$
\mathbf{A} \cdot \mathbf{I}_n = \mathbf{A}
$$

- Macierz jednostkowa jest macierzą odwrotną do siebie samej:

$$
\mathbf{I}_n \cdot \mathbf{I}_n = \mathbf{I}_n
$$

## 11. Macierze diagonalne

### 11.1 Macierz diagonalna

Macierz diagonalna to macierz kwadratowa, w której wszystkie elementy poza główną przekątną są równe 0. Przykład macierzy diagonalnej 3x3:

$$
\mathbf{D} =
\begin{pmatrix}
5 & 0 & 0 \\
0 & 3 & 0 \\
0 & 0 & 2
\end{pmatrix}
$$

### 11.2 Właściwości macierzy diagonalnej

- Mnożenie macierzy diagonalnych polega na mnożeniu odpowiadających sobie elementów na przekątnej.
- Wyznacznik macierzy diagonalnej jest iloczynem elementów na głównej przekątnej.

Przykład:

$$
\det(\mathbf{D}) = 5 \cdot 3 \cdot 2 = 30
$$

## 12. Transponowanie macierzy

### 12.1 Przykład transponowania macierzy

Macierz $ \mathbf{A} $:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{pmatrix}
$$

Jej transponowana macierz $ \mathbf{A}^T $:

$$
\mathbf{A}^T =
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6
\end{pmatrix}
$$

### 12.2 Właściwości transpozycji

- $ (\mathbf{A}^T)^T = \mathbf{A} $
- $ (\mathbf{A} + \mathbf{B})^T = \mathbf{A}^T + \mathbf{B}^T $
- $ (\mathbf{A} \cdot \mathbf{B})^T = \mathbf{B}^T \cdot \mathbf{A}^T $

## 13. Inne operacje macierzy

### 13.1 Mnożenie macierzy

Macierze mogą być mnożone tylko wtedy, gdy liczba kolumn jednej macierzy odpowiada liczbie wierszy drugiej macierzy.

Przykład:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
\quad \text{oraz} \quad
\mathbf{B} =
\begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
$$

Iloczyn $\mathbf{A} \cdot \mathbf{B}$:

$$
\mathbf{A} \cdot \mathbf{B} =
\begin{pmatrix}
1\cdot5 + 2\cdot7 & 1\cdot6 + 2\cdot8 \\
3\cdot5 + 4\cdot7 & 3\cdot6 + 4\cdot8
\end{pmatrix}
=
\begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

### 13.2 Macierz odwrotna

Macierz odwrotna $\mathbf{A}^{-1}$ to taka macierz, która po pomnożeniu przez $\mathbf{A}$ daje macierz jednostkową:

$$
\mathbf{A} \cdot \mathbf{A}^{-1} = \mathbf{I}
$$

Dla macierzy 2x2:

$$
\mathbf{A}^{-1} = \frac{1}{\det(\mathbf{A})}
\begin{pmatrix}
d & -b \\
-c & a
\end{pmatrix}
$$

## 14. Układy równań liniowych

### 14.1 Rozwiązywanie układu równań przy pomocy macierzy

Rozwiązywanie układu równań można przeprowadzić, wykorzystując macierz współczynników i wektor wyników. Układ równań:

$$
\mathbf{A} \mathbf{x} = \mathbf{b}
$$

gdzie $\mathbf{A}$ to macierz współczynników, $\mathbf{x}$ to wektor zmiennych, a $\mathbf{b}$ to wektor wyników. Rozwiązanie:

$$
\mathbf{x} = \mathbf{A}^{-1} \mathbf{b}
$$

## 15. Ranga macierzy

### 15.1 Ranga macierzy

Ranga macierzy to maksymalna liczba liniowo niezależnych wierszy lub kolumn macierzy. Może być obliczana przy pomocy rozkładu macierzy na formę schodkową.

## 16. Wyznaczanie wyznacznika przy pomocy metody Laplace’a

### 16.1 Obliczanie wyznacznika

Dla macierzy 3x3:

$$
\det(\mathbf{A}) =
a(ei - fh) - b(di - fg) + c(dh - eg)
$$

## 17. Wyznaczanie odwrotności macierzy 3x3

### 17.1 Przykład

Dla macierzy 3x3:

$$
\mathbf{A} =
\begin{pmatrix}
a & b & c \\
d & e & f \\
g & h & i
\end{pmatrix}
$$

Macierz odwrotna $\mathbf{A}^{-1}$ oblicza się przy pomocy wyznacznika i macierzy dopełnień.

$$
\mathbf{A}^{-1} = \frac{1}{\det(\mathbf{A})} \cdot \text{Adj}(\mathbf{A})
$$

Gdzie $\text{Adj}(\mathbf{A})$ to macierz dopełnień transponowana.
