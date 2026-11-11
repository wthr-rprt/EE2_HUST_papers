# 1. Độc lập và phụ thuộc tuyến tính
- Một hệ các vector được gọi là phụ thuộc tuyến tính khi có các vector phụ thuộc tuyến tính, tức là có ít nhất một tổ hợp tuyến tính, hệ không phụ thuộc tuyến tính thì độc lập tuyến tính
- Khi có các vector trong ${}\mathbb R^n{}$, ta thành lập ma trận từ các vector theo hàng hoặc cột, khi đó:
	1. ${}r(A)<{}$ số vector thì hệ phụ thuộc tuyến tính
	2. ${}r(A)={}$ số vector thì hệ độc lập tuyến tính
- Tổng quan tính chất về độc lập và phụ thuộc tuyến tính
	1. Điều kiện cần và đủ để một hệ phụ thuộc tuyến tính là một trong các vector của hệ là một tổ hợp tuyến tính của các vector còn lại
	2. Nếu trong hệ chứa ${}\theta{}$ thì hệ phụ thuộc tuyến tính
	3. Hệ đơn vector độc lập tuyến tính khi và chỉ khi ${}v\neq 0{}$
	4. Hệ chứa vector phụ thuộc tuyến tính thì phụ thuộc tuyến tính
	5. Hệ con của hệ độc lập tuyến tính thì độc lập tuyến tính
# 2. Cơ sở và số chiều không gian
- Hệ ${}S{}$ vừa là hệ sinh của [[Không gian Vector]] ${}V{}$, vừa độc lập tuyến tính thì hệ ${}S{}$ được gọi là một cơ sở của không gian vector ${}V{}$, trong trường hợp ${}V{}$ chỉ chứa ${}\theta{}$ thì quy ước ${}S=\emptyset{}$ là cơ sở của ${}V{}$
- Cho không gian ${}V{}$ và hệ vector ${}S{}$, các khẳng định dưới đây là tương đương:
	1. ${}S{}$ là một cơ sở của ${}V{}$
	2. ${}S{}$ là hệ sinh tối tiểu
	3. ${}S{}$ là hệ độc lập tuyến tính tối đại
	4. Mọi vector của ${}V{}$ đều biểu diễn duy nhất qua ${}S{}$
- Mọi hệ sinh của ${}V{}$ đều chứa cơ sở của ${}V{}$
- Bất kỳ hệ độc lập tuyến tính nào cũng có thể bổ sung vector tạo thành cơ sở
- Với hệ sinh có ${}m{}$ phần tử của không gian hữu hạn sinh ${}V{}$ và hệ độc lập tuyến tính có ${}n{}$ phần tử của ${}V{}$, luôn có thể khẳng định ${}n\leq m{}$ 
- Nếu ${}V{}$ là không gian hữu hạn sinh thì mọi cơ sở đều có số phần tử hữu hạn
- Mọi cơ sở đều có số phần tử bằng nhau và là số chiều của không gian ${}V{}$, ký hiệu là ${}dim(V){}$, lúc này không gian vector được gọi là không gian vector hữu hạn chiều
- Hệ quả:
	1. Mọi hệ vector có số phần tử nhiều hơn số chiều đều phụ thuộc tuyến tính
	2. Mọi hệ độc lập tuyến tính có phần tử bằng số chiều đều là cơ sở
	3. Mọi hệ sinh có phần tử bằng số chiều đều là cơ sở
	4. Mọi hệ độc lập tuyến tính có thể bổ sung thêm ${}n-k{}$ phần tử để trở thành cơ sở, với ${}n{}$ là số chiều của không gian và ${}k{}$ là số phần tử của hệ độc lập tuyến tính ban đầu
# 3. Tọa độ vector
- Cho ${}V{}$ là một không gian vector hữu hạn chiều, và ${}\mathcal B=\left\{u_{1},u_{2},\dots,u_{n}\right\}{}$ là một cơ sở của ${}V{}$ (có tính thứ tự các vector trong cơ sở). Khi đó mọi vector ${}v{}$ đều là tổ hợp tuyến tính của cơ sở và biểu diễn duy nhất qua đó. Khi viết các hệ số của các vector trong tổ hợp tuyến tính ${}v{}$ theo đúng thứ tự cơ sở, ta được tọa độ vector ${}v{}$ theo cơ sở ${}\mathcal B{}$, ký hiệu là ${}[v]_{\mathcal B}{}$, hay
		$$[v]_{\mathcal B}=\left(\begin{array}
		{l} x_1 \\ x_2 \\ ... \\ x_n
		\end{array}\right)$$
- Đổi thứ tự các vector trong cơ sở sẽ đổi tọa độ vector
- Việc tìm tọa độ vector theo cơ sở có thể đưa về giải hệ Cramer (xem [[Hệ phương trình tuyến tính]])
# 4. Ma trận tọa độ vector theo cơ sở
- Cho không gian ${}V{}$, cơ sở ${}\mathcal B{}$ có ${}n{}$ vector, và hệ vector ${}S{}$ có ${}m{}$ vector. [[Ma trận]] của hệ vector ${}S{}$ đối với cơ sở ${}\mathcal B{}$, ký hiệu là ${}[S]_{\mathcal B}{}$ cỡ ${}n\times m{}$ xây dựng bởi ${}m{}$ cột tọa độ vector ${}v_{i}{}$ theo cơ sở ${}\mathcal B{}$
- Hạng của ma trận này, là hạng ma trận hệ vector ${}S{}$, ký hiệu ${}r(S){}$
- ${}r(S)=dim(span(S)){}$
# 5. Ma trận chuyển cơ sở
- Cho không gian ${}V{}$ chọn 2 cơ sở ${}\mathcal B_{1},\mathcal B_{2}{}$. Khi đó ma trận ${}[\mathcal B_{2}]_{\mathcal B_{1}}{}$ được gọi là ma trận chuyển cơ sở từ ${}\mathcal B_{1}{}$ sang ${}\mathcal B_{2}{}$, ký hiệu ${}C_{\mathcal B_{1}\to\mathcal B_{2}}{}$ và có các tính chất:
	1. Ma trận chuyển cơ sở luôn khả nghịch
	2. Ma trận nghịch đảo của một ma trận chuyển cơ sở là phép đổi ngược lại từ cơ sở kết quả về ma trận ban đầu
	3. ${}C_{\mathcal B_{1}\to\mathcal B_{3}}=C_{\mathcal B_{1}\to\mathcal B_{2}}.C_{\mathcal B_{2}\to\mathcal B_{3}}{}$
-  Công thức đổi tọa độ cho cơ sở:
		$$[v]_{\mathcal B_{1}}=C_{\mathcal B_{1}\to\mathcal B_{2}}.[v]_{\mathcal B_{2}}$$
