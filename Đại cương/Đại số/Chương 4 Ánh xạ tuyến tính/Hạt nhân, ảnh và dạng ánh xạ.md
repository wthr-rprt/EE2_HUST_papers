# 1. Định nghĩa
- Cho ${}V,W{}$ là hai [[Không gian Vector]] trên trường ${}\mathbb K$ và ${}f:V\to W{}$ là một [[Ánh xạ tuyến tính]]. Khi đó $$Kerf:=\left\{v\in V\mid f(v)=\theta_{W}\right\}=f^{-1}(\left\{\theta_{W}\right\})$$ được gọi là hạt nhân của ${}f{}$
${}\implies{}$ Có thể hiểu là chiều không gian bị sụp đổ khi phép chiếu giảm một chiều trong không gian $$\mathrm{Im} f:=\left\{f(v)\mid v\in V\right\}=\left\{w\in W\mid\exists v\in V,f(v)=w\right\}=f(V)$$
${}\implies{}$ Có thể hiểu là chiều [[Không gian hữu hạn chiều]] còn lại khi sụp đổ ${}dim(Kerf){}$ chiều
- ${}Kerf{}$ là một KGVT con của ${}V{}$
- ${}\mathrm{Im} f{}$ là một KGVT con của ${}W{}$
- Xét hệ ${}S=\left\{v_{1},v_{2},\dots,v_{m}\right\}{}$ của ${}V{}$ và hệ ${}f(S)=\left\{f(v_{1}),f(v_{2}),\dots ,f(v_{m})\right\}{}$ thì
	1. Nếu ${}S{}$ phụ thuộc tuyến tính thì ${}f(S){}$ phụ thuộc tuyến tính
	2. Nếu ${}f(S){}$ độc lập tuyến tính thì ${}S{}$ độc lập tuyến tính
	3. ${}\mathrm{Im} f=span(f(S)){}$
	4. Nếu ${}V{}$ là một hệ sinh của ${}S{}$ thì ${}\mathrm{Im} f{}$ là một hệ sinh của ${}f(S){}$ 
- Định lý về số chiều: Cho ${}V,W{}$ là hai KGVT trên trường ${}\mathbb K{}$ với ${}dimV<+\infty{}$ và ${}f:V\to W{}$ là một ánh xạ tuyến tính, khi đó: $$dim\mathrm{Im} f+dimKerf=dimV$$
# 2. Hạng của ánh xạ tuyến tính
- Cho hai KGVT ${}V,W{}$ trên trường ${}\mathbb K{}$, ${}dimV<\infty{}$ và ${}f:V\to W{}$ là một ánh xạ tuyến tính. Số chiều của không gian ${}\mathrm{Im} f{}$ được gọi là hạng của ${}f{}$, ký hiệu là ${}rank(f)=dim\mathrm{Im}f{}$
# 3. Đơn cấu, toàn cấu, đẳng cấu
- [[Ánh xạ]] tuyến tính được gọi lần lượt là đơn cấu, toàn cấu, đẳng cấu, khi nó lần lượt là đơn ánh, toàn ánh, song ánh
- Cho ${}V,W{}$ là hai KGVT hữu hạn chiều, ánh xạ tuyến tính ${}f:V\to W{}$
	1. ${}f{}$ là đơn cấu khi ${}Kerf=\left\{\theta_{V}\right\}{}$
	2. ${}f{}$ là toàn cấu khi và chỉ khi ${}dim\mathrm{Im}f=dimW{}$
- Hệ quả: Nếu cho hai KGVT ${}V,V'{}$ là hai KGVT hữu hạn chiều có ${}dimV=dimV'{}$ và ánh xạ tuyến tính ${}f:V\to V'{}$ thì ${}f{}$ là đơn cấu, toàn cấu và đẳng cấu
- Cho ${}V,W{}$ là hai KGVT trên trường ${}\mathbb K{}$. Gọi ${}V,W{}$ là đẳng cấu nếu tồn tại ${}f:V\to W{}$ là đẳng cấu, ký hiệu là ${}V\cong V'{}$