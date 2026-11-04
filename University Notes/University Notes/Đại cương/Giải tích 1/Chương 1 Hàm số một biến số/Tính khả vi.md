# 0. Định nghĩa
- Đã được nêu trong [[Đạo hàm và Vi phân]]
# 1. Các định nghĩa về hàm khả vi và ứng dụng
## 1.1. Cực trị hàm số
- Hàm số ${}f(x){}$ xác định trên ${}(a,b){}$ được gọi là:
	1. đơn điệu tăng nếu với mọi ${}x_{1},x_{2}\in (a,b),x_{1}<x_{2}{}$ thì ${}f(x_{1})\leq f(x_{2}){}$
	2. đơn điệu giảm nếu với mọi ${}x_{1},x_{2}\in (a,b),x_{1}<x_{2}{}$ thì ${}f(x_{1})\geq f(x_{2}){}$
	3. tăng ngặt nếu với mọi ${}x_{1},x_{2}\in (a,b),x_{1}<x_{2}{}$ thì ${}f(x_{1})< f(x_{2}){}$
	4. giảm ngặt nếu với mọi ${}x_{1},x_{2}\in (a,b),x_{1}<x_{2}{}$ thì ${}f(x_{1})>f(x_{2}){}$
- Cho hàm số ${}f(x){}$ xác định và có đạo hàm trong khoảng ${}(a,b){}$. Khi đó nếu ${}f'(x)\geq 0\forall x\in(a,b){}$ thì ${}f(x){}$ đơn điệu tăng trên ${}(a,b){}$ và tương tự với giảm
- Có thể khẳng định ngược lại nếu là đạo hàm cấp 2
 - Định nghĩa: Cho hàm $f(x)$ xác định trên tập $D$:
	 1. Điểm $x_{0}$ thuộc $D$ được gọi là điểm cực đại của hàm $f(x)$ nếu tồn tại khoảng $(a,b)\subset D$chứa điểm $x_{0}$ sao cho $f(x_{0})\geq f(x), \forall x\in (a,b)$. Đặc biệt nếu $f(x_{0})>f(x),\forall x\in(a,b)\setminus\left\{x_{0}\right\}$ thì ta nói $x_{0}$ là điểm cực đại chặt.
	 2. Tương tự với điểm cực tiểu và điểm cực tiểu chặt.
- Điểm cực đại/tiểu (chặt) đều gọi là cực trị (chặt).
#### Định lý Fermat
- Giả sử hàm số $f$ đạt cực trị tại $x_{0}$. Khi đó, nếu $f$ có đạo hàm tại $x_{0}$ thì $f'(x_{0})=0$.
- Định lý Fermat là điều kiện cần chứ không đủ để hàm số có đạo hàm đạt cực trị.
- Những điểm mà tại đó hàm số có đạo hàm bằng $0$ hoặc không có đạo hàm, có khả năng sẽ là điểm cực trị của hàm số. Những điểm như vậy gọi là điểm tới hạn của hàm. Do đó, một điểm là cực trị sẽ là điểm tới hạn, nhưng điều ngược lại chưa chắc.
- Quy tắc đạo hàm cấp $n$, đây là điều kiện đủ:
  $$
  f'(x_{0})=f''(x_{0})=f^{(3)}(x_{0})=\dots=f^{(n-1)}(x_{0})=0, f^{(n)}\neq 0
  $$
- Nếu $n$ lẻ thì hàm số không có cực trị, còn chẵn thì là cực tiểu nếu $f^{(n)}(x_{0})>0$ và ngược lại với cực đại.
## 1.2. Các định lý giá trị trung bình
#### Định lý Rolle
- Cho hàm số $f$ liên tục trên $[a,b]$, có đạo hàm trong $(a,b)$ và thỏa mãn $f(a)=f(b)$. Khi đó tồn tại ít nhất một điểm sao cho $c\in(a,b)$ sao cho $f'(c)=0$
	$\longrightarrow$ Với 2 điểm có cùng độ cao, giữa chúng phải bằng phẳng hoặc có đỉnh (đổi chiều)
#### Định lý Lagrange
- Cho hàm số $f$ liên tục trên $[a,b]$, có đạo hàm trong $(a,b)$. Khi đó tồn tại ít nhất một điểm $c\in(a,b)$ sao cho: 
  $$
  \frac{f(b)-f(a)}{b-a}=f'(c)
  $$
	$\longrightarrow$ Luôn có một điểm giữa $(a,b)$ sao cho hệ số góc của nó song song với đoạn thẳng tạo từ hai đầu mút
