## 1.Bốn tính chất của hướng đối tượng.
- Tính đóng gói (Encapsulation) : Là cách để che dấu những tính chất xử lý bên trong của đối tượng, những đối tượng khác không thể tác động trực tiếp làm thay đổi trạng thái mà chỉ có thể tác động thông qua các method public của đối tượng.Để đạt được điều này, bạn phải:
. khai báo các biến / thuộc tính lớp là private 
. cung cấp các phương thức get và set công khai để truy cập và cập nhật giá trị của một private biến.
- Tính kế thừa (Inheritance): là khả năng cho phép ta xây dựng một lớp mới dựa trên các định nghĩa của một lớp đã có. Lớp đã có gọi là lớp Cha, lớp mới phát sinh gọi là lớp Con và đương nhiên kế thừa tất cả các thành phần của lớp Cha, có thể chia sẻ hay mở rộng các đặc tính sẵn có mà không phải tiến hành định nghĩa lại.
- Tính đa hình (polymorphism): Khi một tác vụ được thực hiện theo nhiều cách khác nhau được gọi là tính đa hình. Tính đa hình cung cấp khả năng cho phép người lập trình gọi trước một phương thức của đối tượng, tuy chưa xác định đối tượng có phương thức muốn gọi hay không. Đến khi thực hiện (run-time), chương trình mới xác định được đối tượng và gọi phương thức tương ứng của đối tượng đó. Kết nối trễ giúp chương trình được uyển chuyển hơn, chỉ yêu cầu đối tượng cung cấp đúng phương thức cần thiết là đủ.
- Tính trừu tượng (abstraction): là một tiến trình ẩn các chi tiết trình triển khai và chỉ hiển thị tính năng tới người dùng. Tính trừu tượng cho phép bạn loại bỏ tính chất phức tạp của đối tượng bằng cách chỉ đưa ra các thuộc tính và phương thức cần thiết của đối tượng trong lập trình.Tính trừu tượng giúp bạn tập trung vào những cốt lõi cần thiết của đối tượng thay vì quan tâm đến cách nó thực hiện.

Link bài: https://techtalk.vn/4-tinh-chat-cua-lap-trinh-huong-doi-tuong-trong-java.html 

## 2. Lợi ích của việc sử dụng đối tượng.
- Sử dụng đối tượng để truy cập class mà không làm thay đổi tính chất của oop.
- Dễ quản lý code 
## 3. Khi nào ta sử dụng Abstract class.
- Ta thấy sự trừu tượng hóa của lớp Animal, mọi Animal đều có tiếng kêu, nhưng mỗi lớp kế thừa nó định nghĩa ra một kiểu kêu khác thì 
khi đó ta dùng adstract.Ví dụ ta không thể để thuộc tính bơi hay bay trong abstract class Animal vì 2 thuộc tính này chỉ có ở một số ít loài mà phải tạo ra 2 Interface khác nhau là Can_Fly và Can_Swim rồi xem class nào có thể implements từng cái thích hợp.
## 4.Khi nào ta sử dụng Interface.
- Các class không liên quan với nhau (unrelated classes) khi implement từ interface. Ví dụ, interface Comparable và Cloneable được hiện thực bởi nhiều class không liên quan.
- chỉ quan tâm đến hành động (behavior) của một kiểu dữ liệu nào đó (data type), nhưng lại không cần nhắc đến các hiện thực (implementation) hành động đó như thế nào.
## 5. Override là gì (đưa ra ví dụ).
- Một lớp con kế thừa các phương thức của lớp cha, nhưng nó vẫn có thể định nghĩa lại cách hoạt động của phương thức nào đó, thì đó là ghi đè phương thức.
## 6. Overload là gì (đưa ra ví dụ).
- Nạp chồng phương thức đơn giản là có vài phương thức trùng tên nhưng khác nhau về đối số trong cùng 1 class. Cài chồng phương thức cho phép ta tạo nhiều phiên bản của một phương thức, mỗi phiên bản chấp nhận một danh sách đối số khác nhau, nhằm tạo thuận lợi cho việc gọi phương thức.
## 7.Các access modifier trong java, khi dùng nó thì quyền truy cập sẽ như thế nào.
|Access Modifier|Truy cập bên trong class|Truy cập bên trong package|Truy cập bên ngoài package bởi class con|Truy cập bên ngoài classvà 
|               |                         |                          |                                        |hông thuộc class con|
|-----------------------------------------------------------------------------------------------------------------------------------
|
|
|
|




