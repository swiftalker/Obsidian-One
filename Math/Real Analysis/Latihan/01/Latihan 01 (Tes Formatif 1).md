1. Untuk sebarang himpunan A dan B, tunjukkan (A-B) $\cap$ (B-A) = $\emptyset$
    
    Jawab:
    
    Diambil sebarang x diantara $(A-B) \cap (B-A)$ sehingga $x \in A - B$ dan $x \in B - A$, yang berarti $x \in A$ sekaligus $x \notin B$ dan $x \in B$ sekaligus $x \notin A$, ini menimbulkan kontradiksi karena x juga diantara keduanya, sehingga jelas bahwa $(A-B) \cap (B-A) = \emptyset$
    
2. Tunjukkan $(A \cup B) - C = (A-C) \cup (B-C)$
    Jawab:
    (⇒) Diambil sebarang $x \in (A \cup B) - C$ sedemikian $x \in (A \cup B)$ dan $x \notin C$ sehingga jelas bahwa $x \in A$ atau $x \in B$ tetapi tidak untuk $x \in C$, atau ini bisa disamakan dengan $x \in A$ juga $x\notin C$ serta $x \in B$ namun tidak $x \in C$, sehingga $x \in (A-C) \cup (B-C)$.
    
    (≤) Selanjutnya apakah benar bahwa $x\in(A-C)\cup(B-C)$ berlaku $x\in (A\cup B) - C?$ Karena $x \in (A-C) \cup (B-C)$ maka $x \in (A - C)$ atau $x \in (B-C)$ sehingga $x \in A$ namun $x \notin C$, serta $x \in B$ namun $x \notin C$ sehingga $x \in (A \cup B) - C$.
    
3. Diberikan fungsi $f: \mathbb{R} \to \mathbb{R}$ . Untuk sebarang $A \subset \mathbb{R}$, didefinisikan $f^{-1} (A) = \{x \in \mathbb{R}: f(x) \in A\}$ dan $f(A) = \{f(x): x \in A\}$
    
    Tunjukkan:
    
    1. $f^{-1} (A\cup B) = f^{-1} (A) \cup f^{-1} (B)$
        
        Jawab:
        
        (→) Diambil sebarang $x \in f^{-1} (A \cup B)$ berdasarkan definisi fungsi invers, berarti prapeta x terhadap $f^{-1} (A\cup B)$ sedemikian $f(x) \in A \cup B$ berarti juga $f(x) \in A$ atau $f(x) \in B$. Akibatnya jika $f(x) \in A$ atau $f(x) \in B$ berakibat $x \in f^{-1} (A)$ atau $x \in f^{-1} (B)$. Karena akibat tersebut diantaranya diharuskan benar, sehingga $x \in f^{-1} (A) \text{ atau } x \in f^{-1} (B)$ yang berarti $x \in f^{-1} (A) \cup f^{-1} (B)$.
        
        (←) Buktikan $f^{-1} (A) \cup f^{-1} (B) \subseteq f^{-1} (A\cup B)$, diambil sebarang x dari $f^{-1} (A) \cup f^{-1} (B)$ berarti $x \in f^{-1} (A)$ atau $x \in f^{-1} (B)$. Berdasarkan definisi prapeta berarti $f(x) \in A$ atau $f(x) \in B$. Karena diantara dua klausa tersebut haruslah benar, maka ini sama dengan $f(x) \in A \cup B$. Dan karena $f(x) \in A \cup B$ sedemikian maka x pasti anggota prapeta dari himpunan $x \in f^{-1} (A \cup B)$.
        
        Karena kedua inklusi tersebut terbukti benar maka $f^{-1} (A \cup B) = f^{-1} (A) \cup f^{-1} (B)$ adalah benar.
        
    2. $A \subset f^{-1} (f(A))$
        
        Jawab:
        
        Misalkan $x \in A$, $f(A)$ berarti himpunan semua hasil dari pemetaan dari elemen-elemen A. Karena $x \in A$ maka hasil pemetaan nya yaitu $f(x)$ pasti merupakan anggota dari $f(A)$. Sehingga $f(x) \in f(A)$. Lihat bahwa himpunan $f^{-1}(f(A))$ adalah himpunan-himpunan yang dimana isi nya merupakan hasil pemetaan dari $f(A)$. Demikian kita sudah menunjukan bahwa $f(x)$ adalah anggota dari $f(A)$, karena x adalah elemen yang menghasilkan f(x) yang berada dalam f(A), maka x itu sendiri haruslah menjadi anggota dari prapeta dari $f(A)$. Jadi, $x \in f^{-1} (A)$
        
