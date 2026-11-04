# 1. Ma trận nghịch đảo
## a. Định nghĩa
- Ma trận ${}A\in\mathcal M_{n}{(\mathbb K)}{}$ gọi là [[Ma trận]] khả nghịch nếu tồn tại $B\in\mathcal M_{n}(\mathbb K)$ sao cho 
  $$
  AB=BA=I
  $$
  - Lúc này ${}B{}$ được gọi là ma trận nghịch đảo của ${}A{}$ và ký hiệu là ${}B=A^{-1}{}$
  - Ma trận nghịch đảo nếu tồn tại thì là duy nhất
  - Ký hiệu ${}GL_{n}(\mathbb K){}$ là tập hợp các ma trận khả nghịch cấp ${}n{}$ với mọi ${}n\in \mathbb N^*{}$
## b. Tính chất và điều kiện cần - đủ
- ***Tính chất***: 
	1. Ma trận đơn vị khả nghịch và có ma trận nghịch đảo bằng chính nó
	2. Nếu ${}A\in GL_{n}(\mathbb K){}$ thì ${}A^{-1}\in GL_{n(\mathbb K)}{}$ và ${}(A^{-1})^{-1}=A{}$
	3. Nếu ${}A\in GL_{n}(\mathbb K){}$ thì ${}A^{t}\in GL_{n(\mathbb K)}{}$ và ${}(A^t)^{-1}=(A^{-1})^t{}$
	4. Nếu ${}A\in GL_{n}(\mathbb K){}$ và ${}k\neq 0, k\in\mathbb K{}$ thì ${}kA\in GL_{n(\mathbb K)}{}$ và ${}(kA)^{-1}=\frac{1}{k}A^{-1}{}$
	5. Nếu ${}A,B\in GL_{n}(\mathbb K){}$ thì ${}AB\in GL_{n(\mathbb K)}{}$ và ${}(AB)^{-1}=B^{-1}A^{-1}{}$
		${}\longrightarrow{}$ ${}GL_{n}(\mathbb K){}$ cùng phép nhân ma trận với ma trận lập thành một nhóm không giao hoán với mọi ${}n\geq 2{}$
- ***Điều kiện:***
	1. Cho ${}A=[a_{ij}]\in \mathcal M_{n}(\mathbb K){}$ và ${}A_{ij}{}$ là phần phụ đại số của ${}a_{ij}{}$, đặt ${}C=[A_{ij}]_{n\times n}{}$ thì 
	   $$
	   C^tA=det(A)I
	   $$
		   - Ma trận ${}A\in\mathcal M_{n}(\mathbb K){}$ gọi là ma trận không suy biến khi ${}\det(A)\neq 0{}$ 
		   - Ma trận ${}A{}$ khả nghịch khi và chỉ khi ${}A{}$ không suy biến
		2. Qua đó 
	   $$
	   A^{-1}=\frac{1}{\det A}C^ t
	   $$
## c. Các cách tìm ma trận nghịch đảo
### c1. Tìm qua phần phụ đại số (điều kiện cần và đủ)
### c2. Giải phương trình ma trận (không khuyến khích)
### c3. Tìm qua biến đổi sơ cấp
$$
[A\mid I]\xrightarrow{bdsc} [I\mid B] \implies B=A^{-1}
$$

---

# 2. Hạng ma trận
## a. Khái niệm
- Cho ${}k{}$ là một số nguyên dương , ${}k\leq min\left\{m,n\right\}{}$. Ma trận vuông thu được khi bỏ ${}(m-k){}$ hàng và ${}(n-k){}$ cột của ${}A{}$ gọi là ma trận con cấp ${}k{}$ của ${}A{}$. [[Định thức]] của nó gọi là định thức con cấp ${}k{}$ của ${}A{}$
- Ma trận ${}A{}$ có ${}C^k_{m}.C^k_{n}{}$ ma trận con cấp ${}k{}$ 
- Hạng của ma trận ${}A{}$, ký hiệu ${}r(A){}$ là cấp cao nhất của các định thức con khác ${}0{}$ của ${}A{}$
- Quy ước hạng của ma trận ${}0{}$ là ${}0{}$ 
## b. Ma trận bậc thang và tính hạng ma trận
- Hàng không của một ma trận được hiểu là hàng có các phần tử đều là ${}0{}$ 
- Một ma trận bậc thang nếu có hàng không phải nằm dưới các hàng khác không, và với hai hàng khác không, phần tử khác ${}0{}$ đầu tiên của hàng trên nằm phía bên trái phần tử khác ${}0{}$ đầu tiên của hàng dưới
- Hạng của ma trận bậc thang bằng số hàng khác không của nó
- ==🟢Biến đổi sơ cấp không thay đổi hạng ma trận==