## 1. Hàm số liên tục
- Giả sử hàm số $f$ xác định trên $(a,b)$ và $x_{0} \in (a,b)$
	- Hàm số $f$ được gọi là liên tục tại điểm $x_{0}$ nếu $\lim_{x \to x_{0} }f(x)=f(x_{0})$
	- Hàm số $f$ được gọi là liên tục trên khoảng $(a,b)$ nếu nó liên tục tại mọi điểm thuộc khoảng đó
	- Nếu $f$ xác định trên đoạn $[a,b]$ thì $f$ được gọi là liên tục trên đoạn $[a,b]$ nếu nó liên tục trên $(a,b)$ và 
	  $$
	  \lim_{x \to a^+ }f(x)=f(a), \lim_{x \to b^-}f(x)=f(b)  
	  $$
	- Tương tự với nửa khoảng trái và phải
- Cho hàm số $f$ liên tục trên đoạn $[a,b]$, khi đó:
	- Tồn tại $M=max\left\{f(x)\mid x\in[a,b]\right\}$ và $m=min\left\{f(x)\mid x\in[a,b]\right\}$
	- Với mọi $A\in[m,M]$, tồn tại $\alpha\in[a,b]$ sao cho $f(\alpha)=A$
	- Nếu $f(a)f(b)<0$ thì tồn tại $c\in(a,b)$ sao cho $f(c)=0$
## 2. Phân loại điểm gián đoạn
- Điểm $x_{0}$ được gọi là ==điểm gián đoạn bỏ được== của hàm số $f$ nếu tồn tại $\lim_{x \to x_{0} }f(x)\in \mathbb{R}$ và $\lim_{x \to x_{0} }f(x)\neq f(x_{0})$
- Điểm $x_{0}$ được gọi là ==điểm gián đoạn loại 1== của hàm số $f$ nếu tồn tại giới hạn trái và giới hạn phải nhưng chúng không bằng nhau và hiệu của chúng gọi là bước nhảy của $f$ tại $x_{0}$
- Trường hợp không phải 2 trường hợp trên gọi là ==điểm gián đoạn loại 2== (giới hạn trái hoặc giới hạn phải không tồn tại hữu hạn)
## 3. Hàm số liên tục đều
- Hàm số được gọi là liên tục đều trên tập $D$ nếu với mọi số $\epsilon>0$ bé tùy ý cho trước, tồn tại $\delta>0$ sao cho với $x_{1},x_{2}\in D$ thỏa mãn $\mid x_{2}-x_{1}\mid<\delta$ thì $\mid f(x_{2})-f(x_{1})\mid<\epsilon$
	$\longrightarrow$ Hiểu đơn giản là độ dốc hữu hạn
- Từ định nghĩa, một hàm số liên tục đều trên $D$ thì liên tục trên $D$, còn điều ngược lại thì không
## 4. Hàm số liên tục từng khúc
$\longrightarrow$ Về cơ bản là liên tục trên nửa đoạn, các khoảng ở giữa và nửa khoảng ở cuối