4. Lihat soal nomor 3, Apakah $f^{-1} (f(A)) = A?$ Jelaskan jawaban saudara
		
    Jawab:
    
    Periksa dua inklusi:
    
    Apakah $A \subseteq f^{-1} (f(A)$ dan $f^{-1} (f(A)) \subseteq A$
    
    ($\subseteq$) Diambil sebarang $x \in A$, menurut definisi peta adalah $f(y) = \{f(y) : y \in A\}$, karena $x \in A$ maka hasil pemetaannya yaitu $f(x)$ haruslah berada di $f(A)$. Jadi, $f(x) \in f(A)$. Perhatikan bahwa definisi prapeta adalah $f^{-1} (Y) = \{ z \in \mathbb{R}: f(z) \in Y \}$. Misalkan $Y = f(A)$, karena telah dibuktikan bahwa $f(x) \in f(A)$, maka x memenuhi syarat untuk menjadi anggota dari $f^{-1} (f(A))$. Sehingga, $x \in f^{-1} (f(A))$. Demikian konklusi pertama ini benar untuk setiap $A \subseteq f^{-1} (f(A))$.
    
    ($\supseteq)$ $f^{-1} (f(A)) \subseteq A$, akan dibuktikan dengan percobaan _counterexample ,_ sebagai misal “Misalkan $f: \mathbb{R} \to \mathbb{R}$ didefinisikan dengan formulasi $f(x) = x^2$ . Fungsi ini tidak injektif karena sebagai contoh $f(2) = 4$ dan $f(-2) = 4$. Misalkan $A \subset \mathbb{R}$ dengan A = {2}. Hitung $f(A) = f(\{2\}) = \{f(2)\} = {2^2} = {4}$.
    
    Bisa kita hitung $f^{-1} (f(A))$ = $f^{-1} (4)$, menurut definisi prapeta adalah $f^{-1} (X) = \{ y \in \mathbb{R} : f(y) \in X \}$ = $\{ y \in \mathbb{R} : f(y) \in \{4\} \}$ Ini berarti kita mencari semua nilai y yang mungkin untuk memenuhi f(y) = 4 sedemikian $y^2 = 4$ maka $f^{-1} (4) = \{-2, 2\}$.
    
    Boleh kita lihat bahwa A = {2} dan $f^{-1} (f(4)) = \{-2, 2\}$ . Jelas bahwa $\{ -2, 2 \} \not\subseteq \{2\}$ dan tentu saja ini karena $f^{-1} (f(A))$ terdapat elemen -2 disana serta ini tidak ada di himpunan A. Akibatnya $f^{-1} (f(A))$ = A tidak benar secara umum.
    
    ($\supseteq$) Boleh jadi sebelumnya adalah bukti berdasarkan _counterexample_ dan pada dasarnya ini bukanlah pembuktian formal, kita harus mencobanya dengan pembuktian formal seperti apa? Berikut buktinya:
	    
    Diambil sebarang $x \in f^{-1} (f(A))$ berdasarkan definisi prapeta $f^{-1} (A) = \{ x \in \mathbb{R} : f(x) \in A \}$ berarti peta dari $x$ ialah $f(x)$ yang adalah anggota dari himpunan A sedemikian $f(x) \in f(A)$. Selanjutnya, apa itu $f(x) \in f(A)$ ? Kita harus melihat ini dari sisi peta agar dapat menjawabnya, berdasarkan definisi peta yaitu $f(A) = \{ f(x) : x \in A \}$ berarti terdapat suatu elemen a’ didalam A yang hasil petanya sama dengan f(x). Maka terdapatlah $a' \in A$ sedemikian sehingga $f(x) = f('a)$. Kita memiliki informasi bahwa terdapat $f(x) = f(a')$ dimana $a' \in A$. Tujuan kita adalah untuk membuktikan bahwa $x \in A$. Namun dari $f(x) = f(a')$ tidak bisa disimpulkan secara logis bahwa x = a’. Definisi dasar sebuah fungsi tidak melarang dua input yang berbeda (x dan a’) untuk memiliki output yang sama (f(x) dan f(a’)). Untuk membuktikan lebih lanjut kita harus membuktikan bahwa f sendiri injektif sehingga f(x) = f(a’) sedemikian x = a’ diperlukan syarat tambahan berupa f haruslah injektif, dikarenakan f diasumsikan untuk sebarang f sehingga kita tidak dapat membuat kesimpulan tersebut. Akibatnya bukti $x \in f^{-1} (f(A))$ tidaklah benar.
    
5. Diberikan $f: \mathbb{N} \to \mathbb{N}$ dengan formulasi
    $f(n) = \begin{cases} 2n, & \text{n genap} \\ n, \text{n ganjil} \end{cases}$
    Selidik apakah f injektif? surjektif?
    Jawab:
    Diambil sebarang $n \in \mathbb{N}$ , dengan definisi peta dan prapeta $f(n) = \{ f(x) : x \in n \}$ dan $f^{-1} (N) = \{ x \in \mathbb{N} : f(x) \in N \}$  <= ini bukan "cara" menjawab yang tepat, karena kita dituntut untuk menguji sifat surjektif dan injektif dari $f(n)$ daripada mencari peta dan prapeta. Oleh karena itu, maka kita akan cari definisi injektif dan surjektif nya.
    
	 Jadi, apakah $f(n)$ adalah injektif? 
	 Definisi injektif berdasarkan definisi 1.4.6 sebuah fungsi f disebut injektif jika dia memiliki input yang berbeda maka output yang dihasilkan juga pasti berbeda. Dengan kata lain, jika $f(x) = f(y)$ maka haruslah x=y.
	 
	 Untuk membuktikan bahwa $f(n)$ apakah injektif, diambil x=1, dan karena x = 1 maka berlaku f(n) dengan n ganjil sehingga f(1) = 1. Selanjutnya diambil y = 2, karena y merupakan bilangan ganjil sedemikian berlaku f(n) pertama maka f(2) = 2(2) = 4. Karena terdapat $x,y \in \mathbb{N}$ dengan $x\neq y$ namun diharuskan $f(x) = f(y)$ maka ini bertentangan dengan definisi fungsi injektif. Jelas bahwa f(n) bukan injektif.
	 
	 Kemudian, apakah f(n) adalah surjektif?
	 Definisi surjektif berdasarkan definisi 1.4.6, ialah sebuah fungsi f disebut surjektif jika untuk setiap elemen y di kodomain y (dalam kasus ini $\mathbb{N}$), terdapat sebuah elemen n di domain $\mathbb{N}$ sedemikian sehingga f(n) = y.
	
	Ambil sebarang $y \in \mathbb{N}$ sebagai elemen kodomain. Apakah benar terdapat setiap $n \in \mathbb{N}$ yang menjadi prapetanya? karena terdapat dua kasus dari f(n), maka:
	Kasus 1, y bilangan ganjil:
	 -  Misal n = y. Karena y ganjil, maka n juga ganjil. Menurut definisi fungsi untuk n ganjil, diperoleh f(n) = f(y) = y. Pada kasus ini berhasil kita dapati n yang memenuhi
	Kasus 2, y bilangan genap:
	 - Misal n = 2y. Karena n adalah bilangan asli, maka n = 2y adalah bilangan asli genap. Menurut definisi fungsi f untuk n genap, diperoleh f(n) = f(2y) = (2y)y = $2y^2$. Untuk kasus ini berhasil menemukan n yang memenuhi.
	
	Karena untuk sebarang $y \in \mathbb{N}$ (apakah ganjil atau genap) kita selalu dapat menemukan $n \in \mathbb{N}$ sedemikian sehingga f(n) = y, maka terbukti bahwa f adalah surjektif.
	
	Jadi, f(n) bukanlah injektif namun surjektif.
1. Tentukan daerah definisi fungsi, jika
	a. $f(x) = \sqrt(x^2-1)$
	b. $f(x) = \frac{x-1}{x} + \sqrt{4-3x-x^2}$ 
	Jawab:

	a. $f(x) = \sqrt{(x^2 - 1)}$
	Sebuah fungsi akar kuadrat $f(x) = \sqrt{ g(x) }$ terdefinisi dalam himpunan bilangan real ($\mathbb{R}$) jika dan hanya jika ekspresi dalam akar bernilai $\geq$ 0 / non negatif. Akibatnya, daerah definisi dalam fungsi $f(x) = \sqrt{ (x^2-1) }$ adalah himpunan $\{ x\in \mathbb{R} : x^2 - 1 \geq 0 \}$. Sedemikian $x^2 \geq 1$ berakibat (x+1)(x-1) = 0. Sehingga $x = 1 \cup x = -1$. 
	
	Karena titik-titik tersebut membagi garis bilangan real menjadi $(-\infty, -1]$, [-1, 1], $[1, \infty])$. Maka akan diuji nilai pada setiap interval untuk memenuhi pertidaksamaan:
	1. Untuk interval $(\infty, -1]$, semisal x = -2: (-2 - 1)(-2 + 1) = (-3)(-1) = $3 \geq 0$
	2. Untuk interval [-1, 1], semisal x = 0: (0 - 1)(0 + 1) = -1 < 0
	3. Untuk $[1, \infty)$, semisal x = 2: (2 - 1)(2 + 1) = (1)(3) = 3 $\geq$ 0
	Dengan demikian, hanya [-1, 1] saja yang tidak memenuhi dari pertidaksamaan tersebut, sehingga himpunan penyelesaian dari pertidaksamaan tersebut adalah gabungan dari interval yang memenuhi.
	
	Sehingga, daerah fungsi f terhadap $D_f =\{x \in \mathbb{R} | x \leq -1 \cup x \geq 1\}$  atau dalam notasi interval $(-\infty, -1] \cup [1, \infty)$.

	b. $f(x) = \frac{x-1}{x} + \sqrt{ 4-3x-x^2 }$
	Fungsi f(x) merupakan hasil penjumlahan dari dua fungsi, yaitu fungsi $g(x) = \frac{x-1}{x}$ dan fungsi irasional $h(x) = \sqrt{ 4-3x-x^2 }$. Agar f(x) terdefinisi, kedua fungsi f(x) dan g(x) harus terdefinisi. Sehingga, daerah definisi f(x) adalah irisan dari fungsi g(x) dan h(x) yaitu $D_{f} = D_{g} \cap D_{h}$.
	
	- Fungsi g(x) = $\frac{x-1}{x}$sedemikian sehingga $x \neq 0$ sehingga $D_{g} = \{ x \in \mathbb{R} : x \neq 0 \}$
	- Fungsi h(x) = $\sqrt{ 4-3x-x^2 }$ haruslah $\geq 0$, maka $4-3x-x^2 \geq 0$ atau $x^2-3x+4 \geq 0$ kemudian kalikan -1 sedemikian $-x^2 + 3x -4\leq 0$ sehingga (x+4)(x-1) <= 0 atau faktor-faktornya ialah x = -4 atau x = 1. Karena pertidaksamaan bertanda $\leq$ dan $x^2$ positif, solusinya berada di antara kedua titik pembuat nol. Jadi $D_{h} = \{ x\in \mathbb{R} : -4 \leq x \leq 1\}$
	
	Sehingga, $D_{f} = D_{g} \cap D_{h}$ = $\{ x\in \mathbb{R} | -4 \leq x \leq 1, x \neq 0 \}$.
	
1. Tentukan daerah hasil f jika $f(x) = \frac{2x-1}{x+1}$
	Jawab:
	Definisi daerah hasil, ialah $R(f) = \{x \in \mathbb{R} : f(x) \in A \}$ untuk $f: A \to B$. Sehingga jika $f(x) = \frac{2x-1}{x+1}$  maka $x + 1 \neq 0$ atau $x=-1$ diakibatkan pecahan tidak boleh memiliki nilai = 0.  
	
	Selanjutnya, misal $y=f(x)=\frac{2x-1}{x+1}$ maka $y(x+1)=2x-1 \implies yx + y = 2x -1 \implies yx -2x = -1-y \implies  x(y-2)=-(1+y) \implies x = \frac{1+y}{y-2}$.
	Jika $y - 2 \neq 0 \implies y \neq 2$. Semisal y = 2, jelas tidak mungkin. Jadi, secara domain untuk $x=-1$ tidak diijinkan dan secara range y = 2 tidak diizinkan.
	
	Kesimpulannya ialah $R(f) = \{ x \in \mathbb{R} : x \neq 2\}$.
	
1. Tentukan $f(\mathbb{R})$ jika
	$$
	f(x) = \begin{cases}
	x + \frac{1}{x}, & x > 0 \\
    3x - 1, & x \leq 0
	\end{cases}
	$$
	Jawab:
	Untuk menentukan $f(\mathbb{R})$, tunjukkan daerah hasil / range dari fungsi f untuk seluruh domain nya, $\mathbb{R}$. Pecah domain $\mathbb{R}$ menjadi dua bagian sesuai definisi fungsinya yaitu $A = \{x \in \mathbb{R} | x \leq 0 \}$ dan $B =\{ x \in \mathbb{R} | x > 0\}$. Sehingga daerah hasil totalnya adalah gabungan dari daerah hasil kedua bagia ntersebut $f(\mathbb{R}) = f(A) \cup f(B)$.
	
	Kasus 1: f(A) untuk $A = \{ x | x \leq 0\}$. Pada domain ini, fungsi yang berlaku adalah f(x) = 3x-1.
	
	Fungsi ini adalah linear dengan gradien positif, yang berarti f(x) adalah naik monoton. Karena naik monoton, nilai maksimum dari potongan ini akan terjadi pada nilai x terbesar dalam domainnya, yaitu x = 0. Karena domainnya tidak terbatas ke bawah ($x \to - \infty$). aka nilai f(x) juga tidak terbatas ke bawah ($f(x) \to -\infty$). Jadi daerah hasil untuk bagian ini adalah $f(A) = (\infty, -1]$.
	
	Kasus 2: f(B) untuk $B = \{ x | x > 0 \}$. Pada domain ini fungsi yang berlaku adalah $f(x) = x + \frac{1}{x}$ .
	
	Cari nilai minimum dari fungsi ini pada domain x > 0. Dapat digunakan pertidaksamaan rata-rata aritmetika-geometrika yang idenya serupa dengan berbagai pertidaksamaan di modul 2.
	
	Karena x > 0, maka $\frac{1}{x}$ juga > 0. Untuk dua bilangan positif x dan $\frac{1}{x}$, berlaku: 
	$$
\frac{x+\frac{1}{x}}{2} \geq \sqrt{ x \cdot \frac{1}{x} } 

$$	
$$
\frac{x+\frac{1}{x}}{2} \geq \sqrt{ 1 }
$$
$$
\frac{f(x)}{2} \geq 1
$$
$$
f(x) \geq 2
$$
	Ini menujukkan bahwa nilai minimum dari f(x) pada domain ini adalah 2. (Nilai minimum ini tercapai saat x = $\frac{1}{x}$, yaitu $x^2 = 1$ sehingga x = 1). Saat $x \to \infty$ atau $x \to 0^+$ nilai f(x) akan menuju $\infty$.
	Jadi, daerah hasil untuk bagian ini adalah f(B) = $[2, \infty]$.
	Jadi menggambungkan daerah hasil total $f(\mathbb{R})$ adalah gabungan dari f(A) dan f(B). $f(\mathbb{R}) = f(A) \cup f(B) = (-\infty, -1] \cup [2, \infty)$. Jadi, $f(\mathbb{R}) = \{ y \in \mathbb{R} | y \leq -1  \cup y \geq 2\}$.
9. Diberikan fungs-fungsi $f,g: \mathbb{R} \to \mathbb{R}$ dengan rumus
   $$
f(x) = \begin{cases}
x, & x \geq 0 \\
3 + x, & x < 0
\end{cases}
$$
$$
, g(x) = \begin{cases}
1-x,& x \geq 0  \\
\frac{(x-1)}{x}, & x < 0
\end{cases}
$$
	Tentukan rumus untuk $g \circ f$.
	Jawab:
	Berdasarkan definisi fungsi komposisi (Definisi 1.6) dimana suatu fungsi $f: A \to B$ disebut fungsi jika ia fungsi injektif (fungsi 1-1), dimana untuk setiap $x,y\in A$ dengan $x\neq y$ berakibat $f(x) \neq f(y)$, fungsi surjektif jika untuk setiap $y \in B$ terdapat $x \in A$ berakibat $y=f(x)$, fungsi bijektif (korespondensi 1-1), jika f injektif sekaligus surjektif. Dimana $(g\circ f)(x) = g(f(x))$. Aturan fungsi g bergantung pada apakah inputnya yaitu f(x) bernilai $\geq 0$ atau $< 0$.
	
	Analisa f(x) berdasarkan domain x.
	Kasus 1: Domain $x \geq 0$.
	Pada domain ini f(x) = x. Karena $x \geq 0$, maka keluaran f(x) juga harus $\geq 0$. Karena input untuk g adalah $f(x) \geq 0$, gunakan aturan pertama dari g(y) yaitu g(y) = 1-x. Maka g(f(x)) = 1 - f(x) = 1 - x.
	
	Kasus 2: Domain x < 0
	Pada domain ini, f(x) = 3 + x. Kapan $3+x \geq 0$ dan kapan 3 + x < 0?
	Sub-kasus 2a: Misal $f(x) \geq 0$ => $3+x \geq 0$ => $x \geq -3$. Domain untuk sub-kasus ini adalah gabungan dari x < 0 dan $x\geq-3$, yaitu $-3 \leq x < 0$. Karena $f(x) \geq 0$, gunakan aturan pertama g(y) = 1 - y.g(f(x)) = 1 - f(x) = 1 - (3+x) = -2 - x.
	Sub-kasus 2b: Misal $f(x) < 0$ => $3+x < 0$ => $x < -3$. Domain untuk sub kasus ini adlaah x < -3. Karena f(x) < 0, gunakan aturan kedua g(y) = $\frac{(y-1)}{y}$. $g(f(x)) = \frac{f(x) - 1}{f(x)} = \frac{(3+x)-1}{3+x} = \frac{2+x}{3+x}$.
	Dengan menggabungkan semua kasus, diperoleh rumus untuk $g \cirf f$:
	$$
 (g \circ f) = \begin{cases}
\frac{2+x}{3+x}, & x<-3   \\
-2 - x, & -3 \leq x < 0  \\
1 - x, & x \geq 0
\end{cases}
$$
9. Diberikan fungsi $f: \mathbb{R} \to \mathbb{R}$ dengan rumus
$$
f(x) = \begin{cases}
x^2, & x \geq 0  \\
3x, & x < 0
\end{cases}
$$
	Tentukan $f^{-1}(x)$.
	Jawab:
	Untuk menentukan fungsi invers $f^{-1}$, balik prosesnya. Atur y = f(x) dan menyelesaikan x dalma bentuk y. Tentukan juga daerah hasil / range dari setiap potongan f untuk menjadi daerah definisi atau domain dari $f^{-1}$. 
	
	Kasus 1: Domain $x \geq 0$
	Fungsi y = f(x) $= x^2$. Jika $x\geq0$, maka y = $x^2 \geq 0$. Jadi daerah hasil untuk potongan ini adalah $y\geq0$. Sehingga $y=x^2 \to x = \pm \sqrt{ y }$. Karena domain untuk potongan ini adalah $x \geq 0$, pilih akar non negatif sedemikian x = $\sqrt{ y }$. Sehingga $f^{-1} (y) = \sqrt{ y }$, untuk domain $y \geq 0$.
	
	Kasu 2: Domain x < 0
	Fungsi y = f(x) = 3x. Jika x < 0, maka y  = 3x < 0. Jadi, daerah hasil untuk potongan ini adalah y < 0. Sedemikian sehingga y = 3x => x = y/3. NIlai x = y/3 ini secara otomatis memenuhi domain x < 0 karena y < 0. $f^{-1} (y) = \frac{y}{3}$ untuk domain y < 0 .
	
	Dengan menggabungkan kedua potongan dan mengganti variabel y kembali ke x untuk notasi standar, kita dapatkan $$f^{-1} = \begin{cases}
\sqrt{ x }, x \geq 0 \\ \\
\frac{x}{3}, x < 0
\end{cases}$$

GLOSARIUM:
1. Definisi fungsi: 
2. Definisi prapeta:
3. Definisi peta:
4. Definisi injektif:
5. Definisi surjektif:
6. Peta dan prapeta adalah konsep yang berlaku setelah domainnya ditentukan.