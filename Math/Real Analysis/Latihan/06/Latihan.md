Tunjukkan $\lim_{ x \to -1} (2x+3) = 1$
Bukti.
Untuk sebarang $x \in \mathbb{R}$ berlaku $|(2x+3)-1| = 2|x-(-1)|$
Diberikan bilangan $\epsilon > 0$ sebarang. Dipilih $\delta = \frac{\epsilon}{3}$ maka $\delta > 0$. Selanjutnya untuk setiap $x \in \mathbb{R}$ dengan $0<|x-(-1)| < \delta$ berlaku $|(2x+3) - 1| = 2|x-(-1)| < 2 \delta = 2 \cdot \frac{\epsilon}{3} < \epsilon$
Dengan demikian terbukti $\lim_{ x \to -1 } (2x+3)=1$

Tunjukkan $\lim_{ x \to 0} \frac{x^2}{x} =0$
Bukti.
Untuk $x \neq 0$, $| \frac{x^2}{|x|}| = \frac{|x^2|}{|x|} = |x|$. Untuk sebarang $\epsilon > 0$, dipilih $\delta = \epsilon$ maka $\delta > \epsilon$. Selanjutnya untuk seabrang $x \geq 0$ dengan $0 < |x| < \delta$ berlaku $| \frac{x^2}{|x|} - 0| = |x| < \delta = \epsilon$

Tunjukkan $\lim_{ x \to 0} \frac{|x|}{x}$ tidak ada.
Bukti.
Diambil sebarang $L \in \mathbb{R}$ maka L=1 atau $L \neq 1$.
Jika L = 1, diambil $\epsilon = \frac{1}{2}$. Selanjutnya, untuk sebarang $\delta > 0$, diambil $x=-\frac{\delta}{2}$ maka $0 < |x| < \delta$  tetapi
$| \frac{|x|}{x} - L | = | \frac{\delta / 2}{\delta/2} - 1| = |-1 -1| > \epsilon$
Jika $L\neq_{1}$ diambil $\epsilon = \frac{|L-1|}{2}$. Selanjutnya, untuk sebarang $\delta > 0$ diambil $x=\frac{\delta}{2}$ maka 0 < |x| $< \delta$ tetapi 
$| \frac{|x|}{x} - L | = | \frac{\delta / 2}{\delta/2} - 1| = |L -1| > \epsilon$

Tunjukkan $\lim_{ x \to 0} \frac{1}{x}$ tidak ada.
Bukti.
Diambil barisan $(x_{n})$ dengan $x_{n} = \frac{1}{n}$ untuk setiap $n \in \mathbb{N}$ maka $x_{n}$ konvergen ke 0.  Tetapi karena $\frac{1}{x_{n}} = (1,2,3,\dots,\mathbf{n}..$ tidak terbatas, maka $\frac{1}{x_{n}}$ tidak konvergen. Berdasarkan Teorema 6.26, $\lim_{x \to 0} \frac{1}{n}$ tidak ada.


