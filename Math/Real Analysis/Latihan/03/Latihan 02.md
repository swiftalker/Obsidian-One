Selidiki apakah barisan $(x_{n})$ dengan $x_{n} = \frac{1}{\sqrt{ n }}, n \in \mathbb{N}$ konvergen atau tidak
Bukti:
Untuk setiap $n \in \mathbb{N}$ berlaku $x_{n} = \frac{1}{\sqrt{ n }} > \frac{1}{\sqrt{ n+1 }} = x_{n+1}$ dan $x_{n} = \frac{1}{\sqrt{ n }} > 0$. Jadi $(x_{n})$ turun monotn dan terbatas ke bawah. Menurut Teorema 3.3.2 barisan $x_{n}$ konvergen.

Diberikan barisan $x_{n}$ dengan $x_{1} = 2$ dan $x_{n+1} = x_{n} + \frac{1}{x_{n}}, n \in \mathbb{N}$. Selidiki apakah $(x_{n})$ konvergen atau tidak.
Bukti:
Karena $x_{n} >0$ untuk setiap $n \in \mathbb{N}$ karena $x_{1} = 2$ dan $1 \in \mathbb{N}$. Maka $x_{n+1} > x_{n}$ untuk setiap $x \in \mathbb{N}$ . Jadi, $x_{n}$ naik monoton. Akan ditunjukkan $x_{n+1} > n$ untuk setiap $n \in \mathbb{N}$ . Perhatikan bahwa $x_{2} = 2+\frac{1}{2} > 1$. Diasumsikan $x_{n+1} > n$, maka $x_{n+2} = x_{n+1} + \frac{1}{x_{n+1}} = \frac{x_{n+1}^2}{x_{n+1}} > n^2 + 1 > n+1$. Terbukti untuk $x_{n+1}$, n untuk setiap $n \in \mathbb{N}$. Hal ini berakibat $(x_{n})$ tidak terbatas ke atas. Jadi, $(x_{n})$ tidak konvergen.

Jika $x_{n} = \frac{n}{2n+1}, n \in \mathbb{N}$ tunjukkan $(x_{n})$ merupakan barisan Cauchy, langsung menggunakan definisi. 
Bukti:
Untuk setiap $n,m \in \mathbb{N}$ diasumsikan n < m, berlaku $|x_{n} - x_{m}|=| \frac{n}{2n+1} - \frac{m}{2m+1}| = = \frac{m-n}{(2n+1)(2m+1)} < \frac{m}{nm} = \frac{1}{n}$
Untuk $\epsilon > 0$, dipilih bilangan asli N sehingga $\frac{1}{N} < \epsilon$ (hal ini dapat dilakukan berdasarkan sifat Archimedean). Untuk m > n $\geq N$ berlaku $|x_{n} - x_{m}| < \frac{1}{n} \leq \frac{1}{N} < \epsilon$
Terbukti $x_{n}$ merupakan barisan Cauchy.