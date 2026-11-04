## 1. Giới hạn của [[Dãy số]]
- Dãy số có giới hạn $L\in\mathbb{R}$ hay hội tụ đến $L$ được định nghĩa là $\lim u_{n}=L \iff \lim(u_{n}-L)=0$ nếu với mỗi số $\epsilon>0$ bé tùy ý cho trước tồn tại một $n_{0}$ sao cho với $n\geq n_{0}$ thì $|u_{n}|<\epsilon$
- Giới hạn là duy nhất
- Giới hạn của một dãy hữu hạn thì dãy đó bị chặn
#### Tiêu chuẩn hội tụ của dãy
1. Tiêu chuẩn kẹp
	- $u_{n}\leq v_{n}\leq w_{n}, \forall n\geq 1$
	- $\lim u_{n}=\lim v_{w}=L$
	$\implies \lim v_{n}=L$
2. Tiêu chuẩn đơn điệu bị chặn
	- Dãy số tăng bị chặn trên hoặc giảm bị chặn dưới thì có giới hạn hữu hạn
3. Tiêu chuẩn Cauchy
	- Điều kiện cần và đủ để dãy số có giới hạn là: Với mọi số $\epsilon>0$ bé tùy ý cho trước, tồn tại số tự nhiên $n_{0}$ sao cho với $m, n\geq n_{0}$ thì $|u_{m}-u_{n}|<\epsilon$
## 2. Giới hạn của [[Hàm số]]

| Định nghĩa giới hạn hàm số ở lớp 11                                                                                                                                                                                                                                                                                                                                   | Định nghĩa giới hạn hàm số theo ngôn ngữ $\epsilon, \delta$                                                                                                                                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cho khoảng $(a,b)$ chứa $x_{0}$ và hàm $y=f(x)$ xác định trên $(a,b)\setminus\left\{x_{0}\right\}$. Ta nói hàm $y=f(x)$ có giới hạn $L\in\mathbb{R}\cup\left\{-\infty,+\infty\right\}$, khi $x$ dần tới $x_{0}$ nếu với mọi dãy số $(x_{n}),x_{n}\in(a,b)\setminus\left\{x_{0}\right\}$ và $x_{n}\to x_{0}$, ta có $f(x_{n})\to L$. Ký hiệu $\lim_{ x \to x_{n} }=L$. | Cho khoảng $(a,b)$ chứa $x_{0}$ và hàm $y=f(x)$ xác định trên $(a,b)\setminus\left\{x_{0}\right\}$. Khi đó $\lim_{ x \to  x_{n}}f(x)=L$ nếu mọi $\epsilon>0$ bé tùy ý cho trước, tồn tại $\delta>0$ sao cho với mọi $x$ thỏa mãn $0<\left\|x-x_{0}\right\|<\delta$ thì $\left\|f(x)-L\right\|<\epsilon$. |
- Các phép toán giới hạn
	1. $\lim_{x \to x_{0} }(f(x)+g(x))=\lim_{x \to x_{0} }f(x)+\lim_{x \to x_{0} }g(x)$
	2. $\lim_{x \to x_{0} }(f(x)-g(x))=\lim_{x \to x_{0} }f(x)-\lim_{x \to x_{0} }g(x)$
	3. $\lim_{x \to x_{0} }(f(x).g(x))=\lim_{x \to x_{0} }f(x).\lim_{x \to x_{0} }g(x)$
	4. $\lim_{x \to x_{0}}\left( \frac{f(x)}{g(x)} \right)=\frac{\lim_{x \to x_{0}}f(x)}{\lim_{x \to x_{0} }g(x)}$
	* Các dạng không thực hiện được gọi là vô định: $\frac{0}{0},\infty-\infty,0\times\infty,\frac{\infty}{\infty}$
- Giới hạn của hàm hợp
	 - Có $\lim_{x \to x_{0} }u(x)=u_{0},\lim_{ u \to u_{0} }f(u)=f(u_{0})$, suy ra:
	$$
	\lim_{ x \to x_{0} }f(u(x))=f(u_{0}) 
	$$
	đây là giới hạn của hàm hợp $f(u(x))$.
- Giới hạn tại vô cùng
	- Cho khoảng $(a,b)$ chứa $x_{0}$ và hàm $y=f(x)$ xác định trên $(a,b)\setminus\left\{x_{0}\right\}$. Khi đó $\lim_{ x \to  x_{n}}f(x)=\infty$ nếu mọi $M>0, \delta>0$ sao cho với mọi $x$ thỏa mãn $\left|x-x_{0}\right|<\delta$ thì $\left|f(x)\right|>M$. (liên hệ tới [[Vô cùng lớn, vô cùng bé]])
- Các tiêu chuẩn tồn tại giới hạn
	- Tương tự tiêu chuẩn của dãy số
- Có thể chuyển đổi từ giới hạn dãy số thành giới hạn hàm số để giải toán