	
# BÀI CODE CƠ BẢN CHO NGƯỜI MỚI BẮT ĐẦU










## KIỂU DỮ LIỆU, TOÁN TỬ, CẤU TRÚC RẼ NHÁNH




# Bài 1 : Tính Giá Trị Của biểu thức

**Cho biểu thức A(x) = x^3 + 3x^2 + x + 1 Với giá trị của x được nhập từ bàn phím, tính và in ra giá trị của biểu thức trên**

Input Format

Số nguyên x

Constraints

-10^5≤x≤10^5

Output Format

In ra kết quả cùa biểu thức

Sample Input 0


```pre
2
```


Sample Output 0

<pre>
23	
</pre>




# Bài 2. Tính toán giá trị biểu thức 2

**Yêu cầu: Cho ba số nguyên a , b và c, hãy tính S = a*(b+c)+b*(a+c).**

Input Format

3 số a, b, c trên 1 dòng.

Constraints

-10^8≤a,b,c≤10^8

Output Format

In ra giá trị của biểu thức.

Sample Input 0

```re
1 2 3
```


Sample Output 0

<pre>
13	
</pre>


# Bài 3. Đổi nhiệt độ

**Công thức chuyển đơn vị đo nhiệt độ từ C sang F như sau: F = (C * 9 / 5) + 32. Viết chương trình cho phép nhập vào nhiệt độ đo theo độ C là số nguyên dương không quá 10^6, thực hiện chuyển sang đơn vị đo độ F và in ra màn hình. (Lưu ý luôn lấy 2 chữ số thập phân sau dấu chấm phẩy)**


Input Format

Nhiệt độ ở độ C là một số nguyên không âm.

Constraints

0≤n≤10^6

Output Format

Kết quả đổi từ độ C sang độ F

Sample Input 0

```ew
24
```

Sample Output 0



<pre>
75.20	
</pre>


# Bài 4. Chu vi và diện tích hình tròn

**Cho bán kính R của hình tròn. Yêu cầu tính chu vi và diện tích của hình tròn đó. Lấy PI = 3.14. Công thức tính chu vi = 2 * PI * R, diện tích = PI * R * R**

Input Format

1 dòng chứa bán kính R là số nguyên dương.

Constraints

1≤R≤1000

Output Format

In ra chu vi và diện tích trên 1 dòng, kết quả lấy độ chính xác 4 số sau dấu phẩy.

Sample Input 0

```ew
10
```

Sample Output 0

<pre>
62.8000 314.0000
</pre> 


# Bài 5. Khoảng cách Euclid.


**Có nhiều khoảng cách giữa 2 điểm trong hệ tọa độ ví dụ như khoảng cách Manhattan, Euclid, Minkowski. Nhưng trong chương trình toán phổ thông các bạn sử dụng nhiều nhất là khoảng cách Euclid. Vì vậy bạn hãy tính khoảng cách Euclid giữa 2 điểm trong hệ tọa độ Oxy**

Input Format

Tọa độ của 2 điểm (x1, y1) và (x2, y2) là các số nguyên

Constraints

-10^6≤xi,yi≤10^6

Output Format

In ra khoảng cách giữa 2 điểm, lấy độ chính xác 2 số sau dấu phẩy.

Sample Input 0


```ere
1 4 4 8
```


Sample Output 0

<pre>
5.00
	
</pre>




# Bài 6. Luyện tập viết câu điều kiện





