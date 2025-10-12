- Untuk soal nomor 5, jawaban yang lebih sempurna:
Bagus — kamu sudah berusaha mati-matian menjawab. Ada beberapa kekeliruan kecil di argumenmu (terutama pada bagian surjektif) — aku perbaiki, beri penjelasan formal, dan tunjukkan contoh konkret supaya jelas.

---

## Definisi fungsi yang diberikan

$$
f:\mathbb{N}\to\mathbb{N},\qquad  
f(n)=\begin{cases}  
2n, & \text{jika } n \text{ genap},[4pt]  
n, & \text{jika } n \text{ ganjil}.  
\end{cases}  
$$

(Asumsi: ($\mathbb{N}={1,2,3,\dots}$). Jika kamu pakai ($\mathbb{N}$) termasuk (0), argumen sama saja, tinggal perhatikan (0).)

---

## 1) Apakah (f) injektif?

**Klaim:** (f) _injektif_ (satu-satu).

**Bukti:** Kita tunjukkan: jika (f(a)=f(b)) maka (a=b).

- Kasus 1: (a) dan (b) keduanya ganjil.  
    Maka (f(a)=a) dan (f(b)=b). Jika (f(a)=f(b)) maka (a=b).
    
- Kasus 2: (a) dan (b) keduanya genap.  
    Tuliskan (a=2k,\ b=2\ell) dengan (k,\ell\in\mathbb{N}).  
    Maka (f(a)=2a=4k) dan (f(b)=2b=4\ell). Jika (f(a)=f(b)) maka (4k=4\ell) sehingga (k=\ell) sehingga (a=2k=2\ell=b).
    
- Kasus 3: satu ganjil dan satunya genap (misal (a) ganjil, (b) genap).  
    Maka (f(a)=a) (ganjil) dan (f(b)=2b) (genap, lebih khusus kelipatan 4). Bilangan ganjil tidak pernah sama dengan bilangan genap, jadi tidak mungkin (f(a)=f(b)).
    

Kombinasi ketiga kasus menutup semua kemungkinan. Jadi jika (f(a)=f(b)) maka (a=b). Oleh karena itu (f) injektif. ■

**Catatan:** pada jawabanmu sebelumnya kamu mencoba memberikan contoh (x=1,y=2) tetapi itu tidak membuktikan non-injektif karena (f(1)=1\neq 4=f(2)). Untuk membuktikan non-injektif perlu contoh (x\neq y) dengan (f(x)=f(y)); di fungsi ini tidak ada contoh tersebut.

---

## 2) Apakah (f) surjektif?

**Klaim:** (f) _bukan_ surjektif.

**Bukti (kontrapositif / contoh konkret):** Untuk surjektif, tiap (y\in\mathbb{N}) harus ada (n\in\mathbb{N}) dengan (f(n)=y).

Ambil (y=2). Coba cari (n) dengan (f(n)=2).

- Jika (n) ganjil, (f(n)=n). Maka (n=2) harus ganjil — tidak mungkin.
    
- Jika (n) genap, tulis (n=2k). Maka (f(n)=2n=4k). Persamaan (4k=2) tidak punya solusi integer (k).
    

Jadi tidak ada (n\in\mathbb{N}) dengan (f(n)=2). Oleh karena itu (2) tidak berada di citra (f(\mathbb{N})), sehingga (f) bukan surjektif.

**Kesalahan pada argumenmu:** kamu pilih kandidat (n=2y) saat (y) genap — tetapi jika (n=2y) maka (f(n)=2n=4y), bukan (y). Jadi argumen itu salah dan membuat kesimpulan surjektif jadi keliru.

---

## Ringkasan akhir

- (f) **injektif** — benar.
    
- (f) **tidak surjektif** — benar (contoh: (y=2) tidak punya pra-gambar).
    

---

## Visualisasi kecil (tabel (n\mapsto f(n)) untuk (n=1..10))

[  
\begin{array}{c|cccccccccc}  
n & 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 10\\hline  
f(n) & 1 & 4 & 3 & 8 & 5 & 12 & 7 & 16 & 9 & 20  
\end{array}  
]  
Dari tabel kelihatan semua nilai citra adalah: ({1,3,5,7,9,\dots}) (semua ganjil) **plus** ({4,8,12,16,20,\dots}) (kelipatan 4). Tidak ada nilai `2`, `6`, `10`, ... (genap tapi bukan kelipatan 4).

---

Kalau kamu mau, aku bisa:

- Tulis bukti formal singkat dalam LaTeX, atau
    
- Tunjukkan kode Julia untuk memetakan beberapa nilai dan memeriksa injektif/surjektif pada rentang terhingga.
    
