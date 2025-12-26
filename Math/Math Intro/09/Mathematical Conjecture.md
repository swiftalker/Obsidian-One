---
aliases: []
---
Question:
Andaikan soal serumit (n+1)^n < 3n^n muncul dalam ujian misalnya, bagaimana saya memastikan bahwa saya harus menyederhanakan soal ini sebelum saya memulai lebih lanjut? apa asumsi saya untuk memulai dengan pertama-tama saya sederhanakan soal terlebih dahulu?

Answer:
Pertanyaan brilian. Ini adalah perbedaan antara "menghafal jawaban" dan "memiliki naluri matematikawan".

Dalam ujian Analisis Real (MATA4217), waktu Anda terbatas. Anda tidak ingin menghabiskan 15 menit mencoba Induksi Biasa hanya untuk macet di tengah jalan.

Berikut adalah **Algoritma Keputusan (Decision Making)** untuk mendeteksi kapan Anda wajib menyederhanakan soal sebelum mulai membuktikan.

---

### **Algoritma Deteksi: "Sederhanakan Dulu atau Langsung Hajar?"**

Gunakan 3 indikator ini saat melihat soal pertidaksamaan. Jika salah satu menyala, **STOP**. Jangan langsung tulis "Asumsi $n=k$". Lakukan _Preprocessing_ (Penyederhanaan) dulu.

#### **Indikator 1: Variabel Ganda (Basis & Pangkat)**

- **Gejala:** Huruf $n$ muncul di bawah (basis) **DAN** di atas (pangkat) secara bersamaan.
    
    - Contoh: $n^n$, $(n+1)^n$, $n!$, $n^{\sqrt{n}}$.
        
- **Diagnosa:** Induksi biasa akan gagal karena saat $n \to k+1$, bentuknya berubah drastis secara non-linear. Anda tidak akan menemukan faktor sekutu dengan mudah.
    
- Tindakan: KUMPULKAN $n$ NYA.
    
    Jangan biarkan $n$ tersebar di ruas kiri dan kanan.
    
    - _Kasus Soal Anda:_ $(n+1)^n < 3n^n$.
        
    - Lihat? Ada $n$ pangkat $n$ di kiri, dan $n$ pangkat $n$ di kanan.
        
    - Penyederhanaan: Bagi kedua ruas dengan $n^n$ agar semua variabel $n$ berkumpul di satu sisi.
        
        $$\frac{(n+1)^n}{n^n} < 3 \implies \left(\frac{n+1}{n}\right)^n < 3$$
        

#### **Indikator 2: Pertarungan Melawan Konstanta**

- **Gejala:** Ruas kanan (atau kiri) hanya berupa angka konstanta (seperti $3, e, 2, \pi$).
    
- **Diagnosa:** Matematika jauh lebih mudah jika kita membandingkan **Fungsi vs Konstanta** daripada **Fungsi vs Fungsi**.
    
- **Tindakan:** Ubah soal $f(n) < c \cdot g(n)$ menjadi $\frac{f(n)}{g(n)} < c$.
    
    - Kenapa? Karena membuktikan suatu rasio itu terbatas (bounded) adalah topik standar Analisis Real (Barisan Terbatas).
        

#### **Indikator 3: Bentuk "Ciri Khas" Analisis Real**

- **Gejala:** Muncul bentuk $(n+1)$ dan $n$ dalam orde yang sama.
    
- **Diagnosa:** Dalam Analisis Real, bentuk $\frac{n+1}{n}$ adalah "kode rahasia" untuk $1 + \frac{1}{n}$.
    
- **Tindakan:** Segera ubah menjadi bentuk $(1 + x)$. Ini memancing penggunaan **Bernoulli** atau **Binomial**.
    

---

### **Simulasi Ujian: Langkah demi Langkah**

Bayangkan Anda duduk di ujian, membuka lembar soal, dan melihat:

> **Soal:** Buktikan $(n+1)^n < 3n^n$.

**Langkah 1: Scan Visual (5 Detik)**

- "Waduh, ada pangkat $n$. Basisnya juga ada $n$." (Indikator 1 Menyala 🚨).
    
- "Di kanan ada $n^n$ juga."
    
- **Keputusan:** Jangan pakai Induksi Biasa dulu. Sederhanakan!
    

**Langkah 2: Operasi Penyelamatan (Preprocessing)**

- "Saya mau matikan $n^n$ di kanan biar sisa angka 3 doang (Konstanta)."
    
- Bagi kedua ruas dengan $n^n$:
    
    $$\frac{(n+1)^n}{n^n} < 3$$
    
- Gabungkan pangkatnya (Sifat Eksponen $\frac{a^n}{b^n} = (\frac{a}{b})^n$):
    
    $$\left( \frac{n+1}{n} \right)^n < 3$$
    
- Pecah pecahannya:
    
    $$\left( 1 + \frac{1}{n} \right)^n < 3$$
    

**Langkah 3: Evaluasi Ulang**

- Sekarang soalnya berubah wajah menjadi: "Buktikan $(1 + \frac{1}{n})^n < 3$".
    
- "Apakah ini lebih mudah?"
    
    - Indikator 1: Basisnya sekarang $(1 + 1/n)$, pangkatnya $n$. Masih ada $n$ di dua tempat, TAPI bentuk $(1+x)^n$ adalah makanan empuk untuk **Bernoulli** atau **Binomial**.
        

**Langkah 4: Eksekusi**

- Baru sekarang Anda mulai menulis: "Akan dibuktikan $\dots$ menggunakan Binomial Newton/Bernoulli".
    

---

### **Ringkasan Asumsi Strategis**

Saat menghadapi soal pertidaksamaan di MATA4217, pegang asumsi ini:

1. **"Hukum Malas Bergerak":** Jika variabel $n$ ada di Kiri dan Kanan, itu merepotkan. Pindahkan semua ke Kiri biar Kanan jadi angka diam (Konstanta).
    
2. **"Deteksi Logaritma/Eksponen":** Jika pangkatnya variabel ($n$), cara menurunkannya adalah dengan membagi sesama pangkat $n$, atau di-Logaritma-kan (walaupun jarang dipakai di induksi dasar).
    
3. **"Bentuk 1+x":** Selalu curiga bahwa $\frac{n+1}{n}$ itu sebenarnya ingin menjadi $1 + \frac{1}{n}$.
    

Apakah pola pikir "Deteksi Dini" ini bisa Anda pahami? Jadi jangan langsung "serang" dengan $k+1$, tapi "rapikan medan perang" dulu.


