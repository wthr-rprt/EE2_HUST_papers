# 1. Định nghĩa
- Cho hai ${}\mathbb K{}$-[[Không gian Vector]] ${}V{}$ và ${}W{}$. [[Ánh xạ]] ${}f:V\to W{}$ được gọi là ánh xạ tuyến tính nếu:
	1. ${}f(u+v)=f(u)+f(v),\forall u,v\in V{}$
	2. ${}f(ku)=kf(u), \forall k\in\mathbb K,u\in V{}$
- Ánh xạ tuyến tính bảo tồn cấu trúc KGVT, tức là bảo tồn cả phép toán
- Nếu ${}V\equiv W{}$ thì ánh xạ ${}f{}$ là một toán tử tuyến tính
	- Có thể chứng minh nhanh ánh xạ là ánh xạ tuyến tính thông qua $$f(ku+lv)=kf(u)+lf(v), \forall u,v\in V, k,l\in\mathbb K$$
# 2. Tính chất
- Cho ${}V,W{}$ là hai KGVT trên trường ${}\mathbb K{}$ và ${}f:V\to W{}$ là ánh xạ tuyến tính
	1. ${}f(\theta_{V})=\theta_{W}{}$
	2. ${}f(-u)=-f(u){}$
	3. ${}f(u-v)=f(u)-f(v){}$
	4. ${}f(k_{1}u_{1}+k_{2}u_{2}+\dots+k_{n}u_{n})=k_{1}f(u_{1})+k_{2}f(u_{2})+\dots+k_{n}f(u_{n}){}$
- Khi ${}V{}$ là một ${}\mathbb K{}$-không gian vector ${}n{}$-chiều thì một ánh xạ tuyến tính ${}f:V\to W{}$ hoàn toàn được xác định bởi ảnh của một cơ sở, tức ${}f{}$ là duy nhất để chiếu một hệ cơ sở của ${}V{}$ lên một hệ vector bất kỳ của ${}W{}$
# 3. Các phép toán
- Cho ${}V,W{}$ là hai KGVT trên trường ${}\mathbb K{}$ và ánh xạ tuyến tính ${}f,g{}$ từ ${}V\to W{}$
	1. Tổng hai ánh xạ, ${}f+g{}$ là ánh xạ xác định bởi$$(f+g)(v)=f(v)+g(v),v\in V$$
	2. Tích của một số ${}k\in\mathbb K{}$ với ánh xạ tuyến tính ${}f{}$ là ánh xạ ${}kf{}$ xác định bởi $$(kf)(v)=kf(v),v\in V$$
- Hệ quả:
	- Tổng hai ánh xạ tuyến tính là một ánh xạ tuyến tính
	- Tích hai ánh xạ tuyến tính là một ánh xạ tuyến tính
	- Các phép ánh xạ tuyến tính cùng hai phép toán cộng và nhân với một số là một không gian vector ký hiệu như sau: $Hom(V,W)=\left\{f:V\to W\mid f\right.$ tuyến tính${}\left.\right\}{}$
