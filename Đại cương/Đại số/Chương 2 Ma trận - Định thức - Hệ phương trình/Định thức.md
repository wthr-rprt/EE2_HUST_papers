# 1. Phép thế
## a. Định nghĩa
- Một phép thế bậc $n$ là một [[Ánh xạ]] song ánh $f: \left\{1,2,3,\dots,n\right\}\to\left\{1,2,3,\dots,n\right\}$
- Gọi $S_{n}$ là tập hợp các phép thế bậc $n$
- Phép thế thường được viết dưới dạng $f=\begin{pmatrix}1&2&\dots &n \\  f(1)&f(2)&\dots&f(n)\end{pmatrix}$ với $(f(1),f(2),\dots,f(n))$ là một hoán vị của $\left\{1,2,3,\dots ,n\right\}$. Mỗi phép thế bậc $n$ tướng ứng với một hoán vị, do đó số các phép thế bậc $n$ $\mid S_{n}\mid=n!$ 
## b. Các tính chất và phân loại
- Với phép thế bậc $n$:
	1. Cặp $(f(i),f(j))$ với $1\leq i<j\leq n$ gọi là nghịch thế nếu $f(i)>f(j)$
	2. Nếu số nghịch thế của $f$ là chẵn/lẻ thì $f$ gọi là phép thế chẵn/lẻ tương ứng
	3. Dấu của phép thế $f$, ký hiệu là $sign(f)$, xác định là 1 nếu chẵn, và -1 nếu lẻ
		- Nếu $k$ là số nghịch thế $sign(f)=(-1)^k$ 
- Vì $f^{-1}(f(i))=i,\forall i\in(1,2,\dots,n)$ nên nếu $(f(i), f(j))$ là nghịch thế của $f$ thì $(j,i)$ là nghịch thế của $f^{-1}$, do đó có tính chất:
	- Số nghịch thế của $f$ bằng số nghịch thế của $f^{-1}$
	- $sign(f)=sign(f^{-1})$
	- $sign(f\circ g)=sign(f).sign(g)$
# 2. Định thức của ma trận vuông
## a. Định nghĩa
- Cho [[Ma trận]] $A=[a_{ij}]_{n\times n}$. Định thức của $A$ là một số ký hiệu $\det(A)$ hoặc $\mid A\mid$ xác định bởi: 
  $$
  \det(A)=|A|=\sum_{\sigma\in S_{n}}sign(\sigma)a_{1\sigma(1)}\dots a_{n\sigma(n)}
  $$
$\implies \det(A)$ là tổng $n!$ số hạng trong đó mỗi số hạng ứng với phép thế và được hiểu là tích dấu của phép thế với n phần tử trên các hàng và cột khác nhau của $A$, hoặc đơn giản hơn là số hạng nào thì cũng có đóng góp 1 số từ hàng và cột
  - Định thức ma trận vuông cấp $n$ gọi là định thức cấp $n$
## b. Khai triển Laplace
- Cho $A=[a_{ij}]_{n\times n}$. Với mỗi cặp $(i,j),1\leq i,j\leq n$, ký hiệu $M_{ij}$ là ma trận vuông cấp $n-1$ có được từ ma trận $A$ bằng cách bỏ đi $h_{i},c_{j}$
	- Khi đó phần phụ đại số của $a_{ij}$ được ký hiệu là $A_{ij}=(-1)^{i+j}\det(M_{ij})$
	- Qua đó có khai triển với $i,j$ cố định lần lượt là:
		- $\det(A)=\sum_{k=1}^na_{ik}$
		- $\det(A)=\sum_{k=1}^na_{kj}$
## c. Tính chất của định thức
- Cho $A=[a_{ij}]_{n\times n}$
	1. $\det(A)=\det(A^t)$
		- Tính chất định thức phát biểu đúng cho cột thì cũng đúng cho hàng
	2. Nếu đổi chỗ hai hàng/cột của ma trận thì giá trị định thức của nó đổi dấu
		- Nếu ma trận $A$ có hai hàng/cột giống nhau thì $\det(A)=0$
	3. Nếu nhân tất cả các phần tử trên một hàng/cột của ma trận $A$ với một số $k$ thì được ma trận $B$ với $\det(B)=k\det(A)$
		- Nếu các phần tử của một hàng/cột có thừa số chung thì ta có thể đưa thừa số chung đó ra ngoài dấu định thức
		- $\det(kA)=k^n\det(A)$
		- Nếu ma trận có một hàng hoặc cột bằng 0 thì $\det(A)=0$
	4. Nếu ma trận $A$ có hai hàng hoặc cột tỉ lệ thì $\det(A)=0$
	5. 
	   $$
	   \begin{vmatrix}
	   a_{11}&a_{12}&\dots&a_{1n} \\
	   \dots&\dots&\dots&\dots \\
	   b_{1}+c_{1}&b_{2}+c_{2}&\dots&b_{n}+c_{n} \\
	   \dots&\dots&\dots&\dots \\
	   a_{n1}&\dots&\dots&a_{nn}
	   \end{vmatrix}=\begin{vmatrix}
	   a_{11}&a_{12}&\dots&a_{1n} \\
	   \dots&\dots&\dots&\dots \\
	   b_{1}&b_{2}&\dots&b_{n} \\
	   \dots&\dots&\dots&\dots \\
	   a_{n1}&\dots&\dots&a_{nn}
	   \end{vmatrix}+\begin{vmatrix}
	   a_{11}&a_{12}&\dots&a_{1n} \\
	   \dots&\dots&\dots&\dots \\
	   c_{1}&c_{2}&\dots&c_{n} \\
	   \dots&\dots&\dots&\dots \\
	   a_{n1}&\dots&\dots&a_{nn}
	   \end{vmatrix}
	   $$
	6. Nếu cộng vào một hàng/cột một bội của hàng/cột khác thì ta được một ma trận mới có định thức bằng ma trận cũ
	7. Định thức các ma trận tam giác bằng tích các phần tử chéo
	8. Với mọi ma trận vuông cùng cấp thì $\det(AB)=\det(A)\det(B)$ 