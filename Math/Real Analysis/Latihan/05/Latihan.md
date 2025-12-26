Diberikan $E = \left\{ \frac{1}{n}: n \in \mathbb{N}\right\} \cup \{0\}$ . Tunjukkan 
a. E tidak mempunyai titik dalam
Bukti:
Karena $E^0 \subset E$ maka cukup ditunjukkan bahwa setiap $x \in E$ bukan merupakan titik dalam. DIambil sebarang $x \in E$ dan sebarang $r > 0$. Karena $x \in E$, maka x = 0 atau $x=\frac{1}{n}$ untuk suatu $n \in \mathbb{N}$. Jika x = 0, maka $-\frac{r}{2} \in \mathbb{N}_{r} (0)$ tetapi $-\frac{r}{2} \notin E$. Ini berarti $N_{r}(0) \not\subset$ atau dengan kata lain $0 \not\in E^0$. Jika $x=\frac{1}{n}$ untuk suatu $n \in \mathbb{N}$ maka menurut Teorema 2.5.3 terdapat bilangan irasional $q \in N_{r}(x)$. Tetapi karena $q \not\in E$, maka $N_{r}(x) \not\subset E$. Jadi, $x \not\in E^0$.

b. E tertutup
Bukti. 
Diambil sebarang $x \in \bar{E}$. Diandaikan $x \not\in E$, maka ada 2 kemungkan yang terjadi yaitu x < 0 atau $x \in \left\{  x > 0: x \neq \frac{1}{n} \text{ untuk setiap } n \in \mathbb{N} \right\}$. Jika x < 0, diambil $r = -\frac{x}{2}$ maka untuk sebarang $y \in N_{r}(x)$ berlaku y < $x+r$ = x -$\frac{x}{2}$ = $\frac{x}{2} < 0$
Hal ini berakibat $N_{r} (x) \subset (-\infty,0)$ sehingga $N_{r}(x) \cap E = \emptyset$. Dengan demikian $x \not\in \bar{E}$, kontradiksi dengan $x \in \bar{E}$. Jika $x \in \left\{  x > 0 : x \neq \frac{1}{n} \text{ untuk setiap } n \in \mathbb{N} \right\}$, maka x > 1 atau $\frac{1}{n+1} < x < \frac{1}{n}$ untuk suatu $n \in \mathbb{N}$. Jika x > 1, diambil r=x-, maka untuk sebarang $y \in N_{r}(x)$ berlaku $y>x-r=x-(x-1)=1$ ini berarti $N_{r}(x) \subset (1,\infty)$ sehingga berakibat $N_{r}(x) \cap E = \emptyset$. Dengan demikian diperoleh $x \not\in \bar{E}$, kontradiksi dengan $x \in \bar{E}$. Jika $\frac{1}{n+1}$ < x < $\frac{1}{n}$ untuk suatu $n \in \mathbb{N}$, diambil r = $min${$x-\frac{1}{n+1}, \frac{1}{n} - x$} maka untuk sebarang $y \in N_{r}(x)$ berlaku
$$
x-r < y < x +r
\implies \frac{1}{n+1} - \frac{1}{2} \left( \frac{1}{n+1} - x \right) < y < \frac{1}{n}+\frac{1}{2}\left( x-\frac{1}{n} \right)
\implies \frac{1}{2}\left( \frac{1}{n+1} + x\right) < y < \frac{1}{2}\left( x+\frac{1}{n} \right)
\frac{1}{n+1} < y < \frac{1}{n}
$$
Diperoleh $N_{r}(x) \subset \left( \frac{1}{n+1}, \frac{1}{n} \right)$. Karena $\left( \frac{1}{n+1}, \frac{1}{n} \right) \cap E = \emptyset$, maka $N_{r}(x) \cap E = \emptyset$. Dengan demikian diperoleh $x \notin \bar{E}$ kontradiksi dengan $x \in E$. Jadi berdasarkan uraian diatas diperoleh $x \in E$. Dengan demikian dapat disimpulkan E tertutup.

Dengan menggunakan definisi himpunan kompak, tunjukkan bahwa apabila A dan B kompak, maka $A \cup B$ kompak.
Bukti.
Misalkan I sebarang himpunan indeks dan $\mathcal{C} = \{ G_{\alpha} : \alpha \in I\}$ sebarang selimut terbuka untuk $A \cup B$ maka $A \subset A \cup B \subset \cup_{\alpha \in I} G_{\alpha}$ dan $B \subset A \cup B \subset \cup_{\alpha \in I} G_{\alpha }$
Akibatnya, $\mathcal{C}$ merupakan selimut terbuka untuk A dan untuk B. Karena A dan B kompak, maka terdapat, $\alpha_{1}, \alpha_{2}, \dots, \alpha_{n}, \beta_{1}, \beta_{2}, \dots, \beta_{m} \in I$ sehingga 
$$
A \subset \cup_{j=1}^n G_{\alpha j} \text{ dan } 
B \subset \cup_{j=1}^n G_{\beta j} 
$$
Akibatnya, $A \cup B \subset (\cup_{j=1}^n G_{\alpha j}) \cup B \subset \cup_{j=1}^n G_{\beta j}$ . Jadi $\mathcal{C}$ memuat selimut bagian berhingga untuk $A \cup B$. Dengan demikian terbukti, $A \cup B$ kompak.