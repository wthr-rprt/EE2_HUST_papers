# 1. Khái niệm và tính chất
- Cho [[Hàm số]] ${}f(x){}$ xác định trên khoảng ${}(a,b){}$. Hàm ${}F(x){}$ khả vi (có [[Đạo hàm và Vi phân]]) trên khoảng ${}(a,b){}$ được gọi là một nguyên hàm của ${}f(x){}$ nếu ${}F'(x)=f(x){}$
	- Mọi hàm số dạng ${}F(x) + C{}$ cũng là nguyên hàm của ${}f(x){}$ nếu ${}C\in \mathbb R{}$
	- Mỗi nguyên hàm của ${}f(x){}$ đều có dạng ${}F(x)+C{}$, với ${}C\in\mathbb R{}$
- Họ tất cả các nguyên hàm của ${}f(x){}$ gọi là tích phân bất định của ${}f(x){}$, ký hiệu là:
  $$
  \int f(x)dx=F(x)+C
  $$
- Tính chất
	1. Mọi hàm ${}f(x){}$ liên tục trên khoảng ${}(a,b){}$ đều có nguyên hàm trên khoảng này
	2. ${}\int F(x)dx=F(x)+C{}$
	3. ${}\left( \int f(x)dx \right)'=f(x){}$
	4. ${}\int (\alpha f(x)+\beta g(x))dx= \alpha \int f(x)dx+\beta\int g(x)dx{}$
# 2. Phương pháp tính tích phân bất định
## 2.0. Bảng nguyên hàm cơ bản

| ${}f(x){}$                       | ${}F(x){}$                                                                 |
| -------------------------------- | -------------------------------------------------------------------------- |
| ${}0{}$                          | ${}C{}$                                                                    |
| ${}(x+a)^\alpha{}$               | ${}\frac{(x+a)^{\alpha+1}}{\alpha+1}, a\neq-1{}$                           |
| ${}\frac{1}{x+a}{}$              | ${}\ln\mid x+a\mid{}$                                                      |
| ${}\sin(ax+b){}$                 | ${}-\frac{1}{a}\cos(ax+b),a\neq 0{}$                                       |
| ${}\cos (ax+b){}$                | ${}\frac{1}{a}\sin(ax+b), a\neq 0{}$                                       |
| ${}\frac{1}{\cos^2x}{}$          | ${}\tan x{}$                                                               |
| ${}\frac{1}{\sin^2x}{}$          | ${}-\cot x{}$                                                              |
| ${}\frac{1}{\sin x}{}$           | ${}\ln\mid \tan \frac{x}{2}\mid{}$                                         |
| ${}\frac{1}{\cos x}{}$           | ${}\ln\mid \tan\left( \frac{x}{2}+\frac{\pi}{4} \right)\mid{}$             |
| ${}\frac{1}{\sqrt{ x^2+b }}{}$   | ${}\ln\mid x+\sqrt{ x^2+b }\mid{}$                                         |
| ${}\sqrt{ x^2+b }{}$             | ${}\frac{x\sqrt{ x^2+b }}{2}+\frac{b(\ln\mid x+\sqrt{ x^2+b }\mid)}{2}{}$  |
| ${}\frac{1}{\sqrt{ a^2-x^2 }}{}$ | ${}\arcsin \frac{x}{a},a>0{}$                                              |
| ${}\sqrt{ a^2-x^2 }{}$           | ${}\frac{x\sqrt{ a^2-x^2 }}{2}+\frac{a^2\arcsin \frac{x}{a}}{2},a\neq 0{}$ |
| ${}\frac{1}{x^2+a^2}{}$          | ${}\frac{1}{a}\arctan \frac{x}{a}{}$                                       |
| ${}e^{ax+b}{}$                   | ${}\frac{1}{a}e^{ax+b}{}$                                                  |

## 2.1. Phương pháp đổi biến
$$
\int f(x)dx=\int g(u(x)).u'(x)dx=\int g(x)du
$$
## 2.2. Phương pháp tích phân từng phần
$$
\int f(x)dx=\int u(x)v'(x)dx=\int u(x)dv=u(x)v(x)-\int v(x)du
$$
## 2.3. Tích phân của hàm phân thức hữu tỷ
- Phân tích phân thức thành tổng của các phân thức hữu tỷ tối giản (tử là 1, mẫu max bậc 2)
## 2.4. Tích phân hàm lượng giác
- Nếu hàm dưới dấu tích phân có tính chẵn lẻ với ${}\sin{}$ hoặc ${}\cos{}$
	- Đặt ${}t=\cos x{}$ nếu lẻ với ${}\sin{}$
	- Ngược lại với ${}\cos{}$
	- Nếu chẵn với cả 2 thì đặt ${}t=\tan x{}$
- Nếu hàm dưới dấu tích phân là hàm hữu tỉ với ${}\sin{}$ hoặc ${}\cos{}$
	- Đặt ${}t=\tan \frac{x}{2}{}$, qua đó ${}\sin x=\frac{2t}{1+t^2},\cos x=\frac{1-t^2}{1+t^2},dx=\frac{2dt}{1+t^2}{}$
## 2.5. Tích phân hàm vô tỷ
- Đặt ${}t{}$ bằng căn bậc thấp nhất và đưa ngược về dạng hữu tỉ rồi làm tiếp
