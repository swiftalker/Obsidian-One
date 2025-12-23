Contoh 1.7.2
Diperhatikan himpunan $P_{1}, P_{2} \subseteq \mathbb{R}^2$ dengan $P_{1} = \{ (x,y) : 0 \leq x \leq 2, 1 \leq y \leq 4\}$ dan $P_{2} = \{ (x,y) : 0 < x \leq 2, 1 < y \leq 4\}$. Elemen (0,1) dan elemen (2,4) masing-masing merupakan elemen terkecil dan elemen terbesar di $P_{1}$. Sementara, $P_{2}$ tidak mempunyai elemen terkecil.

Bukti.

Diambil sebarang $(x,y) \in P_{1}$, maka $0\leq x\leq_{2}, 1\leq y\leq4$. Akibatnya, $(0,1) \leq (x,y \leq (2,4)$ . Karena $(0,1), (2,4) \in P_{1}$ maka (0,1) dan elemen (2,4) masing-masing merupakan elemen terkecil dan elemen terbesar di $P_{1}$.
Diambil sebarang $(x,y) \in P_{2}$ maka $0<x\leq2$ dan $1<y\leq4$. Jika diambil $u=\frac{1}{2}x$ dan $v=\frac{y+1}{2}$ maka 0 < u $\leq$ 1 dan $\frac{1+1}{2} < v \leq \frac{4+1}{2}$ . Ini berarti $(u,v) \in P_{2}$. Akan tetapi karena (u,v) < (x,y) maka (x,y) bukanlah elemen terkecil. Karena hal ini berlaku untuk sebarang $(x,y) \in P_{2}$ maka $P_{2}$ tidak mempunyai elemen terkecil.

Induksi matematika dijamin 2 hal, yaitu:
- Poset atau himpunan terurut parsial (PARTIALLY ORDERED SET) -> $(\mathbb{N}, \leq)$ (Refleksif, Transitif, dan Anti-simetri)
- Sifat urutan baik yang menjamin jika setiap himpunan bagian tak kosong dalam himpunan P memiliki elemen terkecil

Teorema 1.8.1
Setiap himpunan bagian tak kosong di dalam $\mathbb{N}$ mempunyai elemen terkecil. Dengan asumsi sifat urutan baik.

Teorema 1.8.2 (Prinsip Induksi Matematika)
Diberikan sebarang himpunan bagian $S \subseteq \mathbb{N}$. Jika dipenuhi sifat-sifat berikut:
(i) $1\in S$, dan
(ii) untuk sebarang $n \in \mathbb{N}$, jika $n \in S$, berakibat $n + 1 \in S$ maka $S = \mathbb{N}$

Bukti. 

Diandaikan $S \neq \mathbb{N}$ maka $\mathbb{N}-S \subset \mathbb{N}$ dan $\mathbb{N} - S \neq \emptyset$. Menurut teorema 1.8.1, $\mathbb{N} - S$ mempunyai elemen terkecil, dinamakan m. Akan ditunjukkan m > 1. Misalkan m = 1, karena $1 \in S$, maka $m = 1 \in S$. Hal ini kontradiksi karena $m \in \mathbb{N} - S$, jadi m > 1.
Selanjutnya, karena ma - 1 < m dan elemen m terkecil di dalam $\mathbb{N} - S$ maka $m-1 \notin \mathbb{N}-S <=> m - 1 \in S$. Berdasarkan hipotesis (ii), m = (m-1)+1 $\in$ S. Hal ini kontradiksi dengan $m\in \mathbb{N} - S$. Jadi haruslah $S = \mathbb{N}$

Prinsip-prinsip induksi matematika sering pula diformulasikan dalam bingkai sifat-sifat atau pernyataan terkait bilangan asli, hal itu dinyatakan dalam teorema 1.8.3

Teorema 1.8.3
MIsalkan $P(n)$ menyatakan sifat yang berlaku untuk sebarang bilangan asli $n \in \mathbb{N}$ yang diberikan. Jika:
(i) P(1) benar dan
(ii) diandaikan P(n) benar, berakibat P(n+1) benar, maka P(n) benar untuk setiap $n \in \mathbb{N}$

Bukti. 

Didefinisikan $S=\{ n \in \mathbb{N}: P(n) benar\}$, menurut (i) $1 \in S$ , selanjutnya menurut (ii) berlaku: $n \in S \implies n + 1 \in S$. Jadi, menurut teorema 1.8.2, $S = \mathbb{N}$. Dengan kata lain, P(n) benar untuk setiap $n \in \mathbb{N}$. Kadang dijumpai suatu keadaan dimana sifat P(n) benar untuk $n \geq n_{0}$ untuk sutau $n_{0} \in \mathbb{N}$. Sebagai contoh, $2^n > 2n + 1$ salah untuk n=1,2, tetapi benar untuk semua bilangan asli $n\geq3$.
Prinsip induksi matematika dapat dimodifikasi untuk situasi sebagaimana disebutkan diatas. Adapun reformulasi prinsip induksi matematika untuk keadaan tersebut, diberikan dalam teorema berikut. 

Teorema 1.8.4
Misalkan $n_{0} \in \mathbb{N}$ dan P(n) menyatakan sifat yang berlaku untuk sebarang bilangan asli $n \geq n_{0}$. Jika
(i) P($n_{0}$) benar dan
(ii) untuk $n \geq n_{0}$ kebenaran P(n) berakibat $P(x + 1)$ benar, maka P(n) benar untuk setiap $n \geq n_{0}$

Bukti. 

Didefinisikan $Q(n)$ dengan $Q(n) = P(n+n_{0}-1), n \in \mathbb{N}$. Menurut (i), $Q(1) = P(n_{0})$ benar. Selanjutnya, diandaikan $Q(n)$ benar, artinya P(k), dengan $k = n + n_{0} - 1 \geq n_{0}$ benar. Akibatnya, menurut (ii), P(k+1) = $P(n+n_{0})$ benar. Perhatikan bahwa $P(k+1)=P(n+n_{0})=Q(n+1)$. Jadi, jika diandaikan Q(n) benar, diperoleh Q(n+1) benar. Dengan demikian, teorema terbukti menurut Teorema 1.8.3.

Contoh 1.8.5
a. Tunjukkan $\frac{1}{1.2} + \frac{1}{2.3} + \dots + \frac{1}{n(n+1)} = \frac{n}{n+1}$ untuk setipa $n \in \mathbb{N}$.
Bukti.
Didefinisikan
S = {$n\in \mathbb{N} : \frac{1}{1.2} + \frac{1}{2.3} + \dots + \frac{1}{n(n+1)} = \frac{n}{n+1}$} 
(i) $1\in S$ karena $\frac{1}{1.2} = \frac{1}{1+1}$ 
(ii) Diandaikan $n \in S$ artinya $\frac{1}{1.2} + \frac{1}{2.3} + \dots + \frac{1}{n(n+1)} = \frac{n}{n+1}$ maka $\frac{1}{1.2} + \frac{1}{2.3} + \dots \frac{1}{n(n+1)} + \frac{1}{(n+1)(n+2)} = \frac{n}{(n+1)} + \frac{1}{(n+1)(n+2)} = \frac{n(n+2)+1}{(n+1)(n+2)} = \frac{(n+1)^2}{(n+1)(n+2)} = \frac{n+1}{(n+1)+1}$
yaitu $n+1 \in S$. Jadi menurut teorema 1.8.2, S = $\mathbb{N}$  atau dengan kata lain $\frac{1}{1.2} + \frac{1}{2.3} + \dots + \frac{1}{n(n+1)} = \frac{n}{(n+1)}$ untuk setiap $n\in \mathbb{N}$.
b. Tunjukkan bahwa untuk setiap $n \in \mathbb{N}, n^3 + (n+1)^3 + (n+2)^3$ habis dibagi 9.
Bukti.
(i) Untuk n=1, $1^3 + (1+1)^3 + (1+2)^3 = 36$ habis dibagi 9. Jadi pernyataan benar untuk n = 1.
(ii) Diandaikan pernyataan benar untuk n, artinya $n^3 + (n+1)^3 + (n+2)^3$ habis dibagi 9. Selanjutnya, karena $(n+1)^3 + ((n+1)+1)^3 + ((n+1)+2)^3 = (n+1)^3 + (n+2)^3 + (n+3)^3 = (n+1)^3 + (n+2)^3 + n^3 + 9n^2 + 27n + 27$ 
$= \{ n^3 + (n+1)^3 + (n+2)^3 \}  + 9\{n^2 +3n + 3\}$ 
dengan $n^3+(n+1)^3+(n+2)^3$ dan $9\{n^2+3n+3\}$ masing-masing habis dibagi 9, maka $(n+1)^3+((n+1)+1)^3 + ((n+1)+2)^3$ habis dibagi 9. Jadi, menurut teorema 1.8.3 pernyataan terbukti.