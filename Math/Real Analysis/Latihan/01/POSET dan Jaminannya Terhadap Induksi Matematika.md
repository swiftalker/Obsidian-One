Induksi matematika dijamin oleh 3 hal
- POSET (refleksif, transitif dan anti-simteri)
- Well-foundness
- Well-ordered
Teorema 1.8.1 dan Teorema 1.8.2 dijamin oleh 3 hal tadi

Well ordered ialah "Suatu poset P dikatakan terurut dengan baik bilaman setiap himpunan bagian tak kosong di dalam P mempunyai elemen terkecil"
Jika $P_{1} \subseteq P$ dengan P terurut dengan baik, maka $P_{1}$ juga terurut dengan baik.

Jadi, suatu POSET (P, $\leq$) disebut well-ordered jika:
1. $\leq$ adalah total order
2. Setiap subset tak kosong $S \subseteq P$ memiliki elemen terkecil

Well-founded adalah "Setiap subset tak kosong dari P memiliki elemen minimal tanpa harus total order"

Suatu relasi $\leq$ pada himpunan P disebut total order jika memenuhi 3 sifat POSET dan satu sifat tambahan yaitu:
Untuk setiap $x,y \in P$ selalu berlaku $x\leq y$ atau $y\leq x$

Contoh total order:
1. Bilangan asli $\mathbb{N}$ dengan $\leq$
	- Setiap dua bilangan dapat dibandingkan misal $3 \leq 7$ atau $7 \leq 3$
2. Bilang real $\mathbb{R}$ dengan $\leq$
	- Semua elemen bisa dibandingkan seperti $\mathbb{N}$

Contoh POSET tapi bukan TOSET
Himpunan $\{ (a,b) | a,b \in \mathbb{N} \}$ dengan relasi:
$(a_{1}, b_{1}) \leq (a_{2}, b_{2})$ jika $a_{1} \leq a_{2}$ dan $b_{1} \leq b_{2}$
- Misal (1,3) dan (2,2) tidak bisa dibandingkan karena $1\leq2$ benar, tapi $3\leq2$ salah.
- Ini POSET tapi bukan TOSET

Jadi,
POSET: TIDAK SEMUA BILANGAN BISA DIBANDINGKAN
TOSET: SEMUA BILANGAN BISA DIBANDINGKAN

Jadi dengan 3 hal diatas demikian menjamin Induksi Matematika.

Pendefinisian POSET:
Diberikan himpunan tak kosong P. Relasi $R \subseteq P \times P$ disebut urutan parsial / partial ordering, pada P jika R bersifat
(i) refleksif yaitu (x, x) $\in$ R untuk setiap $x \in P$
(ii) transitif, yaitu jika (x,y) $\in$ R dan (y,z) $\in$ R maka (x,y) $\in$ R dan
(iii) anti-simetri, yaitu jika $(x,y) \in R$ dan $(y,x) \in R$ maka x = y

Pendefinisian TOSET:
- Definisi POSET
- Namun berlaku untuk setiap $(x,y) \in P$ berlaku $x \leq y$ atau $y \leq x$