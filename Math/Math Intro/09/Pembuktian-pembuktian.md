Bukti langsung : $P \to Q$
Bukti tak langsung: $P \to Q$ yang memiliki implikasi equivalen dengan $\neg Q \to \neg P$
### PEMBUKTIAN LANGSUNG
Cotnoh 9.1.2
Diketahui $m,n \in \mathbb{N}$ dengan m dan n keduanya ganjil. Buktikan bahwa (m+n) genap!
Bukti.
P: m bilangan ganjil 
Q: n bilangan ganjil
Maka $P \to Q = (m+n)$ bilangan genap
Sehingga ---
Karena m ganjil maka dapat dinyatakan m = 2k + 1 $, k \in \mathbb{N}$
Karena n ganjil, maka dapat dinyatakan n = 2l + 1, $l \in \mathbb{N}$
Kalau dijumlahkan dapat diperoleh
$m+n=(2k+1)+(2l+1)=2k+2l+2=2(k+l+1)$
Misalkan $(k+l+1) = b, b \in \mathbb{N}$ sehingga $(m+n)=2b$.
Jadi, (m+n) = 2b maka bilangan genap.

### PEMBUKTIKAN TAK LANGSUNG
Contoh 9.1.3
Dengan menggunakan bukti tak langsung, tunjukkan bahwa jika n genap maka n+1 ganjil, $n \in \mathbb{N}$.
Bukti.
Secara sederhana tunjukkan bukti bahwa $P\to Q$ benar dengan menujukkan $\neg Q \to \neg P$ benar. Dimana 
P : n genap
Q: (n+1) ganjil
~P : n ganjil
~Q: (n+1) genap
Sehingga ---
Andaikan n + 1 genap ($\neg Q$), maka dapat dituliskan n+1=2k $, k \in \mathbb{N}$
Ubah n + 1 = 2k menjadi n = 2k -1, selanjutnya n = 2k - 1 = 2k - 2 + 1 = 2(k-1)+1 = 2m + 1 untuk $m \in \mathbb{N}$  sehingga n = 2m + 1 ganjil ($\neg P$). Dengan demikian $\neg Q \rightarrow \neg P$ benar.
Jadi P => Q benar yaitu n genap maka n+1 ganjil.

Contoh 9.1.4
Buktikan bahwa jika $n^3 + 5$ ganjil maka n genap.
Bukti:
P: n genap
$\neg P$: n ganjil
Q: $n^3 + 5$ ganjil
$\neg Q$: $n^3 + 5$ genap

Misalkan n ganjil maka harus ditunjukkan bahwa $n^3 + 5$ genap, atau harus ditunjukkan $\neg Q \to \neg P$. Karena n ganjil maka terdapat bilangan bulat k sehingga $n=2k+1$. Ini memberikan,
$$
n^3 + 5 = (2k+1)^3 + 5
= \{ (2k)^3 + 3(2k)^2(1) + 3(2k)(1)^2 + (1)^3\}+5
= 8k^3 + 12k^2 + 6k + 6
= 2(4k^3 + 6k^2 + 3k + 3)
$$
Jadi terdapat bilangan bulat $m=4k^3 + 6k^2 + 3k + 3$ sehingga $n^3 + 5 = 2m$ genap, $\neg Q \to \neg P$ benar.
Karena $\neg Q \to \neg P$ ekuivalen dengan $P \to Q$ maka $P \to Q$ benar, yaitu jika $n^3 + 5$ ganjil maka n genap.

Contoh 9.1.5
Jika x dan y dua bilangan rasional maka x + y juga rasional.
Bukti.
Karenaa x dan y bilangan rasional, maka terdapat bilangan-bilangan $p,q,m,n \in \mathbb{Z}, m \neq 0, n \neq 0$ sehingga $x=\frac{p}{m}$ dan $y=\frac{q}{n}$. Perhatikan bahwa $x+y = \frac{p}{m} + \frac{q}{n} = \frac{pn+qm}{mn}, pn+qm \in \mathbb{Z}$ dan $mn \in \mathbb{Z}$ dengan $mn \neq 0$ sehingga $\frac{pn+qm}{mn} \in \mathbb{Q}$ . Jadi $x+y$ rasional.

