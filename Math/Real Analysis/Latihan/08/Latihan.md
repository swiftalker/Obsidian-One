Tunjukkan fungsi $f: \mathbb{R} \to \mathbb{R}$ dengan rumus $f(x) = x^2$ kontinu pada $\mathbb{R}$
Bukti
Diambil sebarang $c \in \mathbb{R}$. Untuk setiap $x \in \mathbb{R}$ berlaku
$|f(x) - f(c)| = |x^2-c^2|=|x+c||x-c|$
Diperhatikan semua $x\in \mathbb{R}$ sehingga $|x-c| < 1$, maka |x+c|=$|x-c+2c| \leq |x-c|+2|c|<1+2|c|$
Akibatnya, untuk semua $x \in \mathbb{R}$ dengan |x-c| < 1 berlaku 
$|f(x) - f(c)| = |x+c||x-c| < (1+2|c|)|x-c|$
Selanjutnya diberkan $\epsilon > 0$ dan dipilih $\delta = min{1, \frac{\epsilon}{1+2|c|}}$ maka untuk $x \in \mathbb{R}$ dengan $|x-c| < \delta$ berlaku $|f(x)-f(c)| < (1+2|c|) |x-c| < \epsilon$

Dibeirkan $-\infty < a < b < \infty$. Jika fungsi $f: [a,b] \to \mathbb{R}$ kontinun pada [a,b] dan $f(x) > 0$ untuk setiap $x\in [a,b]$, tunjukkan ada bilangan k > 0 sehingga $f(x) \geq k$ untuk setiap $x\in[a,b]$
Bukti.
Karena f(x) > 0 untuk setiap $x \in [a,b]$ maka fungsi g: [a,b] $\to \mathbb{R} dengan g(x) = $\frac{1}{f(x)}, x \in [a,b]$ kontin u pada [a,b]. Beradasarkan Teorema 8.4.2, ada $u \in [a,b]$ sehingga $g(x) \leq g(u)$ untuk setiap $x \in [a,b]$. Selanjuntya diambil $k=f(u)$ maka k > 0 dan $f(x) \geq k$ untuk setiap $x \in [a,b]$