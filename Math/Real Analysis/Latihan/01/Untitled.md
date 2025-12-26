Tunjukkan bahwa untuk setiap $n \in \mathbb{N}$ berlaku:
a. $\sum_{k=1}^{n} = 2^k = 2^{n+1} - 2$
Bukti.
(1) Untuk n = 1, maka $2^1 = 2^{1+1} - 2 \to 2^1 = 2^2 - 2 \to 2 = 4 -2 \to 2 = 2$. Sehingga pernyataan benar untuk n = 1;
(2) Diandaikan pernyataan benar untuk n, $\sum_{k=1}^{n} 2^k = 2^{n+1}-2$ maka harus dibuktikan untuk n + 1, sehingga:
$\sum_{n+1}^{k=1} 2^k = \sum_{k=1}^{n} 2^k + 2^{n+1} = 2^{n+1} - 2 + 2^{n+1} =2 \cdot 2^{n+1}-2$ secara sederhana asumsi ini benar untuk n + 1. Jadi terbukti bahwa $\sum_{k=1}^{n} 2^k = 2^{n+1} - 2$

b. $\sum_{k=1}^{n} k\cdot k! = (n+1)! - 1$
Bukti.
(1) Untuk n = 1, maka $1.1! = (1+1)! - 1 \implies 1 = 2! - 1 \implies 1 = 1$. Akibatnya pernyataan benar untuk n = 1;
(2) Andaikan pernyataan benar untuk n, sehingga $\sum_{k=1}^{n} k \cdot k! = (n+1)! - 1$ maka harus dibuktikan untuk n + 1, sehingga:
$\sum_{k=1}^{n+1} k \cdot k! = \sum_{k=1}^{n} k \cdot k! + (n+1)(n+1)!$
$=(n+1)!-1+(n+1)(n+1)!$
= (n+1)! + (n+1)(n+1)!-1
Trik faktorisasi
a + ba = a(1+b)
a = (n+1)!
b = (n+1)
Maka:
= ((n+1)!(1+(n+1)))-1
$=(n+1)!(n+2)-1$
Sehingga pernyataan ini juga benar untuk n + 1. Dan karenanya terbukti untuk $\sum_{k=1}^{n} k \cdot k! = (n+1)!-1$

c. $\sum_{k=1}^{n} (2k-1) = n^2$
Bukti.
(1) Untuk n = 1, maka $(2(1) - 1) = 1^2 \implies 1 = 1$. Sehingga pernyataan benar untuk n = 1;
(2) Andaikan pernyataan benar untuk n sehingga $\sum_{k=1}^{n} (2k-1)=n^2$. Akibatnya harus dibuktikan juga untuk n + 1, sehingga:
$\sum_{k=1}^{n+1} (2k-1) = \sum_{k=1}^{n} 2k-1 + (2(n+1) - 1)$
=$n^2 + (2(n+1)-1) = n^2 + 2n + 1$
=$(n+1)^2$
Sehingga pernyataan benar juga untuk n +1. Dan karenanya induksi matematika terbukti untuk $\sum_{k=1}^{n} (2k-1) = n^2$.

Tunjukkan bahwa untuk setiap $n \in \mathbb{N}$, $4^n - 1$ habis dibagi 3
Bukti.
(1) Diambil $n \in \mathbb{N}$ untuk n = 1 sedemikian sehingga $4^1 - 1 = 3 \implies 3=3$ yang pasti habis dibagi 3 sehingga demikian n = 1 benar untuk kasus pertama.
(2) Andaikan pernyataan benar untuk n sehingga $4^n-1 = 3m$ dengan $m \in \mathbb{Z}$ dan karenanya harus dibuktikan n + 1 sehingga:
$4^{n+1} - 1 \to 4^n.4 - 1 \to 4^n.4 -4 + 3 \to 4(4^n -1)  + 3 \to 4(3m) + 3 \to 12m + 3 \to 3(4m+1)$
Sehingga jelas dapat habis dibagi 3, oleh karenanya pernyataan diatas juga benar untuk n+1. 

Tunjukkan bahwa $n^2 < 2^n$ untuk setiap $n\in \mathbb{N}$ dengan $n\geq5$
Bukti.
(1) Diambil $n \in \mathbb{N}$ untuk kasus nilai terkecil n=5 sedemikian sehingga $5^2 < 2^5 = 25 < 32$ sehingga pernyataan benar untuk kasus n = 5.
(2) Andaikan pernyataan benar untuk n sehingga $n^2 < 2^n$ dan karenanya harus dibuktikan n + 1, maka:
- Ruas kiri: $(n+1)^2 = (n+1)(n+1) = n^2 + 2n + 1$
- Ruas kiri: $2^{n+1} = 2^n.2 = 2^n + 2^n$
Maka, $(n+1)^2 < 2^n+2n+1 \leq 2^n + 2^n \leq 2^{n+1}$
Sehingga pernyataan benar untuk n + 1;

Tunjukkan bahwa $2n-3 \leq 2^{n-2}$ untuk setiap $n \in \mathbb{N}$ dengan $n\geq5$
Bukti.
(1) Diambil $n \in \mathbb{N}$ dengan asumsi n terkecil n = 5 sedemikian sehingga $2(5) - 3 \leq 2^{5-2} \to 10-3 \leq 2^3\to 7 \leq 8$ jelas bahwa n = 5 memenuhi pernyataan ini.
(2) Asumsikan n adalah pernyataan benar sedemikian sehingga $2n-3 \leq 2^{n+2}$ dan harus dibuktikan n + 1, maka:
- Ruas kiri: $2(n+1) - 3 \to 2n + 2 - 3$ maka
$2n-3 \leq 2n + 2 -3$ sehingga $2n-2-3 \leq 2^{n+2}$ 
- Ruas kanan: $2^{n+2} = 2^{(n+1)+2} = 2^{n+3} = 2^n.2^3$
