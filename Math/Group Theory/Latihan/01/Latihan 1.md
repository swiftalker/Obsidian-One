1. Pada himpunan semua bilangan $\mathbb{R}$ didefinisikann aturan berikut $a*b=a+b+1$, untuk setiap $a, b \text{ di } \mathbb{R}$ selidiki apakah merupakan operasi biner di $\mathbb{R}$!
   Jawab:
   Akan diselidiki apakah * tertutup. Ambil sebarang bilangan real a dan b. Berdasarkan definisi, a * b = a + b + 1 adalah operasi bilangan-bilangan real yang hasilnya juga bilangan real, jadi *  tertutup. Selanjutkan akan dibuktikan ketunggalan hasilnya. Ambil a, b, c, dan d bilangan-bilangan real sebarang dengan syarat a = c dan b = d. Jelas bahwa a + b + 1 = c + d + 1, jadi a * b = c * . Dengan kata lain * merupakan operasi biner.
   
2. Perhatikan himpunan vektor-vektor n komponen dengan komponen bilangan-bilangan real:
   $$
\mathbb{R}^n =
\left\{
\begin{bmatrix}
x_{1} \\
x_{2} \\
\vdots \\
x_{n} \\
\end{bmatrix}
: x_{i}, \in \mathbb{R}, i = 1,2, \dots, n
\right\}
   $$
   dan aturan penjumlahan dua vektor sebagai berikut:
   $$
   \begin{bmatrix}
x_{1} \\
x_{2} \\
\vdots \\
x_{n} \\
\end{bmatrix}
+
\begin{bmatrix}
y_{1} \\
y_{2} \\
\vdots \\
y_{n} \\
\end{bmatrix}
= 
\begin{bmatrix}
x_{1} + y_{1}\\
x_{2} + y_{2}\\
\vdots \\
x_{n} + y_{n}\\
\end{bmatrix}
\qquad (1.4)
   $$
   Tunjukan bahwa $(\mathbb{R}^n, +)$ merupakan grup.
   Jawab: 
   Pembuktian bahwa + yang didefinisikan merupakan operasi biner mirip dengan pembuktian pada Contoh 1.5. Akan dibuktikan terpenuhinya syarat-syarat sebuah grup pada $\mathbb{R}^n$ .
   a) Operasi + memenuhi sifat asosiatif:
    $$
    \left(
    \begin{bmatrix}
x_{1} \\
x_{2} \\
\vdots \\
x_{n} \\
\end{bmatrix}
+
\begin{bmatrix}
y_{1} \\
y_{2} \\
\vdots \\
y_{n} \\
\end{bmatrix}
\right)
+
\begin{bmatrix}
z_{1} \\
z_{2} \\
\vdots \\
z_{n} \\
\end{bmatrix}
=
\begin{bmatrix}
x_{1} \\
x_{2} \\
\vdots \\
x_{n} \\
\end{bmatrix}
+
\left( 
\begin{bmatrix}
y_{1} \\
y_{2} \\
\vdots \\
y_{n} \\
\end{bmatrix}
+
\begin{bmatrix}
z_{1} \\
z_{2} \\
\vdots \\
z_{n} \\
\end{bmatrix}
\right)
    $$
    b) Elemen netral di $\mathbb{R}$ adalah $\begin{bmatrix} 0 \\ 0 \\ \vdots \\ 0 \\ \end{bmatrix}$
    c) Invers dari masing-masing vektor $\begin{bmatrix} x_{1} \\ x_{2} \\ \vdots \\ x_{n} \\ \end{bmatrix}$ di $\mathbb{R}^n$ adalah $- \begin{bmatrix} x_{1} \\ x_{2} \\ \vdots \\ x_{n} \\ \end{bmatrix}$ di $\mathbb{R}^n$
