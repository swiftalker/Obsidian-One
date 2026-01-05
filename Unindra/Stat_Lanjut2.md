### **1. Distribusi Hipergeometrik (Untuk Soal No. 1)**
_Ciri-ciri: Ada populasi ($N$), diambil sampel ($n$) **tanpa pengembalian**, dan ingin tahu peluang jumlah sukses ($K$) tertentu._
- **Variabel:**
    - $N$ = Total Populasi
    - $n$ = Jumlah Sampel yang diambil
    - $K$ = Jumlah unsur "Sukses" di dalam populasi        
    - $p$ = Rasio sukses ($K/N$)

- Rumus Nilai Harapan (Mean):
    $$E(X) = \mu = n \cdot \frac{K}{N}$$
- Rumus Varians (Ragam):
$$Var(X) = \sigma^2 = n \cdot \frac{K}{N} \cdot \left( 1 - \frac{K}{N} \right) \cdot \left( \frac{N-n}{N-1} \right)$$
    > **Catatan:** Bagian $\frac{N-n}{N-1}$ disebut _Faktor Koreksi Populasi Terbatas_. Jangan lupa dikalikan!
---
### **2. Distribusi Normal Standar / Z-Score (Untuk Soal No. 2)**
_Ciri-ciri: Diketahui rata-rata ($\mu$) dan standar deviasi ($\sigma$), ditanya peluang satu data ($X$)._
- Rumus Transformasi Z:
$$Z = \frac{X - \mu}{\sigma}$$
- **Cara Baca Tabel & Hitung Peluang:**
    - **Kurang dari ($<$):** Lihat nilai tabel langsung.
    - **Lebih dari ($>$):** $1 - \text{Nilai Tabel}$.
    - **Antara ($a < X < b$):** $\text{Nilai Tabel } Z_b - \text{Nilai Tabel } Z_a$.
---
### **3. Distribusi Sampling Rata-rata (Untuk Soal No. 3)**
_Ciri-ciri: Sama seperti normal, TAPI ada sampel sebanyak $n$ ($n > 1$) dan yang ditanya peluang **rata-ratanya** ($\bar{x}$)._
- **Parameter Baru:**
    - Rata-rata sampel: $\mu_{\bar{x}} = \mu$ (Sama dengan populasi)
    - Standar Error (Simpangan baku sampel): $\sigma_{\bar{x}} = \frac{\sigma}{\sqrt{n}}$
- Rumus Z untuk Rata-rata:
    $$Z = \frac{\bar{x} - \mu}{\frac{\sigma}{\sqrt{n}}}$$
    > **PENTING:** Bedakan rumus No. 2 dan No. 3. Jika ada "$n$ sampel", penyebutnya wajib dibagi $\sqrt{n}$.

---
### **4. Selang Kepercayaan / Confidence Interval (Untuk Soal No. 4)**
_Ciri-ciri: Estimasi rata-rata populasi dengan tingkat kepercayaan (misal 95%)._
- Rumus Interval:
    $$\bar{x} \pm Z_{\alpha/2} \cdot \left( \frac{s}{\sqrt{n}} \right)$$
- **Komponen:**
    - $\bar{x}$ = Rata-rata sampel
    - $s$ = Standar deviasi sampel
    - $n$ = Jumlah sampel
    - $Z_{\alpha/2}$ = Nilai Z kritis.
- **Hafalan Nilai Z Kritis (Sering Keluar):**
    - Kepercayaan **90%** $\rightarrow Z = 1,645$
    - Kepercayaan **95%** $\rightarrow Z = 1,96$ (Paling sering muncul, dipakai di soal ini)
    - Kepercayaan **99%** $\rightarrow Z = 2,575$
- Cara Menulis Kesimpulan:
    "Kita [95%] yakin bahwa rata-rata sesungguhnya berada di antara [Batas Bawah] dan [Batas Atas]."