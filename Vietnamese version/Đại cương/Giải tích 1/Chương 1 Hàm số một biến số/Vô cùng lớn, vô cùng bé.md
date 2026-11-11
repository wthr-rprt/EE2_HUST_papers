## 1. Vô cùng bé
- Hàm số $f(x)$ được gọi là VCB nếu 
  $$
  \lim_{ x \to a }f(x)=0 
  $$
- Liên hệ giữa giới hạn hữu hạn và VCB
$$
\lim_{x \to a }f(x)= \ell \iff f(x)=\ell+a(x) 
$$
trong đó $a(x)$ là một VCB trong quá trình $x\to a$.
#### ***Tính chất của VCB***
- Tổng/hiệu 2 VCB là VCB
- Tích các VCB là VCB
- Tích của một VCB và một đại lượng bị chặn là một VCB
- ***Lưu ý: Thương của 2 VCB là dạng vô định $\frac{0}{0}$***
#### ***So sánh các VCB***
- Nếu $\lim_{x \to a}\frac{\alpha(x)}{\beta(x)}=A\neq 0$ thì $\alpha(x)$ và $\beta (x)$ là 2 VCB cùng bậc
- Nếu $\lim_{x \to a }\frac{\alpha(x)}{\beta(x)}=1$ thì $\alpha(x)$ và $\beta(x)$ là 2 VCB tương đương và viết 
  $$
  \alpha(x) \sim \beta(x)
  $$
- Một số VCB tương đương hay dùng:
	- $x \sim \sin x \sim \tan x \sim \arcsin x \sim \arctan x \sim e^x-1 \sim \frac{a^x-1}{\ln a} \sim \ln(1+x)$
	- $(1+x)^a-1 \sim ax$. Đặc biệt $\sqrt[m]{1+ax}-1 \sim \frac{ax}{m}$
	- $1-\cos x \sim \frac{x^2}{2}$
- VCB bậc cao
	- Nếu $\lim_{x\to a}\frac{\alpha(x)}{\beta(x)}=0$, ta nói $\alpha(x)$ là VCB bậc cao hơn $\beta(x)$ và ký hiệu là $\alpha(x)=o(\beta(x))$
	- Hiệu hai VCB tương đương là một VCB bậc cao hơn VCB đó
	- Tích hai VCB là một VCB bậc cao hơn cả 2 VCB đó
	- Trong giới hạn có thể thay tương đương 2 VCB và ngắt bỏ VCB bậc cao nếu tồn tại VCB bậc thấp hơn trong tổng trong giới hạn
## 2. Vô cùng lớn
- Hàm số $f(x)$ được gọi là một VCL khi $x\to a$ nếu
$$
\lim_{x \to a }|f(x)|=\infty 
$$
- Nghịch đảo của một VCB và một VCL và ngược lại
#### So sánh các VCL
- VCL cùng bậc và tương đương (tương tự VCB)
- Thứ tự bậc VCL:
	- ${}\ln x\ll x^a\ll a^x\ll x!\ll x^x{}$
- VCL bậc cao
	- Nếu $\lim_{x \to a }\frac{\alpha(x)}{\beta(x)}=\infty$ thì nói $\alpha(x)$ là VCL bậc cao hơn $\beta(x)$ 
- Lược VCL bậc thấp tương tự lược VCB bậc cao