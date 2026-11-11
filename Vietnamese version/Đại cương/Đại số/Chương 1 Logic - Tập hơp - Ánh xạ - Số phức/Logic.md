## 1. Mệnh đề toán học và giá trị chân lý
- Mệnh đề toán học chỉ có đúng hoặc sai, không nhập nhằng, không rõ vì không đủ thông tin thì gọi là giả thuyết, thường ký hiệu kiểu A, B, C, D,...
- Giá trị chân lý là tính đúng sai của mệnh đề, tương tự [[nhị phân]] hay các [[bit]] thường ký hiệu kiểu V(A), V(B),...
## 2. Phép toán mệnh đề (theoretically [[Logic gates]])
- Phép phủ định, giống NOT 

| $A$ | $\overline{A}$ |
| --- | -------------- |
| 1   | 0              |
| 0   | 1              |
- Phép hội, giống AND

| $A$ | $B$ | $A \land B$ |
| --- | --- | ----------- |
| 1   | 1   | 1           |
| 1   | 0   | 0           |
| 0   | 1   | 0           |
| 0   | 0   | 0           |
- Phép tuyển, giống OR

| $A$ | $B$ | $A \lor B$ |
| --- | --- | ---------- |
| 1   | 1   | 1          |
| 1   | 0   | 1          |
| 0   | 1   | 1          |
| 0   | 0   | 0          |
- Phép kéo theo, giống IMPLY

| $A$ | $B$ | $A \rightarrow B$ |
| --- | --- | ----------------- |
| 1   | 1   | 1                 |
| 1   | 0   | 0                 |
| 0   | 1   | 1                 |
| 0   | 0   | 1                 |
- Phép tương đương, giống XNOR

| $A$ | $B$ | $A \leftrightarrow B$ |
| --- | --- | --------------------- |
| 1   | 1   | 1                     |
| 1   | 0   | 0                     |
| 0   | 1   | 0                     |
| 0   | 0   | 1                     |

## 3. Biểu thức và biến mệnh đề - Tương đương logic
- Về cơ bản là biểu thức nhưng mà là mệnh đề, còn tương đương logic nó như cái dấu bằng. ***Biểu thức lúc nào cũng đúng là hằng đúng và ngược lại hằng sai***
- Các tính chất của logic:
	- Phủ định của phủ định
	- Giao hoán
	- Kết hợp
	- Phân phối
	- Kéo theo: đối tuyển xuôi
	- Tương đương: kéo theo 2 chiều
	- Lũy đẳng
	- De Morgan: đối mọi phép và mệnh đề
#### 3.1. Hàm mệnh đề
- Mệnh đề có x
#### 3.2. Lượng từ phổ biến và tồn tại
- Với mọi - Tồn tại: $\forall - \exists$