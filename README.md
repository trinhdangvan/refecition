
## refecition 7/4/2021
#### 1.Abstract Class.
+ Lớp trừu tượng trước tiên nó chính là 1 lớp, nhưng nó được gọi là lớp trừu tượng bởi vì: – Lớp này sẽ chứa các phương thức trừa tượng. – Các lớp khác khi kế thừa lớp trừu tượng sẽ phải định nghĩa các phương thức trừu tượng ấy
+ Mức truy cập các abstract method phải ở public hoặc protected để lớp kế thừa có thể định nghĩa lại.
+ Không dùng từ khóa final cho khai báo abstract class và abstract method.
#### 2. Interface.
+ Interface là một khuôn mẫu iúp cho chúng ta tạo ra bộ khung cho một hoặc nhiều đối tượng và nhìn vào interface thì chúng ta hoàn toàn có thể xác định được các phương thức và các thuộc tính cố định (hay còn gọi là hằng) sẽ có trong đối tượng implement nó.
+ Interface không thể khởi tạo.
+ Interface không phải là một lớp đối tượng .
#### 3. Ưu điểm.
> - stract class
 + Có thể linh động các method. giống như một class thông thường.
 + Các class extend có thể override hoặc không override các method thường.
  > - Interface.
 + Có thể implements nhiều interface(tính đa hình).
 + Xây dựng được bộ khung mẫu mà các lớp phải follow theo.
 + Giúp quản lý tốt, nắm bắt được các chức năng phải có cho một đối tượng nào đó.
### 4. Nhược điểm:
> - Abstract class:
 + Không thể extend nhiều abstract class.
> - Interface:
+ Mỗi khi định nghĩa thêm tính năng, các class impelement nó đồng lọat phải thêm tính năng đó.
#### 5. Tại sao lại sử dụng abstract class và interface.
> - Sử dụng abstract để tránh tình trạng khai báo nhiều lớp mà mỗi lớp có những thuộc tính và phương thức tương tự nhau.
> - Sử dụng interface để giải quyết vấn đề đa kế thừa.
> - Sử dụng abstract class và interface giúp dễ mở rộng ứng dụng cũng như bảo trì code.
### 6. Khi nào sử dụng.
> - Khi một nhóm đối tượng có cùng bản chất kế thừa từ một class thì sử dụng abstract class.
> - Khi một nhóm đối tượng không có cùng bản chất nhưng chúng có hành động giống nhau thì sử dụng interface.
***
## Refecition 6/4/2021
#### 1.Method overriding.
>- Method Overriding (ghi đè phương thức) là cơ chế cho phép lớp con định nghĩa lại các phương thức đã được định nghĩa trước đó ở lớp cha.
>- Phương thức override ở lớp con có cùng tên, cùng danh sách tham số và kiểu dữ liệu trả về so với phương thức ở lớp cha.
>- Phương thức ở lớp con phải có access modifier có level bằng hoặc cao hơn so với phương thức ở lớp cha.
#### 2. method overloading:
>-Nạp chồng (Overloading): Việc khai báo trong một lớp có nhiều thuộc tính, nhiều phương thức có cùng tên nhưng với các tham số khác nhau (khác kiểu dữ liệu,khác số lượng tham số).
***
