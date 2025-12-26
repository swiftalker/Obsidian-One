Untuk sebarang $a \in \mathbb{R}$ tunjukkan $|a| = \sqrt{ a^2 }$
Bukti.
Jika $a \geq 0, |a| = a = \sqrt{ a^2 }$. Jika a < 0, maka $|a| = -a = \sqrt{ (-a)^2 } = \sqrt{ a^2 }$

Untuk sebarang $a,b \in \mathbb{R}$ tunjukkan $|a+b|=|a|+|b|$ jika dan hanya jika $ab \geq 0$
Bukti:
Karena $|x|^2 = x^2$ untuk setiap $x \in \mathbb{R}$ makaL
$$
|a+b|^2 = (|a|+|b|)^2 \iff (a+b)^2 = (|a| + |b|)^2
\iff a^2 + 2ab + b^2 = |a|^2 + 2|a||b|+|b|^2
\iff ab = |ab|
\iff ab \geq 0
$$

Untuk  semua $x \in \mathbb{R}$ sehingga memenuhi $2x+|x-1|<3$
Bukti.
Jika $x\geq 1$ maka $x-1\geq0$ sehingga
$2x+|x-1|<3 \iff 2x + x -1 < 3$
$\iff 3x < 4 \iff x< \frac{4}{3}$
Akibatnya, diperoleh $1\leq x< \frac{4}{3}$. Jika x < 1, maka x - 1 < 0. Selanjutnya,
$2x+|x-1|<3 \iff 2x + (-(x-1))) < 3 \iff x < 2$
sehingga diperoleh x < 1 dan x < 2 atau x < 1 . Jadi $x \in \mathbb{R}$ yang dicari adalah $1 \leq x < \frac{4}{3}$ atau x < 1, atau ekuivalen dengan $x < \frac{4}{3}$

Tentukan suatu bilangan $\delta > 0$ sehingga untuk setiap $x \in \mathbb{R}$ yang memenuhi $|x-1| < \delta$ berakibat $|x^2+x-2| < 1$
Bukti.
Untuk setiap $x \in \mathbb{R}$, $|x^2 + x - 2| = |x+2||x-1|$. Diperhatikan $x \in \mathbb{R}$ yang memenuhi $|x-1| < 1$ maka diperoleh $|x+2|=|x-1+3|\leq|x-1|+3<1+3=4$. Akibatnya, $|x^2+x-2| = |x+2||x-1|<4|x-1|$.
Diambil $\delta = min\{1,1/4\} = \frac{1}{4}$ maka $\delta > 0$ dan untuk setiap $x \in \mathbb{R}$ dengan $|x-1| < \delta$ berakibat $|x^2 + x -2| < 4|x-1|<1$

Jika E={$x:x<0$} tunjukkan E terbatas ke atas tettapi tidak terbatas ke bawah. Selanjutnya, tentukan sup E.
Bukti:
Untuk setiap $x \in E$ berlaku $x < 0$ . Jadi E terbatas ke atas.
Diambil sebarang $y \in \mathbb{R}$. Jika $y\geq0$, maka x < y untuk setiap $x \in E$. Hal ini berarti y bukan batas bawah E. Jika y < 1, maka -y < 0. Menurut sifat Archimedean, terdapat $n \in \mathbb{R}$ sehingga -y < n atau -n < y. Karena $-n < 0$, maka $-n \in E$. dengan demikian, y bukan batas bawah E. Jadi, terbukti E tidak terbatas ke bawah. Karena untuk setiap $x \in E$ berlaku x < 0, maka 0 merupakan batas atas E. Diberikan sebarang $\epsilon > 0$. Menurut sifat Archimedean, terdapat $n_{g} \in \mathbb{R}$ sehingga $\frac{1}{n_{\epsilon}} < \epsilon$. Akibatnya, $0-\epsilon < -\frac{1}{n_{\epsilon}}$  dengan $-\frac{1}{n_{\epsilon}} \in E$. Berdasarkan Akibat 2.4.9 a, 0 = sup E.

