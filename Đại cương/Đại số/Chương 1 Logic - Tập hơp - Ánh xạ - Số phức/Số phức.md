- Là một trường trong [[Cấu trúc đại số]]
## Trường số phức
#### 1. Định nghĩa & Cấu trúc 
- Tập số phức $\mathbb{C}$ là một trường số mở rộng từ $\mathbb{R}$, được xây dựng từ tập $\mathbb{R} \times \mathbb{R}$ với hai phép toán cộng và nhân đặc biệt. 
- Đặt $i = (0, 1) \implies i^2 = -1$. 
- ==***Đa thức bậc n có n nghiệm trong trường số phức***==
#### 2. Dạng đại số (Chính tắc) 
- Dạng biểu diễn: $z = a + bi \quad (a, b \in \mathbb{R})$. 
- Số phức chia làm hai phần: Phần thực và Phần ảo
	- Phần thực: $\text{Re}(z) = a$ 
	- Phần ảo: $\text{Im}(z) = b$ 
- Số phức liên hợp: $\bar{z} = a - bi$ 
#### 3. Dạng lượng giác & Argument
- Module của số phức: $\mid z\mid=\sqrt{ a^2 +b^2}$
- Argument của số phức: $Arg(z)=\varphi=\arccos\left( \frac{a}{a^2+b^2} \right)=\arcsin\left( \frac{b}{a^2+b^2} \right)$
	- $arg(z)=Arg(z)+2k\pi$
- Dạng biểu diễn: $z = r(\cos\phi + i\sin\phi)$. Trong đó:
	- $r = |z|$. 
	- $\varphi = \arg(z)$ 
#### 4. Các phép toán với số phức, số phức liên hợp
##### 4.1. Số phức
***Cho hai số $z_{1}=a_{1}+b_{1}i$ và $z_{2}=a_{2}+b_{2}i$***
- Phép cộng/trừ:
	- $z_{1}\pm z_{2}= (a_{1}+a_{2}) + (b_{1}+b_{2})i$
- Phép nhân:
	- $z_{1}.z_{2}=(a_{1}a_{2}-b_{1}b_{2})+(a_{1}b_{2}+a_{2}b_{1})i$
	- $z_{1}.z_{2}=r(\cos(\varphi_{1}+\varphi_{2})+i\sin(\varphi_{1}+\varphi_{2}))$
- Phép chia:
	- $\frac{z_{1}}{z_{2}}=\frac{z_{1}\overline z_{2}}{z_{2}\overline z_{2}}=\frac{(a_{1}a_{2}+b_{1}b_{2})+(-a_{1}b_{2}+a_{2}b_{1})i}{a^2+b^2},z_{2}\neq 0$
	- $\frac{z_{1}}{z_{2}}=\frac{r_{1}}{r_{2}}(\cos(\varphi_{1}-\varphi_{2})+i\sin(\varphi_{1}-\varphi_{2}))$
- Phép lũy thừa: 
	- $z^n = r^n(\cos n\varphi + i\sin n\varphi)$
	- Khi $r=1$, ta có công thức Moiver: $[(\cos \varphi+i\sin \varphi)]^n=\cos (n\varphi)+i\sin(n \varphi)$
- Công thức Euler:
	- $e^{i\varphi}=\cos \varphi+i\sin \varphi \implies e^{i\pi}=-1$
- Căn bậc $n$ của số phức:
	- $z_{k}=\sqrt[n]{r}\left[ \cos\left( \frac{\varphi + k2\pi}{n} \right) +i\sin\left( \frac{\varphi +k 2\pi}{n} \right)\right], k=\overline{0,n-1}$
		- Nếu biểu diễn căn bậc $n$ của số $z$ trên mặt phẳng phức thì sẽ tạo thành một đa giác đều $n$ đỉnh nội tiếp trong đường tròn có tâm là gốc tọa độ và bán kính $s=\sqrt[n]{r}$
		- Đặt $\epsilon=\cos\left( \frac{2\pi}{n} \right)+i\sin\left( \frac{2\pi}{n} \right)$ thì $\left\{1,\epsilon,\dots,\epsilon^{n-1}\right\}$ là $n$ căn bậc $n$ của số 1. Dễ thấy $z_{k}=z_{0}.\epsilon^k,\forall k=\overline{1,n-1}$, các căn bậc $n$ của số phức $z$ là cấp số nhân công bội $\epsilon$
##### 4.2. Số phức liên hợp
***Cho số phức $z=a+bi$ và $\overline z=a-bi$***
- $z+\overline{z}=2a=2\mathrm{Re}(z)\in\mathbb{R}, z.\overline z=a^2+b^2=|z|^2=|\overline z|^2 \in\mathbb{R}$
- $z\in \mathbb{R}\iff z-\overline z =0$
- $\mathrm{Re}(z)=0\iff z+\overline z=0$
- $\overline z=r(\cos (-\varphi)+i\sin(-\varphi))$
- Liên hợp của tổng, hiệu, tích, thương là tổng, hiệu, tích, thương các liên hợp
- Liên hợp của liên hợp là số gốc
- $\frac{1}{z}=\frac{\overline z}{|z|^2}$
