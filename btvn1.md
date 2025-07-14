Bài 1: Python là ngôn ngữ thông dịch hay biên dịch? Tại sao?
Python là ngôn ngữ thông dịch (interpreted). Lý do:
- Python không biên dịch mã nguồn thành mã máy trước khi chạy (như C/C++). Thay vào đó, trình thông dịch Python đọc và thực thi từng dòng lệnh một.
- Khi chạy chương trình Python, mã nguồn (.py) được dịch sang bytecode (tệp .pyc) và thực thi bởi Python Virtual Machine (PVM), không phải trực tiếp thành mã máy.
- Tuy nhiên, Python có một số yếu tố của biên dịch (như tạo bytecode), nhưng về bản chất, nó vẫn là ngôn ngữ thông dịch do cách thức thực thi từng dòng.
________________________________________
Bài 2:
1. Các kiểu dữ liệu trong Python
- Số (Numbers):
  + int (số nguyên): 5, -10
  + float (số thực): 3.14, -0.5
  + complex (số phức): 1 + 2j
- Chuỗi (String): "Hello", 'Python' (bất biến).
- Boolean: True, False (viết hoa chữ cái đầu).
- Danh sách (List): [1, 2, 3] (có thể thay đổi).
- Tuple: (1, 2, 3) (không thể thay đổi).
- Từ điển (Dictionary): {"name": "Alice", "age": 20} (cặp key-value).
- Tập hợp (Set): {1, 2, 3} (không trùng lặp, không thứ tự).
2. Các toán tử trong Python
- Toán tử số học: +, -, *, /, // (chia nguyên), % (chia dư), ** (lũy thừa).
- Toán tử so sánh: ==, !=, >, <, >=, <=.
- Toán tử logic: and, or, not.
- Toán tử gán: =, +=, -=, *=, /= (ví dụ: x += 1 tương đương x = x + 1).
3. Mệnh đề điều kiện và vòng lặp
- Mệnh đề điều kiện (if-elif-else):
VD: python
if x > 0:
    print("Dương")
elif x == 0:
    print("Không")
else:
    print("Âm")
- Vòng lặp (for, while):
VD: python
# For loop
for i in range(5):  # 0 đến 4
    print(i)  
# While loop
count = 0
while count < 5:
    print(count)
    count += 1
4. Kiểu dữ liệu Boolean (True, False)
- Là kết quả của phép so sánh hoặc điều kiện logic.
VD: python
a = 10 > 5  # a = True
b = bool(0)  # b = False (vì 0 là falsy)
- Giá trị "falsy": False, 0, "" (chuỗi rỗng), None, [], {}.