Contoh 9.1.6 
Buktikan, jika $m^2$ ganjil maka m ganjil, $m \in \mathbb{N}$ 
Bukti.
P: $m^2$ ganjil
Q: m ganjil
Sehingga P => Q. Harus dibuktikan $\neg Q \implies \neg P$ atau m bilangan tidak ganjil maka $m^2$ bilangan tidak ganjil. Sedangkan tidak ganjil sama dengan dengan genap, sehingga harus dibuktikan jika $m$ genap maka $m^2$ genap.
Karena m genap maka dapat dinyatakan m=2k dengan k bilangan bulat, sehingga $m^2 = (2k)^2 = 4k^2 = 2(2k^2)$. Jika dinyatakan $2k^2 = l$ maka $m^2 = 2l$ karena $\neg Q \implies \neg P$ ekuivalen $P \implies Q$ maka: jika $m^2$ bilangan ganjil maka m bilangan ganjil.

Contoh 9.1.7
Buktikan, jika n bilangan genap maka n+3 bilangan ganjil untuk $n \in \mathbb{N}$.
Bukti.
Jika n bilangan genap maka n+3 bilangan ganjil: P => Q. Harus dibuktikan $\neg Q \implies \neg P$: jika $n+3$ genap (tidak ganjil) maka n tidak genap / ganjil. 
Misalkan n+3 genap, terdapat $k \in \mathbb{N}$ sehingga n + 3 = 2k. Kemudian ditambahkan kedua ruas dengan -3, sehingga didapati:
n+3+(-3)=2k+(-3) => n=2k-3=2k-4+1=2(k-2)+1
Sehingga (k-2)= sehingga n = 2p+1, jadi n ganjil / tidak genap.

PEMBUKTIAN KONTRADIKSI
Contoh 9.1.8a
Buktikan bahwa $n^2 + n + 1$ adalah ganjil $\forall n\in \mathbb{N}$
Bukti.
Andaikan $n^2 + n + 1$ genap, maka dapat ditulis $n^2+n+1=2k$ untuk suatu $k \in \mathbb{N}$. Ubah $n^2 + n + 1 = 2k$ menjadi $n^2 + n = 2k - 1$ $n(n+1) = 2k -1$. Bentuk terakhir adalah suatu kontradiksi karena $n(n+1)$ genap sedangkan $2k-1$ ganjil. Ini berarti pengandaian bahwa $n^2 + n + 1$ genap adalah salah, yang benar adalah $n^2 + n + 1$ ganjil, $\forall n \in \mathbb{N}$

PEMBUKTIAN EKUIVALENSI
Buktikan bahwa ketiga pernyataan ini ekuivalen:
1) 3n+2 bilangan genap;
2) n+5 bilangan ganjil; dan
3) $n^2$ bilangan genap.
Bukti:
a) $3n+2$  bilangan genap $\iff$ n+5 bilangan ganjil
Untuk masing-masing harus ditunjukkan:
a. $(\implies)$ Jika (3n+2) genap, akan ditunjukkan $(n+5)$ ganjil. Akan dibuktikan dengan kontraposisi. 
Misalkan n+5 genap sedemikian $3n+2$ ganjil. Maka ada k bulat pada n+5 sehingga $n+5 = 2k$, ini setara dengan $3n+15=6k \implies 3n+2=6k-13=6k-12-1=6(k-2)-1$ sehingga $(3n+2)$ ganjil. 
b. ($<=$) Jika n+5 ganjil akan ditunjukkan 3n+2 genap.
n+5 ganjil sehingga ada k bulat maka n+5=2k+1. $(n+5) = 2k+1 \implies n = 2k-4$. Ini memberikan $3n=3(2k-4)=6k-12$ sehingga $3n+2=6k-12+2=6k-10=2(3k-5)$ genap.