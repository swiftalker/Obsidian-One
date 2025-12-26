Teorema 8.2.5
Apabila $A \subseteq \mathbb{N}$ maka A terbilang.
Bukti:
Misalkan A tak terhingga dengan k bilangan terkecil di A sedemikian sehingga buatlah fungsi $f: \mathbb{N} \to A$ dengan f(n) = a+n maka: $f(1) = a + 1; f(2) = a + 2; \dots$  dan seterusnya, sehingga f merupakan fungsi bijektif dan dengan demikian $A \approx \mathbb{N}$. Jadi A terbilang.

Apa yang disebut himpunan tak terhingga adalah ketika suatu himpunan A (misalnya) ekuivalen dengan himpunan bagian sejati dari himpunan bilangan asli $\mathbb{N}$. Atau bisa kita tulis dengan definisi himpunan A terhingga apabila $A \approx N_{k}$ dengan $N_{k} \subset \mathbb{N}$.

Misalkan $A \subseteq B$, jika B terbilang maka A juga terbilang.
Bukti.
Misalkan A tak terhingga dengan elemen terkecil di A. Buatlah fungsi $f: B \to A$ dengan $f(n) = a + n$ sedemikian sehingga $f(1) = a + 1, f(2) = a + 2, dst$ sehinga f merupakan fungsi bijektif, dengan demikian $A \approx B$. Jadi, A terbilang.

Buktikan bahwa himpunan A = {1,2,3,4,5} terhingga!
Bukti:
Himpunan A terdiri dari 5 anggota, misalkan himpunan B={1,11,21,31,41} yang terdiri dari 5 anggota juga dan olehkarenanya jelas $B \subset \mathbb{N}$ dan $A \approx B$. Karena $B \subset \mathbb{N}$ dan $A \approx B$ maka terhingga.

Buktikan bahwa jika A dan B masing-masing himpunan terhingga maka $A \cap B$ juga terhingga.
Bukti.
Karena A dan B masing-masing himpunan terhingga sedemikian sehingga A = $\{a_{1},a_{2},a_{3}, \dots, a_{n}\}$ dan B = $\{b_{1}, b_{2}, b_{3}, \dots, b_{m}\}$ sehingga:
$A \cup B = \{a_{1},a_{2}, \dots, a_{n} \cup \{b_{1},b_{2}, \dots, b_{n} \}$
$=\{a_{1}, a_{2}, \dots, a_{n}, b_{1}, b_{2}, \dots, b_{n}\}$ (1)
Ganti penulisan b dengan $a_{n+1}$ maka (1) menjadi
=$\{a_{1},a_{2},\dots,a_{n},a_{n+1},a_{n+2},\dots,a_{n+m}\}$
Andaikan himpunan bagian $N_{AB} \subset \mathbb{N}$ dengan $N_{AB} = \{1,2,3,\dots,n,n+1,\dots,n+m\}$ sehingga dapat dibuat fungsi satu-satu dan pada $f: (A\cup B)\to N_{AB}$. Jadi, karena $(A\cup B) \approx N_{AB}$ dan $N_{AB} \subset \mathbb{N}$ maka $A \cup B$ berupa himpunan terhingga.
Karena $A \cap B \subseteq A \cup B$. Jadi $A \cap B$ terhingga.

Buktikan bahwa $G = \{\frac{1}{2}: n \in \mathbb{N}\}$ merupakan himpunan tak terhingga.
Bukti.
Misalkan $G = \{\frac{1}{2n}: n \in \mathbb{N}\ = \left\{ \frac{1}{2}, \frac{1}{4}, \frac{1}{6}, \dots \right\}$ sehingga $G \approx \mathbb{N}$. Ambil himpunan $G_{n} = \left\{ \frac{1}{4n}: n \in \mathbb{N} \right\} = \left\{ \frac{1}{4}, \frac{1}{8}, \frac{1}{12}, \dots \right\}$ 
sehingga $G_{n} \approx \mathbb{N}$. Karena $G_{n} \subset G$ dan $G \approx G_{n} \approx \mathbb{N}$ maka G tak terhingga.

Buktikan bahwa himpunan bilangan cacah $\mathbb{C}_{a} = \{ 0, 1, 2, 3, \dots \}$ adalah terbilang.
Bukti.
Karena himpunan terbilang definisinya adalah$A \approx \mathbb{N}$ maka lihat bahwa $\mathbb{C}_{a} \approx \mathbb{N}$ sedemikian sehingga himpunan bilangan cacah adalah terbilang.

Himpunan A = {2,4,6,7,8} ialah terbilang, terhingga, dan terhitung;
Kenapa terhingga:
$A \approx \mathbb{N}_{5} = \{ 1,2,3,4,5 \}$ sebagai contoh $1 \to 2, 2 \to 4, dst$
Jadi A, terhingga.
Kenapa terbilang:
Terbilang berarti $A \approx \mathbb{N}$ karena A hanya punya 5 elemen dan $\mathbb{N}$ memiliki tak hingga elemen tidak ada bijeksi diantara A dan $\mathbb{N}$. Jadi A tak terbilang.
Kenapa terhitung:
Terhitung berarti ia terhingga atau terbilang. Karena A terhingga, jelas A terhitung.

Himpunan B = {2,4,6,...,2n,...}
Kenapa terhingga:
Andaikan B terhingga; Menurut definisi terhingga $\exists k \in \mathbb{N}$ sehingga $B \approx \mathbb{N}$. Artinya ada bijeksi. Dimana $f: N_{k} \to B$. Karena $N_{k}$ memiliki elemen terbesar yaitu k, maka B juga harus memiliki elemen terbesar yaitu $f(k)$. Tetapi pada B selalu memiliki elemen lain yaitu untuk setiap $2n \in B$ dimana $2(n+1) > 2n$ yang juga berada di B. Jadi B tidak memiliki elemen terbesar. Ini bertentangan dengan kesimpulan bahwa B memiliki elemen terbesar. Kontradiksi
Kenapa terbilang:
Karena $B \approx \mathbb{N}$ dan setiap elemen B bijeksi dengan $\mathbb{N}$. Jadi B terbilang.
Kenapa terhitung:
Karena terhingga dan terbilang berarti jelas B terhitung.

Tunjukkan himpunan A ={$(x_{1},x_{2},x_{3},\dots): x_{i} = 0 \cup 1, i \in \mathbb{N}$} tidak terhitung
Bukti.
Jelas bahwa A himpunan tak hingga. Diandaikan A terhitung, maka A denumerabel. Artinya ada enumerasi pada A, atau dengan kata lain A dapat dinyatakan sebagai $A = \{ a_{1}, a_{2}, a_{3}, \dots\}$ dengan $a_{i = (x_{i1}, x_{i2}, x_{i3}, \dots)}$, $x_{ik} = 0$ atau 1 untuk semua $i,k \in \mathbb{N}$. Didefinisikan a = ($a_{11}, a_{22}, a_{33}, ..$), dengan $a_{ii} = 0$ atau 1 dan $a_{ii} \neq x_{ii}$ untuk semua $i \in \mathbb{N}$. Dari definisi, diperoleh $a \in A$. Tetapi karena $a \neq a_{i}$ untuk semua $i \in \mathbb{N}$ maka $a \notin A$. Terjadi kontradiksi. Jadi A tidak terhitung. 