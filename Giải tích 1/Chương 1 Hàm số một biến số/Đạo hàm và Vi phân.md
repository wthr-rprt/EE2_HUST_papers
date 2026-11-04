# 1. Đạo hàm
- Cho hàm số $f(x)$ xác định trên khoảng $(a,b)$ và $x_{0}\in(a,b)$. Đạo hàm $f'(x_{0})$ của [[Hàm số]] được tính là:
$$
f'(x_{0})=\lim_{x \to x_{0}}\frac{f(x)-f(x_{0})}{x-x_{0}}
$$
- Đạo hàm trái và đạo hàm phải xây dựng tương tự với $x\to x_{0}^-$ và $x\to x_{0}^+$
- Đạo hàm chỉ tồn tại khi đạo hàm trái phải là bằng nhau
- Hàm số có đạo hàm tại $x_{0}$ thì có [[Tính liên tục]] tại $x_{0}$ nhưng ngược lại không đúng
## Đạo hàm của hàm hợp và [[Hàm ngược]]
- Cho $y=f(u)$ và $u=u(x)$ có đạo hàm. Khi đó hàm số hợp $g(x)=f[u(x)]$ có đạo hàm là:
$$
g'(x)=f'[u(x)]u'(x)
$$
- Cho hàm số $f:(a,b)\to(c,d)$ với $f'(x)\neq 0, \forall x\in(a,b)$. Khi đó hàm ngược của $f$ là $g:(c,d)\to(a,b)$ thỏa mãn 
  $$
  g'(y_{0})=\frac{1}{f'(x_{0})}, \forall x_{0}\in(a,b), (y_{0}=f(x_{0}))
  $$
# 2. Vi phân
#### Định nghĩa
- Cho khoảng $( a,b )$ chứa điểm $x_{0}$ (cho lân cận $U_{\epsilon}(x_{0})$) và hàm số $f$ xác định trên $( a,b )$. Hàm số $f$ được gọi là khả vi tại điểm $x_{0}$ nếu tồn tại một số thực $A$ sao cho:
  $$
  f(x)=f(x_{0})+A(x-x_{0})+o(x-x_{0}), x\to x_{0}
  $$
- Trong đó đặt $x-x_{0}$ là $\Delta x$ và định nghĩa $df(x_{0})=A\Delta x$ là vi phân của hàm số tại điểm $x_{0}$
- Cho khoảng $( a,b )$ chứa điểm $x_{0}$ và hàm số $f$ xác định trên $( a,b )$. Khi đó, hàm số ==khả vi== tại $x_{0}$ ==khi và chỉ khi nó có đạo hàm== tại $x_{0}$ và trong định nghĩa trên số $A=f'(x_{0})$.
- Vi phân của hàm số $f$ là $df(x)=f'(x)\Delta x$. Đặc biệt khi $f=x$ thì $dx=\Delta x$, do đó vi phân của hàm số được viết là: 
  $$
  df(x)=f'(x)dx
  $$
- ==Vi phân cấp 1 là bất biến== nên khi đổi biến của hàm số thì vi phân cũng đổi biến
### Đạo hàm và vi phân cấp cao
- Cho hàm số $f$ có đạo hàm trên khoảng $( a,b )$. Nếu hàm $f'$ có đạo hàm thì $f''= ( f' ) '$ là đạo hàm cấp hai của $f$ . Tương tự ta có các đạo hàm cấp cao hơn.
- Công thức Newton - Leibniz:
  $$
  (fg)^{(n)}=\sum_{k=0}^{n}C_{n}^kf^{(k)}g^{(n-k)}=fg^{(n)}+C_{n}^1f'g^{(n-1)}+\dots+f^{(n)}g
  $$
- Nếu hàm số có đạo hàm cấp $n$ thì có vi phân cấp $n$ là:
  $$
  d^nf(x)=f^{(n)}(x)(dx)^{n}
  $$
### Bảng đạo hàm và đạo hàm cấp cao
1. Bảng đạo hàm

| Hàm                      | Đạo hàm                                         |
| ------------------------ | ----------------------------------------------- |
| $u^\alpha$               | $\alpha.u^{\alpha-1}.u'$                        |
| $\alpha^u$               | $\alpha^u.\ln\alpha.u'$                         |
| $\log_{a}\mid u\mid$     | $\frac{u'}{u.\ln a}$                            |
| $\sin u$                 | $\cos u.u'$                                     |
| $\cos u$                 | $-\sin u.u'$                                    |
| $\tan u$                 | $\frac{u'}{\cos^2u}=(1+\tan^2u).u'$             |
| $\cot u$                 | $-\frac{u'}{\sin^2u}=-(1+\cot^2u).u'$           |
| $\arcsin u$              | ${}\frac{u'}{\sqrt{ 1-u^2 }}{}$                 |
| $\arccos u$              | $-\frac{u'}{\sqrt{ 1-u^2 }}$                    |
| $\arctan u$              | ${}\frac{u'}{u^2+1}{}$                          |
| $\operatorname{arccot}u$ | ${}-\frac{u'}{u^2+1}{}$                         |
| $u^v$                    | ${}u^v.\left( v'\ln u+\frac{v.u'}{u} \right){}$ |
2. Bảng đạo hàm cấp cao

| Hàm                         | Đạo hàm cấp $n$                                        |
| --------------------------- | ------------------------------------------------------ |
| ${}(ax+b)^\alpha{}$         | ${}a^n.\alpha.(\alpha-1)\dots(\alpha-n+1)x^{\alpha-n}$ |
| $\frac{1}{ax+b}$            | $\frac{(-1)^n.n!.a^n}{(ax+b)^{n+1}}$                   |
| ${}a^{kx+m}$                | ${}k^{n}.(\ln a)^n.a^{kx+m}$                           |
| ${}\log_{c}\mid ax+b\mid{}$ | $\frac{(-1)^{n-1}.(n-1)!.a^n}{(ax+b)^n.\ln c}$         |
| ${}\sin(ax+b){}$            | ${}a^n.\sin\left( ax+b+\frac{n\pi}{2} \right){}$       |
| ${}\cos(ax+b){}$            | ${}a^n.\cos\left( ax+b+\frac{n\pi}{2} \right){}$       |

