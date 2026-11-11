## 1. Định nghĩa
- Cho 2 tập $X$, $Y$ khác $\emptyset$, phép ánh xạ $f$ từ tập ([[Tập hợp]]) $X$ đến tập $Y$ được định nghĩa là một quy tắc đặt tương ứng sao cho mỗi phần tử $x \in X$ ứng với một phần tử $y \in Y$, ký hiệu $y=f(x)$. Khi đó, ánh xạ $f$ được viết là: 
		$f:X  \longrightarrow Y$
		$x\mapsto y=f(x)$
- Trong đó $X$ là tập nguồn, $Y$ là tập đích
## 2. Tập ảnh, nghịch ảnh
- Xét phép ánh xạ:
		$f:X\longrightarrow Y$
		$x\mapsto y=f(x)$
- Trong đó $A \subset Y$, $f(A)=\left\{f(x) \mid x \in A \right\}$ được gọi là ==***tập ảnh***==, $B\subset X$ $f^{-1}(B)=\left\{x\in X\mid f(x)\in B\right\}$ được gọi là ==***tập nghịch ảnh***==.
#### 2.1. ***Các tính chất của tập ảnh và nghịch ảnh***
1. $f(A\cup B)=f(A)\cup f(B);\forall A, B\subset X$
2. $f(A\cap B)\subseteq(f(A)\cap f(B)); \forall A, B\subset X$ ***(dấu bằng xảy ra khi f là đơn ánh)***
3. $f^{-1}(A\cup B)=f^{-1}(A)\cup f^{-1}(B);\forall A,B\subset Y$
4. $f^{-1}(A\cap B)=f^{-1}(A)\cap f^{-1}(B);\forall A,B\subset Y$
5. $f^{-1}(A\setminus B)=f^{-1}(A)\setminus f^{-1}(B);\forall A,B\subset Y$
## 3. Đơn ánh, toàn ánh, song ánh
#### 3.1. ***Đơn ánh***
- Một ánh xạ $f$ được gọi là đơn ánh nếu 
  $$
  x_{1}\neq x_{2}\implies f(x_{1})\neq f(x_{2})
  $$
- Qua đó có thể chứng minh $f$ là đơn ánh thông qua 
  $$
	f(x_{1})=f(x_{2}) \implies x_{1}=x_{2}, \forall x_{1},x_{2} \in X
  $$
	và $\forall y\in Y$, phương trình $y=f(x)$ có nhiều nhất một nghiệm trong $X$
#### 3.2. ***Toàn ánh***
- Ánh xạ $f$ là toàn ánh nếu với mỗi $y\in Y$ đều tồn tại ít nhất 1 $x\in X\mid y=f(x)$
#### 3.3. ***Song ánh***
- Ánh xạ $f$ là song ánh nếu nó đồng thời là đơn ánh và toàn ánh
- Qua đó, $f$ là song ánh khi và chỉ khi $y=f(x)$ có nghiệm duy nhất $\forall y\in Y$
- Có thể hiểu khác là một [[Hàm số]]
## 4. Tích ánh xạ, ánh xạ ngược
- Cho $f:X\to Y$ và $g:X\to Y$. $f$ và $g$ được gọi là bằng nhau, viết là $f=g$, nếu $f(x)= g(x),\forall x\in X$
#### 4.1. ***Tích ánh xạ***
- Cho $f:X\to Y$ và $g:Y\to Z$. Ánh xạ $h:X\to Z$ được gọi là tích hợp thành của 2 ánh xạ $f$ và $g$, ký hiệu bởi $g\circ f$ hoặc $gf$. Khi đó:
  $$
  (g \circ f)(x)=g(f(x)), \forall x\in X
  $$
***Chú ý:***

$$
h \circ(g \circ f) = (h \circ g)\circ f
$$
- Ánh xạ $g \circ f$ chỉ có thể thực hiện khi tập đích của $f$ là tập nguồn của $g$
- Tích ánh xạ ***không*** có tính giao hoán
- Tính đơn, toàn và song ánh của tích hợp thành giống với thành phần của nó khi 2 thành phần có cùng dạng ánh xạ ***(chỉ đúng với chiều khẳng định tính chất của tích ánh xạ)***
#### 4.2. ***Ánh xạ ngược***
- Cho ánh xạ $f:X\to Y$, nếu tồn tại $g:Y\to X$ thỏa mãn:
$$
\forall x\in X,(g\circ f)(x)=x
$$
và
$$
\forall y\in Y ,(f\circ g)(y)=y
$$
thì $g$ được gọi là ánh xạ ngược của $f$, ký hiệu là $f^{-1}$
- Ánh xạ ngược chỉ xuất hiện ở song ánh