- Ý nghĩa [[Cơ học]]: Luôn có một thời điểm mà vận tốc tức thời bằng vận tốc trung bình
- Ý nghĩa toán học: Chứng minh liên hệ của đạo hàm tới đồng biến, nghịch biến và chứng minh đẳng thức
#### Định lý Cauchy
- Cho $f$ và $g$ là hai hàm số liên tục trên đoạn $[a,b]$, có đạo hàm trong $(a,b)$, $g'(x)\neq 0,\forall x\in(a,b)$. Khi đó, tồn tại ít nhất một số $c\in(a,b)$ sao cho: 
  $$
  \frac{f(b)-f(a)}{g(b)-g(a)}=\frac{f'(c)}{g'(c)}
  $$
#### Liên hệ
- Định lý Rolle là trường hợp đặc biệt của định lý Lagrange khi $f(a)=f(b)$ và định lý Lagrange là trường hợp đặc biệt của định lý Cauchy
# 2. Quy tắc L'Hôpital
- Xét giới hạn $I=\lim_{x \to x_{0}}\frac{f(x)}{g(x)}$ ở dạng vô định $\frac{0}{0}$ hoặc $\frac{\infty}{\infty}$. Giả sử hai hàm số $f$ và $g$ có đạo hàm, $g'(x)\neq 0,\forall x\in(a,b)\setminus\left\{x_{0}\right\},x_{0}\in(a,b)$. Khi đó, nếu tồn tại $\lim_{x \to x_{0}}\frac{f'(x)}{g'(x)}=L$ thì:
  $$
  \lim_{x \to x_{0} }\frac{f(x)}{g(x)}=\lim_{x \to x_{0}}\frac{f'(x)}{g'(x)}  
  $$
- Quy tắc L'Hôpital vẫn đúng với giới hạn một phía, giới hạn tại vô cùng và giới hạn bằng vô cùng
# 3. Khai triển Taylor, khai triển Maclaurin
- Cho hàm số $f$ có đạo hàm cấp $n+1$ trong khoảng $(a,b),x_{0}\in(a,b), x_{0}\in (a,b)$. Khi đó, $\forall x\in(a,b),\exists c\in(x,x_{0})$:
  $$
  f(x)=f(x_{0})+\frac{f'(x_{0})}{1!}(x-x_{0})+\dots+\frac{f^{(n)}(x_{0})}{n!}(x-x_{0})^n+\frac{f^{(n+1)}(c)}{(n+1)!}(x-x_{0})^{n+1}
  $$
  - Đây là khai triển Taylor của hàm số $f(x)$ tại $x=x_{0}$. Nếu $x_{0}=0$ thì còn gọi là khai triển Maclaurin của $f(x)$ 
  - Bảng khai triển Maclaurin sơ cấp:

| Hàm số              | Khai triển Maclaurin                                                                                                    |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| ${}e^x{}$           | ${}1+x+\frac{x^2}{2!}+\dots+\frac{x^n}{n!}+o(x^n){}$                                                                    |
| ${}\sin x{}$        | ${}x-\frac{x^3}{3!}+\frac{x^5}{5!}+\dots+\frac{(-1)^{n+1}x^{2n-1}}{(2n-1)!}+o(x^{2n}){}$                                |
| ${}\cos x{}$        | ${}1-\frac{x^2}{2!}+\frac{x^4}{4!}+\dots+\frac{(-1)^nx^{2n}}{(2n)!}+o(x^{2n+1}){}$                                      |
| ${}\frac{1}{1+x}{}$ | ${}1-x+x^2+\dots+(-1)^nx^n+o(x^n){}$                                                                                    |
| ${}\ln(1+x){}$      | ${}x-\frac{x^2}{2}+\frac{x^3}{3}+\dots+\frac{(-1)^{n+1}x^n}{n}+o(x^n){}$                                                |
| ${}(1+x)^\alpha{}$  | ${}1+\alpha x+\frac{\alpha(\alpha -1)x^2}{2!}+\dots+\frac{\alpha(\alpha-1)(\alpha-2)\dots(\alpha-n+1)x^n}{n!}+o(x^n){}$ |

