# 1. Khảo sát [[Hàm số]]
- Đường tiệm cận (đã học ở cấp 3, nên đọc thêm)
- Đường thẳng ${}y=ax+b,a\neq 0{}$ được gọi là tiệm cận xiên của đồ thị hàm số ${}f{}$ nếu 
  $$
  \lim_{x \to \pm\infty}(f(x)-ax-b)=0 
  $$
- Khi đó có thể tính ${}a,b{}$ bằng: 
  $$
  a=\lim_{x \to \pm\infty}\frac{f(x)}{x} 
  $$
    và
  $$
  b=\lim_{x \to \pm\infty }(f(x)-ax) 
  $$
# 2. Khảo sát đường cong dạng tham số
- Phương trình tham số của một đường cong được cho dưới dạng: 
  $$
  \left\{\begin{array}{l}
  x=x(t) \\
  y=y(t),
  \end{array}\right.
  $$
  với tham số ${}t\in D,D\subset \mathbb R{}$
- Tiệm cận:
	1. Khi ${}t\to t_{0}{}$ hoặc ${}t\to\infty{}$ mà ${}x(t)\to x_{0},y(t)\to \infty{}$ thì ${}x=x_{0}{}$ là tiệm cận đứng
	2. Khi ${}t\to t_{0}{}$ hoặc ${}t\to\infty{}$ mà ${}x(t)\to \infty,y(t)\to a{}$ thì ${}y=a{}$ là tiệm cận ngang
	3. Khi ${}t\to t_{0}{}$ hoặc ${}t\to\infty{}$ mà ${}x(t)\to \infty,y(t)\to \infty{}$ thì đường cong có thể có tiệm cận xiên nếu ${}\frac{y(t)}{x(t)}\to a\neq 0,y(t)-ax(t)\to b{}$ thì ${}y=ax+b{}$ là tiệm cận xiên
- Hệ số góc tiếp tuyến tại ${}M_{0}(x_{0};y_{0}){}$ khi ${}x=x(t){}$ có hàm ngược ${}t=t(x){}$ là 
  $$
  f'(x_{0})=\frac{y'(t_{0})}{x'(t_{0})}
  $$
# 3. Đường cong trong hệ tọa độ cực
- Trong mặt phẳng, chọn một điểm ${}O{}$ cố định làm gốc cực và một tia ${}Ox{}$ là trục cực. Vị trí của điểm ${}M{}$ trong mặt phẳng xác định bởi [[Vector]] ${}\overrightarrow{OM}{}$. Gọi ${}r=|\overrightarrow{OM}|\geq 0{}$ là bán kính cực và góc ${}\varphi=(Ox,\overrightarrow{OM})\in[0,2\pi){}$ là góc cực. Cặp số ${}(r,\varphi){}$ là tọa độ cực của ${}M{}$
- Suy rộng: Mở rộng ${}r\in\mathbb R, \varphi\in \mathbb R{}$ với ${}\varphi{}$ là góc lượng giác, còn nếu ${}r<0{}$ thì ta xác định điểm ${}M(r;\varphi){}$ trùng với điểm ${}M(-r;\varphi+\pi){}$
- Công thức liên hệ với tọa độ Descartes: 
  $$
  \left\{\begin{array}
  {l} x=r\cos \varphi \\
  y=r\sin \varphi
  \end{array}\right. ,\left\{\begin{array}
  {l} r=\sqrt{ x^2+y^2 }  \\
\tan \varphi=\frac{y}{x}(x\neq 0)
  \end{array}\right.
  $$
- Phương trình ${}r=f(\varphi){}$ là phương trình đường cong trong hệ tọa độ cực
# 4. Tính lồi lõm, điểm uốn của đồ thị hàm số
- Lồi: đạo hàm cấp 2 lớn hơn ${} 0{}$
- Lõm: đạo hàm cấp 2 nhỏ hơn ${}0{}$
- Điểm uốn: vị trí đổi tính lồi lõm