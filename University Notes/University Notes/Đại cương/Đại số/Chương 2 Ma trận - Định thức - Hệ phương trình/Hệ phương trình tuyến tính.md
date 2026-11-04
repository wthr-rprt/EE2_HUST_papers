# 1. Khái niệm
- Hệ phương trình tuyến tính ${}m{}$ phương trình ${}n{}$ ẩn có dạng 
  $$
  \left\{
  \begin{array}{l}
  a_{11}x_{1}+a_{12}x_{2}+\dots+a_{1n}x_{n}=b_{1} \\
  a_{21}x_{1}+a_{22}x_{2}+\dots+a_{2n}x_{n}=b_{2} \\
  \dots \\
  a_{n1}x_{1}+a_{n2}x_{2}+\dots+a_{nn}x_{n}=b_{n}
  \end{array}
  \right.
  (2.6)
  $$
  Trong đó ${}a_{ij},b_{i}\in\mathbb K, i=1,2,\dots,m;j=1,2,\dots,n{}$ là các số cho trước và ${}x_{j}, j=1,2,\dots,n{}$ là các ẩn, các số ${}a{}$ là hệ số, các số ${}b{}$ là hệ số tự do, dạng trên gọi là dạng tổng quát của hệ. Nếu ${}b_{i}=0,\forall i{}$ thì hệ gọi là hệ phương trình tuyến tính thuần nhất
- ${}a_{ij}{}$ là hệ số của phương trình thứ ${}i{}$ và ẩn thứ ${}j{}$
- Nghiệm của hệ là một bộ số ${}t_{1},t_{2},\dots,t_{n}\in \mathbb K^n{}$ sao cho khi thay các ${}t{}$ vào ${}x{}$ tương ứng thì được các đồng nhất thức trên ${}\mathbb K{}$
## Dạng ma trận của hệ phương trình tuyến tính
- Cho hệ phương trình ${}(2.6){}$
	1. [[Ma trận]] ${}A=[a_{ij}]_{m\times n}{}$ gọi là ma trận hệ số
	2. Ma trận cột ${}B=\begin{pmatrix}b_{1} \\  b_{2} \\  \dots \\  b_{m}\end{pmatrix}{}$ là cột hệ số tự do
	3. Ma trận ${}\overline A=[A|B]= \left(\begin{array}{cccc|c}a_{11} & a_{12} & \dots & a_{1n} & b_{1} \\  a_{21} & a_{22} & \dots & a_{2n} & b_{2} \\  \dots \\  a_{1n} & a_{2n} & \dots & a_{nn} & b_{m}\end{array}\right){}$ gọi là ma trận bổ sung
	4. Ma trận ${}X=\begin{pmatrix}x_{1} \\  x_{2} \\  \dots \\  x_{n}\end{pmatrix}{}$ gọi là cột ẩn số
- Các phần tử ${}i{}$ của ma trận bổ sung ${}\overline A{}$ là các hệ số của phương trình thứ ${}i{}$ của hệ phương trình ${}AX=B{}$ và ngược lại. Do đó khi cố định biến sẽ xuất hiện một song ánh (xem trong [[Ánh xạ]]) giữa các ma trận bổ sung và các hệ phương trình tuyến tính, lúc này ${}AX=B{}$ gọi là dạng ma trận của hệ phương trình tuyến tính
# 2. Hệ phương trình Cramer
- Hệ phương trình ${}AX=B{}$ gọi là hệ Cramer nếu ${}A{}$ là ma trận vuông và ${}\det A\neq 0{}$ (xem trong [[Định thức]])
- Hệ Cramer có nghiệm duy nhất, xác định bởi công thức ${}x_{j}=\frac{\det A_{j}}{\det A},j=1,2,\dots,n{}$, với ${}A_{j}{}$ là ma trận thu được khi thay cột ${}j{}$ của ${}A{}$ với cột hệ số tự do 
# 3. Điều kiện có nghiệm và phương pháp giải
- Các phép biến đổi tương đương (2 hệ tương đương là 2 hệ có cùng nghiệm)
	1. Đổi chỗ 2 phương trình
	2. Nhân 2 vế của phương trình với một số khác ${}0{}$
	3. Nhân một phương trình với một số rồi cộng vào phương trình khác
		- Các phép biến đổi trên hệ ứng với các biến đổi sơ cấp trên hàng của ma trận bổ sung của hệ
- Điều kiện có nghiệm của hệ, ==🟢định lý Kronecker - Capelli==: Hệ phương trình có nghiệm khi hạng của ma trận hệ số bằng hạng của ma trận bổ sung
	1. ${}r(\overline A)\neq r(A){}$ thì hệ vô nghiệm
	2. ${}r(\overline A)=r(A)=n{}$ thì hệ có nghiệm duy nhất
	3. ${}r(\overline A)=r(A)=r<n{}$ thì hệ có vô số nghiệm phụ thuộc vào ${}(n-r){}$ tham số
- ==🟢Phương pháp Gauss==:
	1. Lập ma trận bổ sung
	2. Biến đổi sơ cấp cho ma trận về dạng bậc thang
	3. Đánh giá nghiệm, nếu phụ thuộc vào tham số thì đặt tham số vào một số ẩn và giải theo tham số, còn lại giải bình thường
	4. Nếu hệ là hệ Cramer, có thể tiếp tục biến đổi ma trận về ma trận đường chéo, lúc này cột hệ số tự do sẽ là nghiệm, bước bổ sung này gọi là phương pháp Gauss - Jordan
- Hệ phương trình tuyến tính thuần nhất: 
	1. Luôn có nghiệm ${}(0,0,\dots,0){}$ gọi là nghiệm tầm thường
	2. Khi dùng phương pháp Gauss có thể dùng luôn ma trận ${}A{}$ thay vì ma trận bổ sung của nó
	3. Hệ có nghiệm không tầm thường khi ${}r(A)<n{}$ và ${}\det A=0{}$ 