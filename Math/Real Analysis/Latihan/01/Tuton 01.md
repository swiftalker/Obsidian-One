1. Diberikan himpunan tak kosong A, B dan C.
	a. Jika $A \cup C = B \cup C$  apakah A = B? Jika tidak, berikan contoh penyangkalnya.
	Jawab:
	Ambil sebarang $x \in A$ maka sedemikian $x\in A \cup C$, dari asumsi $A \cup C = B \cup C$ kita tahu bahwa $x \in A \cup C$ maka berakibat $x \in B \cup C$, berdasarkan definisi gabungan ini berarti juga $x \in B \cup  x\in C$. Argumen saya tidak dapat dilanjutkan, karena saya tidak bisa memastikan apakah $x\in B$. Secara sederhana ada kemungkinan bahwa $x \in A \subseteq C \text{ maupun } x \in C \supseteq A$ namun tidak ada bukti yang mendukung bagaimana bisa $x \in B$ juga. Jadi pembuktian tidak dapat dilanjutkan atau dengan kata lain $x \in (A \cap C) \land x \notin B$.

	Lebih lanjut saya mencoba mengambil contoh dari kasus kontradiksi, dimana misalkan A = {1}, B = {2}, C={1,2} maka $A \cup C = \{ 1 \} \cup \{ 1,2 \} = \{ 1,2 \} = B \cup C$, tunggu? secara logis jelas disini bahwa $A \neq B$. Dikasus tertentu mungkin saja A = B. Kalau saya melihat lebih jauh lagi, misalnya seperti ini:
	- Dari $A \cup C = B \cup C$ selalu berlaku $A - C = B - C$ dimana ini berarti $x \in A - C$ sama dengan $x \in A$ dan $x \notin C$. Jadi $x \in A \cup C = B\cup C$ karena $x \notin C$ harusnya $x\in B$  
	b. Jika $A \cap B = B \cap C$, apakah A = B? Jika tidak berikan contoh penyangkalnya.
	Jawab:
	Ambil sebarang $x \in A \cap B$ berarti $x \in A$ dan $x \in B$, kita mengetahui $x \in B$ dari klausa pertama, namun apakah ia juga dengan $x \in C$? 
	