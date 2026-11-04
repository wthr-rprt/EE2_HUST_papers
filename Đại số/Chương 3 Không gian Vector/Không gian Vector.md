# 1. Khái niệm
- Cho tập hợp ${}V\neq\emptyset{}$ và trường ${}\mathbb K{}$ cùng với các phép toán cộng và nhân vô hướng được định nghĩa bởi các [[Ánh xạ]] sau:
  $$
  \begin{array}{l}
  (+):\begin{array}{l} V\times V\to V \\
  (u,v)\mapsto u+v
  \end{array} \\
  
  (.):\begin{array}
  {l}\mathbb K\times V\to V \\
  (k,v)\mapsto k.v
  \end{array}
  \end{array}
  $$
  - Lúc này ${}V{}$ được gọi là một không gian vector trên trường ${}\mathbb K{}$, hay một ${}\mathbb K{}$-không gian vector, nếu các phép toán thỏa mãn 8 điều kiện sau:
	  1. ${}u+v=v+u,\forall u,v\in V{}$
	  2. ${}(u+v)+w=u+(v+w), \forall u,v,w\in V{}$
	  3. ${}\exists\theta\in V{}$ thỏa mãn: ${}u+\theta=\theta +u=u,\forall u\in V{}$
	  4. ${}\forall u\in V,\exists u'\in V{}$ thỏa mãn: ${}u+u'=u'+u=\theta{}$
	  5. ${}\alpha(u+v)=\alpha u+\alpha v,\forall u,v\in V, \forall\alpha\in\mathbb K{}$
	  6. ${}(\alpha+\beta)u=\alpha u+\beta u,\forall u\in V,\forall\alpha,\beta\in \mathbb K{}$
	  7. ${}(\alpha.\beta)u=\alpha.(\beta u),\forall u\in V,\forall \alpha,\beta\in\mathbb K{}$
	  8. ${}1.u=u,\forall u\in V{}$ và là một đơn vị của trường ${}\mathbb K{}$
- Các quy ước và chú ý:
	1. Các phần tử của ${}V{}$ gọi là các vector, các phần tử của ${}\mathbb K{}$ gọi là các vô hướng (scalar)
	2. Phần tử ${}\theta{}$ gọi là vector không
	3. Phần tử ${}u'{}$ gọi là vector đối và duy nhất, ký hiệu là ${}-u{}$
	4. Các phần tử của ${}V{}$ thường ký hiệu ${}u,v,w{}$, các phần tử của ${}\mathbb K{}$ thường ký hiệu các chữ cái Hy Lạp nhỏ ${}\alpha,\beta,\gamma{}$
	5. Nếu ${}\mathbb K=\mathbb R{}$ thì ${}V{}$ là không gian vector thực, còn nếu ${}\mathbb K=\mathbb C{}$ thì ${}V{}$ là không gian vector phức
	6. Ta ký hiệu ${}ku{}$ thay vì ${}k.u{}$ nếu một thuộc ${}V{}$, một thuộc ${}\mathbb K{}$
	7. Không nói gì thì là không gian thực
	8. Phép trừ là cộng với vector đối
- ***Một số không gian vector:***
	1. Trường ${}\mathbb K{}$ chính nó là một không gian vector
	2. ${}\mathbb K^n{}$ cũng là một không gian vector
	3. ${}E{}$ là tập hợp chỉ có vector đã biết từ cấp 3
	4. Tập hợp ${}\mathcal M_{m\times n}(\mathbb K){}$
	5. Tập hợp các đa thức có bậc nhỏ hơn hoặc bằng một số
	6. Tập hợp các hàm liên tục trên một đoạn nào đó
# 2. Tính chất 
- Các tính chất suy ra từ 8 điều kiện định nghĩa:
	1. ${}k.v=\theta,k\in\mathbb K,v\in V{}$ nếu và chỉ nếu ${}k=0 \lor v=\theta{}$
	2. ${}-v=(-1)v,\forall v\in V{}$
	3. ${}(-k)v=k(-v)=-kv,\forall v\in V,\forall k\in\mathbb K{}$
	4. ${}k(u-v)=ku-kv,\forall u,v\in V,\forall k\in \mathbb k{}$
	5. ${}(\lambda-\alpha)u=\lambda u-\alpha u,\forall u\in V,\forall\lambda,\alpha\in\mathbb K{}$
	6. ${}ku=kv,k\neq 0\implies u=v{}$
	7. ${}hu=ku,u\neq\theta\implies h=k{}$
# 3. Không gian Vector con
- Cho ${}V{}$ là một ${}\mathbb K{}$-không gian vector và ${}W{}$ là một tập con khác rỗng của ${}V{}$. ${}W{}$ đóng kín đối với các phép toán trên ${}V{}$ khi: ${}w_{1}+w_{2}\in W,kw_{1}\in W,kw_{2}\in W,\forall w_{1},w_{2}\in W,k\in\mathbb K{}$. Khi đó các phép toán trên ${}V{}$ sẽ trở thành các phép toán trên ${}W{}$, gọi là các phép toán cảm sinh từ ${}V{}$ lên ${}W{}$
- ${}W{}$ đóng kín với các phép toán trên ${}V{}$ và cùng các phép toán cảm sinh tạo một ${}\mathbb K{}$-không gian vector thì ${}W{}$ là ${}\mathbb K{}$-không gian vector con của ${}V{}$
- Tiêu chuẩn không gian con:
	1. Đóng kín với phép cộng
	2. Đóng kín với phép nhân vô hướng
	3. Không rỗng
- Nhận xét:
	1. Mọi không gian con đều chứa ${}\theta{}$
	2. ${}W_{1}\cap W_{2}{}$ là không gian con
	3. ${}W_{1}+W_{2}{}$ là không gian con
	4. ${}W_{1}\cup W_{2}{}$ chưa chắc là không gian con
# 4. Tổ hợp tuyến tính