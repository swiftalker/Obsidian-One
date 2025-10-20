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
3. Diberikan himpunan $G = \{ (a,b) | a,b \in \mathbb{R}, b \neq 0 \}$ dengan operasi biner $(a,b) * (c,d) = (a+bc, bd)$ untuk semua (a,b), (c,d) di G. Buktikan G merupakan grup tidak komutatif terhadap operasi yang dimaksud.
   Jawab:
   Jelas bahwa operasi * yang didefinisikan pada soal merupakan operasi biner, karena untuk setiap (a,b), (c,d) di G dengan $b\neq0$ dan $d\neq 0$ berakibat $bd\neq 0$. Selanjutnya dibuktikan aksioma-aksioma yang lain sebagai berikut:
	   a) Sifat asosiatif:
			$$
			((a,b) * (c,d)) * (e,f) = (a+bc,bd) * (e,f) = ((a+bc) + bde, bdf) \\
			= (a+b(c+de), bdf) = (a,b) * (c+de, df) \\ 
			= (a,b) * ((c,d) * (e,f))
			$$
		b) Misalkan (a,b) adalah elemen nteral di G, untuk setiap (c,d) di G berlaku (a,b) * (c,d) = (c,d) yang berakibat (a+bc, bd) = (c,d). Dari persamaan tersebut disimpulkan bd = d yang berakibat b = 1 dan a + bc + a + c = c yang berakibat a = 0. Jadi (0,1) adalah elemen netral di G
		c) Ambil sebarang (a,b) di G. Misalkan (c,d) adalah invers (a,b). Akibatnya (a,b) * (c,d) = (0,1) dan selanjutnya (a+bc,bd)=(0,1). Dari persamaan tersebut disimpulkan a + bc = 0 dan bd = 1. Jadi $c = \frac{-a}{b}$ dan $d = \frac{1}{b}$.
	Untuk menunjukan bahwa G tidak komutatif perhatikan bahwa (a,b) * (c,d) = (a + bc, bd),
	sementara itu (c,d) * (a,b) = (c+da,m bd). Jadi secara umum dapat disimpulkan bahwa
	(a,b) * (c,d) $\neq$ (c,d) * (a,b).
	 
4. 
5. 