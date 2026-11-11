## 0. Phép toán hai ngôi
- Cho [[Tập hợp]] $X\neq\emptyset$. Một phép toán hai ngôi (gọi tắt là phép toán) trên tập $X$, ký hiệu là "$*$", là một quy tắc biến đổi mỗi phần tử $(x,y)\in X^2$ thành phần tử $x*y\in X$. Nói cách khác là một ánh xạ:
	 $*:X^2\to X$
	$(x,y)\mapsto x*y$
- Tập $X$ cùng với phép toán 2 ngôi cho trên gọi là một đại số 2 ngôi, ký hiệu là $(X,*)$
- Tùy tập X thì $*$ sẽ là phép toán cụ thể trên tập đó
	$\longrightarrow$ Cơ bản thì $X$ sẽ là tập số kiểu $\mathbb{N},\mathbb{Z},\mathbb{Q},\mathbb{R}$ còn $*$ sẽ là $+,.,\dots$ 
#### Một số tính chất
1. Phép toán $*$ được gọi là có tính chất kết hợp nếu: 
   $$
   (a*b)*c=a*(b*c), \forall a,b,c\in X
   $$
2. Phép toán $*$ được gọi là có tính chất giao hoán nếu:
   $$
   a*b=b*a,\forall a,b\in X
   $$
3. Phần tử $e\in X$ duy nhất được gọi là phần tử trung hòa của phép toán $*$ nếu:
   $$
   a*e=e*a=a, \forall a\in X
   $$
4. Giả sử $X$ có phần tử trung hòa $e$ và $a\in X$. Phần tử $b\in X$ được gọi là phần tử đối của $a$ nếu: 
   $$
   a*b=b*a=e
   $$
- ***QUY ƯỚC MỘT SỐ KÝ HIỆU:***
	1. Để tiện thì các phép toán hai ngôi sẽ được gọi là cộng hoặc nhân kể cả khi không trong tập số
	2. Nếu phép toán là cộng thì $e$ gọi là phần từ không $(\theta)$ và phần tử đối gọi là $-x$
	3. Nếu phép toán là nhân thì $e$ gọi là phần tử đơn vị (1) và phần tử đối gọi là phần tử nghịch đảo ($x^{-1}$), tồn tại phần tử nghịch đảo gọi là khả nghịch và $a.b$ có thể viết là $ab$
## Nhóm, vành, trường
#### 1. Nhóm
- Cho tập $X\neq\emptyset$ với phép toán $+$, khi đó đại số hai ngôi $(X,+)$ lập thành một nhóm nếu thỏa mãn: 
	1. ==Tính chất kết hợp==: $(a+b)+c=a+(b+c), \forall a,b,c \in X$
	2. ==Tồn tại phần tử trung hòa== $\theta\in X$ sao cho: $x+\theta=\theta+x=x,\forall x\in X$
	3. Với mỗi phần tử $x\in X$, ==tồn tại phần tử đối== $-x\in X$ sao cho: $x+(-x)=(-x)+x=\theta$
		1. $a+b=b+a,\forall a,b\in X$
- Nhóm $X$ được gọi là ==nhóm giao hoán== hoặc ==nhóm Abel== nếu có thêm điều kiện phụ
#### 2. Vành
- Cho tập $X\neq \emptyset$, trên $X$ trang bị 2 phép toán "$+$" và "$.$". Khi đó $(X,+,.)$ là một vành khi thỏa mãn:
	1. $(X,+)$ ==là một nhóm Abel==
	2. Phép toán "$.$" ==có tính kết hợp==: $(a.b).c=a.(b.c), \forall a,b,c\in X$
	3. Phép toán "$.$" ==có tính phân phối _về 2 phía_== đối với phép toán "$+$":
	   $a(b+c)=ab+ac$  
	   $(b+c)a= ba+ca, \forall a,b,c\in X$
		1. Nếu phép nhân có tính giao hoán thì gọi là ==vành giao hoán==
		2. Nếu phép nhân có đơn vị thì gọi là ==vành có đơn vị==
#### 3. Trường
- Cho tập $X$ khác rỗng, trên đó xác định hai phép toán "$+$" và phép toán "$.$". Khi đó $(X,+,.)$ là một trường nếu:
	1. $(X,+,.)$ ==là một vành giao hoán có đơn vị 1==
	2. Với mọi $\theta\neq x\in X$, luôn tồn tại một phần tử nghịch đảo sao cho:
	   $$
	   x.x^{-1}=x^{-1}.x= 1
	   $$