Contoh 9.2.1
Buktikan bahwa bilangan $4^n - 1$ habis dibagi 3 untuk $\forall n \in \mathbb{N}$
Bukti:
1. Untuk n = 1, diperoleh 4-3 = 3 sehingga habis dibagi 3.
2. Untuk n = k, asumsikan $4^k - 1$ habis dibagi 3 atau $4^k - 1 = 3m$ untuk suatu $m \in \mathbb{N}$. Selanjutnya harus dibuktikan ebrlaku juga untuk n = k + 1. 
   Untuk n = k + 1 diperoleh, 
   $4^{k+1} = 4^k . 4 - 4 + 3 = 4(4^k - 1) + 3 = 4 . 3m + 3 = 3(4m+1)$, sehingga $(4^{k+1} - 1)$
   Karena $(4^{k+1} - 1)$ habis dibagi 3 untuk $n=k+1$ maka $4^n - 1$ habis dibagi 3 untuk $\forall n \in \mathbb{N}$.
Contoh 9.2.2
Buktikan $2n+1 \le 2^n$ untuk bilangan asli $n \geq 3$.
Bukti.
(1) Untuk n=3, $2(3) + 1 = 7$ dan $2^3 = 8$. sehingga $7<8$, jelas dipenuhi
(2) Asumsi berlaku untuk n=k, maka $2k+1<2^k$ untuk n > 3.
Untuk n = k + 1:
- Ruas kiri $2(k+1) + 1 = 2k + 2 + 1 = (2k+1) + 2 < 2^k + 2$
- Ruas kanan $2^{k+1} = 2^k . 2= 2^k + 2^k$ 
Dari ruas kiri dan kanan diperoleh $2(k+1) + 1 < 2^k . 2 < 2^k + 2^k = 2^{k+1}$ sehingga untuk n = k + 1 dipenuhi. Jadi, 2n + 1 < $2^n$ berlaku untuk semua bilangan asli $n\geq3$.

Contoh 9.2.3
Buktikan $n^2 < 2^n$, untuk bilangan asli $n\geq4$.
Bukti.
(1) Untuk n = 4 maka $4^2 = 16 = 2^4$ sehingga n = 4 terpenuhi. (?) you can think $n^2 < 2^n = 4^2 < 2^4 = 16 < 16$? apa yang terpenuhi?
(2) Asumsikan n = k dipenuhi sehingga $k^2 < 2^k$ .
Untuk n = k + 1:
- Ruas kiri $(k+1)^2 = k^2 + 2k + 1$.
- Ruas kanan $2^{k+1} = 2^k.2 = 2^k + 2^k$
Dari ruas kiri dan kanan diperoleh $(k+1)^2 = k^2 + 2k + 1 < 2^k + 2^k = 2^{k+1}$
Karena $2n + 1 < 2^n$ maka $(k+1)^2 < 2^{k+1}$ berlaku untuk n = k +1
Jadi, $n^2 + 2^n$ berlaku untuk bilangan asli $n\geq4$.

Contoh 9.2.4
Buktikan $\forall n \in \mathbb{N}$ berlaku rumus $1+2+3 \dots + n = \frac{1}{2} n(n+1)$ 
Bukti:
(1) Ambil n = 1, ruas kiri 1 dan ruas kanan $\frac{1}{2}(1)(1+1) = 1$
Jadi untuk n = 1, terlihat $1=\frac{1}{2}(1)(1+1)$ sehingga rumus $S(1)$ berlaku.
(2)  Misalkan $S(k)$ atau untuk n = k berlaku, maka $1+2+3+\dots+k=\frac{1}{2}k(k+1)$. Kemudian akan ditunjukkan $S(k+1)$ atau untuk $n=k+1$ berlaku juga. Untuk n=k+1, maka $S(k+1)$ diperoleh:
$1+2+3+\dots+k+(k+1) = \frac{1}{2} k(k+1) + (k+1)$
$=(k+1)\left( \frac{1}{2} k+1\right)$
$= (k+1) \frac{1}{2} (k+2)$
= $\frac{1}{2}(k+1)(k+2)$
sehingga, rumus S(k+1) berlaku untuk n = k + 1. Karena rumus berlaku untuk n = k + 1, maka disimpulkan rumus S(n) yaitu $1+2+3+\dots+n =  \frac{1}{2} n(n+1)$ berlaku $\forall n \in \mathbb{N}$
