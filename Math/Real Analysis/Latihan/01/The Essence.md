# Kegiatan Belajar 1
- Himpunan adalah sekumpulan objek benda dengan sifat atau kriteria tertentu. Objek dalam himpunan disebut anggota atau elemen himpunan tersebut. Himpunan keseluruhan disebut Semesta / Universe. Jika A suatu himpunan dan x anggota A, maka dituliskan $x \in A$. Jika x bukan anggota A, dituliskan $x \notin A$. 
- Diberikan Himpunan A dan B.
	- Himpunan A disebut bagian dari B / subset, dinotasikan $A \subseteq B$, jika setiap anggota A merupakan anggota B.
	- Himpunan A dan B dikatakan sama, dengan notasi A = B, jika A dan B memuat elemen-elemen yang sama, berarti jika setiap anggota A merupakan anggota B dan setiap anggota B merupakan anggota A.
- Sehingga dapat dipahami bahwa dua himpunan A dan B sama jika dan hanya jika $A \subseteq B$ dan $B \subseteq A$. Jika himpunan A tidak kosong, $A \subseteq B$ dan $A \neq B$ maka dikatakan A himpunan bagian sejati B, biasa dinotasikan $A \subset B$.
- Himpunan notasi umum pada analisis real adalah $\mathbb{N}, \mathbb{Z}, \mathbb{Q}, \mathbb{R}$
- Operasi aljabar pada himpunan didefinisikan pada dasar makna kata-kata "ATAU", "DAN", serta "BUKAN". Gabungan didefinisikan dengan notasi $\cup$ dengan misal $A\cup B$ berarti himpunan yang anggotanya ada di A ATAU di B. Irisan didefinisikan dengan notasi $\cap$ adalah himpunan yang anggota-anggotanya adalah terikat dengan kata "DAN".
- ... Pada konsep himpunan sekiranya sudah dipahami, 
###### Konsep Relasi Dan Fungsi
- Sebagai contoh dapat dipahami mengenai perkalian silang, misalnya diberikan himpunan A, B, C, dan D, adalah terdapat soal sebagai berikut: 
  - $A \times (B\cup C) = (A\times B) \cup (A\times C)$
  Jawab:
  Diambil sebarang $(x,y) \in A \times (B \cup C)$ maka $x\in A$ dan $y \in B \cup C$, sementara pada kasus $y \ in B\cup C$ terdapat dua kemungkinkan yaitu $y \in B$ atau $y\in C$. Jika $y\in B$ maka (x,y) = $A\times B$, atau jika $y \in C$ maka (x,y) = $A \times C$. Dengan kata lain, (x,y) $\in (A \times B) \cup (A \times C)$. Sehingga telah dibuktikan kasus pertama ($A \times (B\cup C) \subseteq (A\times B) \cup (A\times C)$). 
  ... Selanjutnya buktikan sebaliknya .. ($(A \times B) \cup (A \times C) \subseteq A \times (B\cup C)$)
  
-  Sekilas tadi mengenai soal perkalian silang, umumnya ketika soal tersebut berbasis "=" maka kita perlu menguji kedua klausa persamaan yaitu ketika sesuatu $\subseteq$ atau sesuatu $\supseteq$.
- Apa itu relasi? sebagai contoh ada himpunan tak kosong A dan B. Dimana relasi dari A ke B adalah suatu himpunan bagian tak kosong $R \subseteq A \times B$. Jika R relasi dari A ke B dan (a,b) $\in$ R, maka biasa dituliskan aRb atau b=R(a).
- Misalnya himpunan $R = {(x,y): x^2 + y^2 = 1}$ merupakan relasi dari [-1,1] ke [-1,1]. Maka dengan definisi tersebut ini dapat dipandang sebagai relasi dari $\mathbb{R}$ ke $\mathbb{R}$.
- Misalnya A = {a,bc,d} dan B={1,2,3}. Maka $$
R_{1} = \{(a,1), (b,2)\}
R_{2} = \{(a,1), (b,2), (c,1), (d,3)\}
R_{3} = \{(a,1), (a,2), (b,2), (c,1), (d,3) \}
$$
- Terlihat bahwa $R_{2}$ mempunyai sifat "untuk setiap $x \in A$ terdapat tepat satu $y\in B$ sehingga (x,y) $\in R_{2}$ atau $y=R_{2}(x)$". Relasi yang demikian disebut fungsi atau pemetaan dari A ke B, 
- Diberikan himpunan tak kosong A dan B. Relasi R dari A ke B disebut fungsi jika untuk setiap $x \in A$ terdapat tepat satu $y\in B$ sehingga (x,y) $\in R$ atau y=R(x).
- $$
R_{1} = \{(a,1), (b,1), (c,2), (d,3)\} \\
R_{2} = \{(a,1), (c,2), (d,3)\} \text{ dan }
R_{3} = \{(1,2), (2,b), (3,d)\}
$$
- Melihat definisi fungsi, $R_{1}$ merupakan fungsi dari A ke B dan $R_{3}$ merupakan fungsi dari B ke A. Akan tetapi $R_{2}$ bukan merupakan fungsi dari A ke B, karena ada anggota A, yaitu b, yang tidak memiliki pasangan di B, biasanya fungsi dinotasikan dengan huruf-huruf: f,g,h,F, G, .. dan seterusnya, meskipun bukan suatu keharusan jika f merupakan fungsi dari A ke B: maka dituliskan $f: A \to B$.

# Kegiatan Belajar 2
- Urutan baik / Well ordering merupakan 
$\lvert  \rvert$