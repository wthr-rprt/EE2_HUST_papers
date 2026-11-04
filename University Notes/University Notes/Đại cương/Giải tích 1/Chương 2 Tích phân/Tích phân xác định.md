# 1. Định nghĩa
- Cho hàm ${}f(x){}$ xác định trên ${}[a,b]\subset\mathbb R{}$, chia ${}[a,b]{}$ thành ${}n{}$ đoạn bởi các điểm chia ${}x_{0}=a<x_{1}<x_{2}<\dots<x_{n}=b{}$, trên mỗi đoạn chia chọn đại diện ${}\xi{}$ và dựng hình chữ nhật chiều cao ${}f(\xi){}$, khi đó diện tích tổng diện tích ${}\sum_{i=1}^{n}f(\xi)\Delta_{i}{}$ xấp xỉ diện tích của hình giới hạn bởi đồ thị ${}y=f(x), x=a, x=b{}$ với ${}\Delta_{i}=x_{i}-x_{i-1}{}$. Giá trị ${}\sum_{i=1}^nf(\xi)\Delta_{i}{}$ được gọi là tổng tích phân của hàm ${}f{}$ trên ${}[a,b]{}$
- Nếu giới hạn ${}\lim_{\Delta \to 0}\sum_{i=1}^nf(\xi)\Delta_{i}{}$ tồn tại và không phụ thuộc cách đặt ${}a,b,\xi{}$ thì ta nói ${}f(x){}$ khả tích trên ${}[a,b]{}$. Giá trị của nó gọi là tích phân xác định của hàm ${}f(x){}$ trên ${}[a,b]{}$ được ký hiệu là ${}\int^a_{b}f(x)dx{}$.
# 2. Tiêu chuẩn khả tích, tính chất tích phân xác định
## 2.1. Tiêu chuẩn khả tích
- Hàm số ${}f(x){}$ xác định trên đoạn ${}[a,b]{}$ khả tích khi thỏa mãn 1 trong 2 điều kiện sau:
	1. Hàm ${}f(x){}$ bị chặn và có hữu hạn điểm gián đoạn trên ${}[a,b]{}$
	2. Hàm ${}f(x){}$ đơn điệu và bị chặn trên ${}[a,b]{}$
## 2.2. Tính chất của tích phân xác định
- Cho hai hàm ${}f(x),g(x){}$ khả tích trên ${}[a,b]{}$:
	1. Với mọi ${}\alpha,\beta\in\mathbb R{}$:
	   $$
	   \int^b_a(\alpha f(x)+\beta g(x))dx=\alpha\int^b_af(x)dx+\beta\int^b_ag(x)dx
	   $$
	2. Với mọi ${}c\in[a,b]{}$:
	      $$
	\int^b_{a}f(x)dx=\int^c_{a}f(x)dx+\int^b_{c}f(x)dx
	      $$
	      Quy ước:
	      $$
		-\int^b_af(x)dx=\int^a_bf(x)dx
		  $$
	3. Nếu $f(x)\geq g(x),\forall a,b\in[a,b]$ thì $$\int^b_{a}f(x)dx\geq\int^b_{a}g(x)dx$$
	4. Hàm ${}|f(x)|{}$ cũng khả tích trên đoạn ${}[a,b]{}$ thì 
	$$
|\int^b_{a}f(x)dx|\leq\int^b_{a}|f(x)|dx
$$
	5. Nếu ${}f(x){}$ chẵn và khả tích trên ${}[-a,a]{}$ thì 
	$$
	\int^a_{-a}f(x)dx=2\int^a_{0}f(x)dx
	$$
	6. Nếu ${}f(x){}$ là hàm lẻ và khả tích trên ${}[-a,a]{}$ thì 
	$$
	\int^a_{-a}f(x)dx=0
	$$
	7. Nếu ${}f(x){}$ tuần hoàn với chu kỳ ${}T{}$ và khả tích trên mọi đoạn thuộc ${}\mathbb R{}$ thì 
	$$
	\int^{a+T}_{a}f(x)dx=\int^T_{0}f(x)dx,\forall a\in\mathbb R
	$$
	8. Định lý trung bình tích phân thứ nhất, nếu ${}m\leq f(x)\leq M,\forall x\in[a,b]{}$ thì:
	$$
	m(b-a)\leq\int^b_{a}f(x)dx\leq M(b-a)
	$$
		Đặc biệt, nếu ${}f(x){}$ liên tục trên ${}[a,b]{}$, tồn tại ${}c\in[a,b]{}$ sao cho
	$$
	\int^b_{a}f(x)dx=f(c)(b-a)
	$$
	9. Định lý trung bình tích phân thứ hai, giả sử:
		- ${}m\leq f(x)\leq M,\forall x\in[a,b]{}$
		- ${}g(x){}$ không đổi dấu trên ${}[a,b]{}$
	- Khi đó ta có:
	$$
	\int^b_{a}f(x)g(x)dx=\mu\int^b_{a}g(x)dx,m\leq \mu\leq M
	$$
	- Đặc biệt, nếu ${}f(x){}$ liên tục trên ${}[a,b]{}$ thì tồn tại ${}c\in[a,b]{}$ sao cho
	$$
	\int^b_{a}f(x)g(x)dx=f(c)\int^b_{a}g(x)dx
	$$
# 3. Công thức đạo hàm theo cận, công thức Newton-Leibniz
- Cho hàm ${}f(x){}$ khả tích trên ${}[a,b]{}$. Với mọi ${}x\in[a,b]{}$ đặt 
$$
F(x):=\int^x_{a}f(t)dt
$$
Khi đó:
1. Nếu ${}f(x){}$ khả tích trên đoạn ${}[a,b]{}$ thì ${}F(x){}$ liên tục trên đoạn đó
2. Nếu ${}f(x){}$ liên tục trên đoạn ${}[a,b]{}$ thì ${}F(x){}$ chính là một nguyên hàm của hàm ${}f(x){}$
$$
\left( \int^x_{a} f(t)dt \right)'=f(x)
$$
Trong trường hợp cả 2 cận đều phụ thuộc vào biến ${}x{}$ thì công thức trên có thể biến đổi như sau:
$$
\iff \left( \int^{\beta(x)}_{\alpha(x)}f(t)dt \right)'=f(\beta(x))\beta(x)'-f(\alpha(x))\alpha(x)'
$$
Đồng thời ta có công thức Newton-Leibniz: 
$$
\int^b_{a}f(t)dt=F(b)-F(a)
$$
# 4. Phương pháp tính
(xem thêm ở [[Tích phân bất định]])