**Cho một số nguyên không âm N.Bạn hãy thực hiện viết câu lệnh để kiểm tra các điều kiện sau :
1.N có phải là số chẵn? (Kiểm tra số dư của N với 2 và so sánh 0)
2.N có phải là số vừa chia hết cho 3 vừa chia hết cho 5? (Kết hợp 2 điều kiện sử dụng &&)
3.N có phải là số chia hết 3 nhưng không chia hết cho 7? (Kết hợp 2 điều kiện sử dụng &&)
4.N có phải là số chia hết cho 3 hoặc 7? (Kết hợp 2 điều kiện sử dụng ||)
5.N là số lớn hơn 30 và nhỏ hơn 50? (Kết hợp 2 điều kiện sử dụng &&)
6.N có phải là số không nhỏ hơn 30 và chia hết cho ít nhất một trong 3 số 2, 3, 5? (Lớn hơn hoặc bằng 30 && (chia hết ....
7.N có phải là số có 2 chữ số có chữ tận cùng là một số nguyên tố? (>= 10, <= 99, kiểm tra chữ số tận cùng là 2, 3, 5, 7)
8.N có phải là số không vượt quá 100 và chia hết cho 23?
9.N không thuộc đoạn [10, 20]?
10.N có chữ số tận cùng là bội số của 3?**

Input Format

Số nguyên dương N

Constraints

1<=N<=10^6

Output Format

In ra 10 dòng, mỗi dòng là "YES" hoặc "NO" tương ứng với 10 điều kiện. Nếu N thỏa mãn điều kiện thứ i thì dòng i in ra YES, ngược lại in ra NO.

Sample Input 0


```rr
263
```


Sample Output 0

<pre>
	NO
NO
NO
NO
NO
NO
NO
NO
YES
YES
</pre>



# Bài 7. Số lớn nhất và nhỏ nhất


**Cho 2 số nguyên a và b. Bạn hãy tìm 2 số sau, số thứ 1 là số lớn nhất <= a mà chia hết cho b, số thứ 2 là số nhỏ nhất >=a mà chia hết cho b. Chú ý các bạn không được dùng vòng lặp.
Gọi ý : Số thứ 1 : a / b * b
Số thứ 2 : (a + b - 1) / b * b
Hoặc các bạn có thể if else cũng được, ko dùng vòng lặp.
Số thứ 2 nếu dùng if else thì check a chia hết cho b đáp án là a, còn ko thì là (a / b + 1) * b.
Các phép chia đều là chia nguyên**


Input Format

1 dòng chứa 2 số a, b.

Constraints

1<=a,b<=10^6

Output Format

Dòng đầu tiên in ra số thứ 1 cần tìm. Dòng thứ 2 in ra số thứ 2 cần tìm.

Sample Input 0


```res
717 689
```


Sample Output 0

<pre>
689
1378
</pre>



# Bài 8. Tổng, hiệu, tích, thương


**Nhập vào 2 số nguyên, in ra tổng, hiệu, tích, thương(lấy độ chính xác với 4 chữ số) của 2 số đó. Bài này có thể bị sai do 2 nguyên nhân : 1. Khi tính tích bị tràn số, 2. Độ chính xác của thương.**

Input Format

2 số nguyên a, b trên 1 dòng.

Constraints

-10^8≤a,b≤10^8

Output Format

In ra tổng, hiệu, tích, thương trên từng dòng. Nếu trường hợp không thể tìm được thương của 2 số thì sẽ in ra "INVALID" cho dòng kết quả của thương.

Sample Input 0

```res
7769 0
```

Sample Output 0

<pre>
7769
7769
0
INVALID	
</pre>

Sample Input 1


```res
9794 1282
```

Sample Output 1

<pre>
11076
8512
12555908
7.6396	
</pre>



# Bài 9.Kiểm tra năm nhuận

**Năm nhuận là năm chia hết cho 400 hoặc (chia hết cho 4 và không chia hết cho 100). Nhập vào N là một năm và kiểm tra xem N có phải là năm nhuận hay không?**

Input Format

Số nguyên dương N.

Constraints

1<=N<=5000

Output Format

In ra YES nếu N là năm nhuận, ngược lại in ra NO.

Sample Input 0


```res
2020
```

Sample Output 0

<pre>
YES	
</pre>


# Bài 10. Tam giác hợp lệ


**Cho 3 cạnh a, b, c là độ dài 3 cạnh của tam giác, kiểm tra xem a, b, c có thể tạo thành một tam giác hợp lệ hay không?**

Gợi ý : Tam giác hợp lệ là tam giác có 3 cạnh đều dương, và tổng hai cạnh luôn lớn hơn cạnh còn lại => Cần 6 điều kiện và kết hợp toán tử &&

Input Format

1 dòng chứa 3 số a, b, c.

Constraints

-10^6<=a,b,c<=10^6

Output Format

In ra YES nếu a, b, c là 3 cạnh của 1 tam giác hợp lệ, ngược lại in ra NO.

Sample Input 0


```res
3 4 5
```

Sample Output 0


<pre>
	YES
</pre>
