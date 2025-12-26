Tunjukkan deret $\sum_{n=1}^{\infty} \frac{8}{n(n+2)(n+4)}$ konvergen. Tentukan limitnya
Bukti.
Untuk setiap $n \in \mathbb{N}$ ,
$\frac{8}{k(k+2)(k+4)} = \frac{1}{k} - \frac{2}{k+2} + \frac{1}{k+4}$
$=\left( \frac{1}{k} - \frac{1}{k+1}\right) + \left( \frac{1}{k+1} - \frac{1}{k+2} \right) - \left( \frac{1}{k+2} - \frac{1}{k+3} \right) - \left( \frac{1}{k+3} - \frac{1}{k+4} \right)$
Akibatnya, untuk setiap $n \in \mathbb{N}$ 
$S_{n} = \sum_{k=1}^{n} \frac{8}{k(k+2)(k+4)}$
= $\sum_{k=1}^{n} \left( \frac{1}{k} - \frac{1}{k+1} \right) + \sum_{k=1}^{n} (\frac{1}{k+1} - \frac{1}{k+2}) + \sum_{k=1}^{n} (\frac{1}{k+2} - \frac{1}{k+3}) + \sum_{k=1}^{n} (\frac{1}{k+3} - \frac{1}{k+4})$
$=\left( 1-\frac{1}{n+1} \right)+\left( \frac{1}{2}-\frac{1}{n+2} \right)-+\left( \frac{1}{3}-\frac{1}{n+3} \right)-+\left( \frac{1}{4}-\frac{1}{n+4} \right)$

Karena lim $S_{n} = 1 + \frac{1}{2} + \frac{1}{3} - \frac{1}{4} - \frac{1}{4} = \frac{11}{12}$ (ada), maka deret $\sum_{n=1}^{\infty} \frac{8}{n(n+2)(n+4)}$ konvergen dan $\sum_{n=1}^{\infty} \frac{8}{n(n+2)(n+4)} = \frac{11}{12}$

Jika $\sum_{n=1}^{\infty} x_{n}$ dan $\sum_{n=1}^{\infty}$ keduanya konvergen mutlak, tunjukkan $\sum_{n=1}^{\infty} x_{n} y_{n}$ konvergen.
Bukti:
Karena $\sum_{n=1}^{\infty} x_{n}$ konvergen mutlak, maka $x_{n}$ terbatas, artinya terdapat M > 0 sehingga $|x_{n}| \leq M$ untuk setiap $n \in \mathbb{N}$. Diberikan $\epsilon >0$. Karena $\sum_{n=1}^{\infty} y_{n}$ konvergen mutlak, maka terdapat $N \in \mathbb{N}$ sehingga untuk setiap $m,n \in \mathbb{N}$ dengan $m> n \leq N$ berlaku $\sum_{k=n+1}^{m} |y_k| < \frac{\epsilon}{M+1}$. Akibatnya, $\sum_{k=n+1}^{m} |x_{k} y_{k}| = \sum_{k=n+1}^{m} |x_{k}||y_{k}| \leq M \sum_{k=n+1}^{m} |y_{k}| < M \cdot \frac{\epsilon}{M+1} < \epsilon$
Jadi, $\sum_{n=1}^{\infty} x_{n} \cdot y_{n}$ konvergen mutlak. Akibatnya, $\sum_{n=1}^{\infty} x_{n} y_{n}$ konvergen.