Jika $A \subset \mathbb{R}$ terbatas dan $B \subset A$ tak kosong, tunjukkan $inf A \leq inf B \leq sup B \leq sup A$.
Bukti:
Karena $A \subset \mathbb{R}$ terbatas $B \subset A$ tak kosong, maka A dan B keduanya tidak kosong dan terbatas. Akibatnya, inf A, inf B, sup A, dan sup B semuanya ada. Dimisalkan inf A = a, inf B = b, sup A=u, sup B = v.
(i) Untuk setiap $x \in B$ berlaku $b\leq x\leq v$. Jadi, $b \leq v$
(ii) Untuk sebarang $x \in B \subset A$ berlaku $a \leq x$. Ini berarti bahwa a merupakan batas bawah B. Karena b = inf B, maka $a \leq b$.
(iii) Untuk sebarang $x \in B \subset A$ berlaku $x \leq u$. Ini berarti bahwa u merupakan batas a tas B. Karena v=sup B, maka $v \leq u$.
Dari (i), (ii) dan (iii) diperoleh $a \leq b \leq v \leq u$ atau dengan kata lain $inf A \leq inf B \leq sup B \leq sup A$.

Diberikan himpunan tak kosong $A \subset \mathbb{R}$. Jika bilangan $a \in \mathbb{R}$ memiliki sifat untuk setiap $n \in \mathbb{N}$,
(i) $a-\frac{1}{n}$ bukan batas atas A, dan
(ii) $a+\frac{1}{n}$ batas atas A
tunjukkan a = sup A.
Bukti:
Diambil sebarang $\epsilon > 0$. Menurut sifat Archimedean, terdapat $N \in \mathbb{N}$a sehingga $\frac{1}{N} \in \epsilon$. Menurut (ii), untuk sebarang $x \in A$ berlaku $x \leq a + \frac{1}{N} < a + \epsilon$>. Karena hal  itu berlaku untuk sebarang $\epsilon > 0$ maka $x \leq a$. Jadi a merupakan batas atas A. Selanjutnya menurut (i), $a-\frac{1}{N}$ bukan batas atas A. Artinya, terdapat $x_{0} \in A$ sehingga $a-\epsilon < a - \frac{1}{N} < x_{0}$. Berdasarkan akibat 2.4.9a, a=supA.

Jika $A \subset \mathbb{R}$ terbatas dan B = {$-x: x\in A$} tentukan sup B dan inf B dalam hubungannya dengan sup A dan inf A
Bukti:
Karena $A \subset \mathbb{R}$ terbatas maka a=supA dan b = inf A keduanya ada. Untuk sebarang $x \in B$, berlaku $-x \in A$. Sehingga, $b\leq-x\leq a$ atau $-a \leq x \leq -b$. Ini berarti -a merupakan batas bawah B, sedangkan -b batas atas B. Akan ditunjukkan -a = inf B dan -b = sup B. Diberikan $\epsilon > 0$ sebarang. Karena a=sup A dan b =inf A, maka ada $u,v \in A$ sehingga $a - \epsilon < u$ dan $b+\epsilon > v$ atau $-a + \epsilon > -u$ dan $-b - \epsilon < -v$. Karena $-u, -v \in B$ maka menurut akibat 2.4.9, inf B = -a = -sup A dan sup B = -b = -inf A.

Diberikan $A \subset \mathbb{R}$. Jika sup A ada, tunjukkan nilainya tunggal
Bukti.
Dimisalkan sup A = a dan sup A = x. DXengan memperhatikan Definisi 2.4.4a, maka diperoleh $a \leq x$ dan $x \leq a$. Jadi a = x

Diberikan himpunan-himpunan tak kosong $A,B \subset \mathbb{R}$. Jika A dan B keduanya terbatas ke atas, tunjukkan A+B={$a+b: a \in A, b \in B$} juga terbatas ke atas dan sup(A+B) = sup A + sub B
Bukti.
Karena A dan B keduanya tak kosong dan terbatas ke atas, maka u=sup A dan v = sup B keduanya ada. Jelas A  +B tak kosong. Karena untuk sebarang $a + b \in A + B$ berlaku $a+b \leq u + v$ maka A + B terbatas ke atas oleh u+v. Diberikan sebarang $\epsilon > 0$. Karena u=sup A dan v = sup B, maka terdapat $a \in A$ dan b \in B sehingga $u - \frac{\epsilon}{2} < a$ dan $v-\frac{\epsilon}{2} < b$. Akibatnya, (u+v)-$\epsilon$ <a+, dengan a + b suatu elemen di dalam A+B. Dengan memperhatikan Akibat 2.4.9a, diperoleh u + v=sup(A+B)