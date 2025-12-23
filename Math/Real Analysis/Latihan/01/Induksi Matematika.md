Karena $\mathbb{N}$ adalah himpunan yang memenuhi 3 poin dasar jaminan induksi matematika dan yaitu *well-ordered* pada semua bilangan asli $\mathbb{N}$ dan merupakan himpunan yang terurut baik pada $\leq$. Artinya setiap himpunan bagian tak kosong di $\mathbb{N}$ selalu memiliki elemen terkecil. Maka, didapati teorema-teorema sebagai berikut:

Teorema 1.8.1
"Setiap himpunan bagian tak kosong di dalam $\mathbb{N}$ mempunyai elemen terkecil. Berdasarkan hal ini dapat diturunkan teorema sebagai berikut."

Teorema 1.8.2 (Prinsip Dasar Induksi Matematika)
"Diberikan sebarang himpunan bagian $S \subseteq \mathbb{N}$. Jika dipenuhi sifat-sifat sebagai berikut:
(i) $1 \in S$, dan
(ii) untuk sebarang $n \in \mathbb{N}$ jika $n \in S$ berakibat $n+1 \in S$, maka $S = \mathbb{N}$"
Bukti.
Diandaikan $S \neq \mathbb{N}$ maka $\mathbb{N} - S \subset \mathbb{N}$ dan $\mathbb{N} - S \neq \emptyset$. Menurut teorema 1.8.1, $\mathbb{N} - S$ mempunyai elemen terkecil, sebut saja m. Akan ditunjukkan m > 1. Diandaikan m = 1. Karena $1 \in S$ . Hal ini kontradiksi dengan $m \in \mathbb{N} - S$. Jadi, m > 1. Selanjutnya, karena m - 1 < m dan m elemen terkecil di dalam $\mathbb{N} - S$, maka $m - 1 \notin \mathbb{N} - S \iff m - 1 \in S$. Berdasarkan hipotesis bahwa 