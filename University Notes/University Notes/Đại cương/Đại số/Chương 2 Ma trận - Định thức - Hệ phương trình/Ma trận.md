 # 1. Định nghĩa
- Một ma trận cỡ $m\times n$ là một bảng số chữ nhật gồm $m$ hàng, $n$ cột dạng:
$$
A=\begin{pmatrix}
a_{11} & a_{12} & \dots & a_{1n} \\
a_{21} & a_{22} & \dots & a_{2n} \\
\dots & \dots & \dots & \dots \\
a_{n1} & a_{n2} & \dots & a_{nn}
\end{pmatrix}
$$
với $a_{ij}\in\mathbb{K}$. Số $a_{ij}$ gọi là phần tử của ma trận $A$, nằm ở hàng $i$, cột ${}j{}$ với mọi $1\leq i\leq m, 1\leq j\leq n$.
Có thể ký hiệu ma trận bằng ngoặc tròn hoặc ngoặc vuông. Hơn nữa, ký hiệu $A=[a_{ij}]_{m\times n}$ để chỉ $A$là ma trận $m$ hàng, $n$ cột với các phần $a_{ij}$.
- Nếu $\mathbb{K}=\mathbb{R}$, $A$ là ma trận thực, nếu $\mathbb{K}=\mathbb{C}$, $A$ là ma trận phức.
- $1\times n$ là ma trận hàng, ma trận $m\times 1$ là ma trận cột.
- Ma trận với $a_{ij}=0,\forall i,j$ được gọi là ma trận không, ký hiệu là $\theta$.
- Nếu số hàng và số cột của $A$ bằng nhau $(m=n)$ thì $A$ là ma trận vuôn cấp n
- Ký hiệu $\mathcal{M}_{m\times n}(\mathbb{K}), \mathcal{M}_{n}(\mathbb{K})$ lần lượt là tập hợp các ma trận $m\times n$ và tập hợp ma trận vuông cấp $n$ với các phần tử thuộc trường $\mathbb{K}$.
### ***Các đặc điểm:***
- Cho ma trận $A=\begin{pmatrix}a_{11}&a_{12}&\dots&a_{1n} \\  a_{21}&a_{22}&\dots&a_{2n} \\  \dots&\dots&\dots&\dots \\  a_{n1}&a_{n2}&\dots&a_{nn}\end{pmatrix}$
	- Các phần tử $a_{ii}$ gọi là các phần tử chéo lập thành đường chéo chính của $A$.
	- Nếu $a_{ij}=0, \forall i>j$ (các phần tử dưới đường chéo chính), gọi $A$ là ma trận tam giác trên.
	- Tương tự với ma trận tam giác dưới.
	- Vừa là ma trận tam giác trên và dưới là ma trận đường chéo (chỉ có $a_{ii}\neq 0$)
	- Nếu ma trận đường chéo có các phần tử đường chéo là 1 thì $A$ là ma trận đơn vị cấp $n$, ký hiệu là $I,E,I_{n},E_{n}$
- Hai ma trận bằng nhau khi chúng cùng cỡ và cùng giá trị ở mọi phần tử.
# 2. Phép toán ma trận
## a. Phép cộng
- Để cộng hai ma trận, chúng phải cùng cỡ.
$$[a_{ij}]_{m\times n}+[b_{ij}]_{m \times n}=[a_{ij}+b_{ij}]_{m\times n}$$
- Ma trận đối của ma trận $A$ là $-A=[-a_{ij}]_{m\times n}$
- Hiệu hai ma trận là tổng một ma trận với ma trận đối của ma trận khác.
- Với mọi ma trận $A,B,C$ cùng cỡ, chúng có:
	- Tính kết hợp
	- Tính giao hoán
	- Phần tử trung hòa (ma trận $\theta$)
$\implies \mathcal{M}_{m\times n}(\mathbb{K})$ cùng với phép cộng ma trận là một nhóm Abel trong [[Cấu trúc đại số]]
## b. Phép nhân một số với ma trận
$$
kA=[ka_{ij}]_{m\times n}
$$
- Với mọi ma trận $A,B$ và số $k,l\in\mathbb{K}$, chúng có:
	- Tính chất phân phối 2 chiều
	- Tính chất kết hợp
	- $1A=A, (-1)A=-A$
	- $0A=\theta$
	- $k\theta=\theta$
## c. Phép nhân hai ma trận
- Với $A$ và $B$ là các ma trận cỡ $m\times p$ và $p\times n$, tích $AB$ là ma trận $C=[c_{ij}]_{m\times n}$ xác định bởi:
	- Mỗi phần tử $c_{ij}$ là tổng các tích tương ứng của hàng $a$ và cột $b$
- Cho $A,B,C$ là các ma trận sao cho các phép toán trong các hệ thức thực hiện được và $k\in\mathbb{K}$. Khi đó chúng có:
	- $IA=A$ với $I$ là ma trận cấp phù hợp
	- Tính kết hợp với phép nhân ma trận và nhân ma trận với một số
	- Tính chất phân phối với phép cộng ma trận
		- Nhân ma trận không có tính chất giao hoán
		- Từ $AB=\theta$ không suy ra được $A=\theta$ hoặc $B=\theta$
- Với mọi số nguyên dương $n\geq 2$, tập $\mathcal{M}_{n}(\mathbb{K})$ với phép cộng và nhân lập thành một vành không giao hoán có đơn vị $I_{n}$
## d. Ma trận chuyển vị
- Ma trận chuyển vị $A^t$ của ma trận $A=[a_{ij}]_{m\times n}$ xây dựng là $A^t=[b_{ji}]_{n\times m}$
- Các tính chất:
	- $(A^t)^t=A$
	- $(A+B)^t=A^t+B^t$
	- $(kA)^t=kA^t$
	- $(AB)^t=B^tA^t$
- Cho ma trận $A$ vuông cấp $n$
	- $A$ là một ma trận đối xứng nếu $A^t=A$
	- $A$ là một ma trận phản xứng nếu $A^t=-A$
# 3. Phép biến đổi sơ cấp trên ma trận
- Để tiện sử dụng:
	- Hàng $i$ gọi là $h_{i}$, cột $j$ gọi là $c_{j}$
- Các phép biến đổi sau được gọi là sơ cấp 
	1. Đổi chỗ hai hàng hay hai cột ($h_{1}\leftrightarrow h_{2}$)
	2. Nhân một hàng hay một cột với một số khác $0$ ($\lambda h_{i}$)
	3. Cộng vào một hàng/cột một bội của hàng khác ($h_{k}+\lambda h_{i}\to h_{k}$)
