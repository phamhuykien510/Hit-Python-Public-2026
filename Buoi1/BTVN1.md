Bài 1: Python là ngôn ngữ thông dịch hay biên dịch? Tại sao?

Python là ngôn ngữ thông dịch (Interpreted Language).

Khi chạy chương trình Python, mã nguồn (.py) sẽ được thông dịch từng dòng thành mã máy để thực thi.
Trong trình thông dịch CPython, mã nguồn trước tiên được chuyển thành bytecode (.pyc), sau đó Python Virtual Machine (PVM) thực thi bytecode này.
Vì vậy, người dùng không cần biên dịch chương trình thành file thực thi (.exe) trước khi chạy như C/C++.
Bài 2
1. Các kiểu dữ liệu trong Python
int: Số nguyên
float: Số thực
complex: Số phức
str: Chuỗi ký tự
bool: Kiểu logic (True, False)
list: Danh sách
tuple: Bộ dữ liệu
set: Tập hợp
dict: Từ điển
None: Giá trị rỗng
2. Các toán tử trong Python
Toán tử số học

+ : Cộng
- : Trừ
* : Nhân
/ : Chia
// : Chia lấy phần nguyên
% : Chia lấy dư
** : Lũy thừa
Toán tử so sánh

==
!=
>
<
>=
<=
Toán tử gán

=
+=
-=
*=
/=
%=
Toán tử logic

and
or
not
Toán tử thành viên

in
not in
Toán tử định danh

is
is not
3. Mệnh đề điều kiện và vòng lặp
Mệnh đề điều kiện

if
if...else
if...elif...else
Vòng lặp

for
while
Lệnh điều khiển vòng lặp

break
continue
pass
4. Kiểu dữ liệu True, False
True và False thuộc kiểu dữ liệu bool (Boolean). Đây là kiểu dữ liệu dùng để biểu diễn kết quả của các phép so sánh hoặc điều kiện trong chương trình.

Ví dụ:

print(5 > 3)   # True
print(5 < 3)   # False
Một số giá trị được coi là False trong Python gồm:

False
0
0.0
"" (chuỗi rỗng)
[] (danh sách rỗng)
{}
()
set()
None
Các giá trị còn lại thường được coi là True.