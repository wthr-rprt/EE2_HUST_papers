# 1. Định nghĩa
- Cho ${}f{}$ là một [[Ánh xạ tuyến tính]] từ [[Không gian Vector]] ${}n{}$ chiều ${}V{}$ tới không gian vector ${}m{}$ chiều ${}W{}$. Giả sử ${}\mathcal B{}$ là một cơ sở của ${}V{}$ và ${}\mathcal B'{}$ là một cơ sở của ${}W{}$ với $$\mathcal B=\left\{v_{1},v_{2},\dots,v_{n}\right\},\mathcal B'=\left\{w_{1},w_{2},\dots,w_{m}\right\}$$
- [[Ma trận]] ${}A_{m\times n}{}$ gọi là ma trận của ánh xạ tuyến tính ${}f{}$ đối với cặp cơ sở ${}\mathcal B,\mathcal B'{}$ nếu với mọi vector ${}v\in V{}$ $$[f(v)]_{\mathcal B'}=A[v]_{\mathcal B}$$ở đó ${}[f(v)]_{\mathcal B'}{}$ là tọa độ cột của vector ${}f(v){}$ đối với cơ sở ${}\mathcal B'{}$ và ${}[v]_{\mathcal B}{}$ là tọa độ cột của vector ${}v{}$ đối với cơ sở ${}\mathcal B{}$
- Tổng quát hóa, ta thay ${}v_{i}{}$ vào phương trình trên ta được $$[f(v_{i})]_{\mathcal B'}=A[v_{i}]_{\mathcal B},\forall i=\overline{1,n}$$
- Do đó cột thứ ${}i{}$ của ma trận ${}A{}$ là vector tọa độ của ${}f(v_{i}){}$ theo cơ sở ${}\mathcal B'{}$
- Quy trình xác định ma trận của ánh xạ tuyến tính đối với mỗi cặp cơ sở của ${}V,W{}$
	1. Tính ${}f(v_{i}){}$ với mọi ${}i\in\mathcal B{}$
	2. Đổi cơ sở của ${}f(v_{i}){}$ sang ${}\mathcal B'{}$
	3. Lập ma trận tọa độ cột của hệ vector ${}f(v){}$
- Nên chọn các cơ sở thật đơn giản, khi đó ma trận có thể cung cấp thông tin liên quan đến ánh xạ tuyến tính
- Mối liên hệ giữa các ánh xạ tuyến tính và các ma trận là một đẳng cấu $${}\mathcal F:Hom(V,W)\to\mathcal M_{m\times n}(\mathbb K)\mid\mathcal F(f)=A{}$$
# 2. Ma trận đồng dạng và toán tử tuyến tính
- Với ${}A,B{}$ là hai ma trận vuông cùng cấp ${}n{}$. ${}A{}$ và ${}B{}$ đồng dạng, ký hiệu là ${}A\sim B{}$, khi tồn tại một ma trận ${}P{}$ không suy biến sao cho $$B=P^{-1}AP$$
- Cho ${}f{}$ là một toán tử tuyến tính của KGVT ${}n{}$ chiều ${}V{}$. Giả sử ${}\mathcal B{}$ là một cơ sở của ${}V{}$ với $$\mathcal B=\left\{v_{1},v_{2},\dots,v_{n}\right\}$$
- Ma trận ${}A{}$ của ${}f{}$ đối với cặp cơ sở ${}\left\{\mathcal B,\mathcal B\right\}{}$ được gọi là ma trận của ${}f{}$ đối cơ sở ${}\mathcal B{}$
- Ma trận của toán tử tuyến tính là ma trận vuông cấp ${}n{}$ thỏa mãn tính chất $$[f(v_{i})]_{\mathcal B}=A[v_{i}]_{\mathcal B}$$
- Giả sử ${}f:V\to V{}$ là một toán tử tuyến tính của [[Không gian hữu hạn chiều]] ${}V{}$ và ${}\mathcal B,\mathcal B'{}$ là hai cơ sở của ${}V{}$. Nếu ${}A{}$ là ma trận của ${}f{}$ đối với ${}\mathcal B{}$ và ${}A'{}$ là ma trận của ${}f{}$ đối với $\mathcal B'$ thì $$A'=C^{-1}AC$$ trong đó ${}C{}$ là ma trận chuyển cơ sở từ ${}\mathcal B{}$ sang ${}\mathcal B'{}$ 
# 3. Ma trận và các phép toán trên ánh xạ
- Nếu các ánh xạ tuyến tính ${}f,g{}$ có ma trận tương ứng là ${}A,B{}$ đối với cặp cơ sở nào đó của ${}V,W{}$ thì tổng ${}f+g{}$ có ma trận là ${}A+B{}$ đối với các cơ sở này
- Nếu ánh xạ tuyến tính ${}f{}$ có ma trận ${}A{}$ đối với một cặp cơ sở của ${}V,W{}$ thì tích ${}kf{}$ với ${}k\in\mathbb K{}$ với một cặp cơ sở của ${}V,W{}$ thì tích ${}kf,k\in\mathbb K{}$ có ma trận ${}kA{}$ đối với cặp cơ sở này
- Cho các ánh xạ tuyến tính xác định trên các không gian hữu hạn chiều ${}V,W,Z{}$ có tính chất ${}V\xrightarrow fW\xrightarrow gZ{}$ thì tích hai ánh xạ ${}g\circ f:V\to Z{}$ cũng là một ánh xạ tuyến tính. Nếu ${}f{}$ có ma trận ${}A{}$ đối với cặp cơ sở ${}\mathcal B_{V},\mathcal B_{W}{}$ và ${}g{}$ có ma trận ${}C{}$ đối với cặp cơ sở ${}\mathcal B_{W},\mathcal B_{Z}{}$ thì tích ${}g\circ f{}$ có ma trận ${}CA{}$ đối với cặp cơ sở ${}\mathcal B_{V},\mathcal B_{Z}{}$
- Cho ${}V,W{}$ là hai KGVT có cùng số chiều, ánh xạ tuyến tính ${}f:V\to W{}$ được gọi là không suy biến nếu ma trận của nó không suy biến. Ánh xạ ${}f:V\to W{}$ được gọi là không suy biến khi và chỉ khi nó là một đẳng cấu. Nếu đẳng cấu này có ma trận ${}A{}$ với một cặp cơ sở nào đó thì ánh xạ ngược ${}f^{-1}{}$ có ma trận ${}A^{-1}$ đối với cặp cơ sở này
- Ma trận của ánh xạ tuyến tính khả nghịch khi và chỉ khi ${}f{}$ là đẳng cấu