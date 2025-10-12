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
	
	Jawaban yang lebih make sense: [here](GPT-Answer.md)
1. 
    
2. s

GLOSARIUM:
1. Definisi fungsi: 
2. Definisi prapeta:
3. Definisi peta:
4. Definisi injektif:
5. Definisi surjektif:
6. 