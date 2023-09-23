# Node.js_design_pattern
##  [Node.js_design_pattern](https://stackoverflow.com/questions/32510232/node-js-design-pattern) <br><br>
**Design Pattern** là các giải pháp tổng quát và có thể tái sử dụng cho các vấn đề phổ biến trong thiết kế phần mềm. Chúng được thiết kế để giúp lập trình viên tạo ra các phần mềm chất lượng cao, dễ bảo trì và mở rộng.
**Design Pattern** không phải là các giải pháp hoàn chỉnh, mà là các mô hình hoặc khuôn mẫu giải quyết một vấn đề cụ thể. Chúng có thể được áp dụng cho nhiều ngôn ngữ lập trình khác nhau.

Có nhiều loại **Design Pattern** khác nhau, được phân loại theo mục đích của chúng. Một số loại **Design Pattern** phổ biến bao gồm:
![image](https://github.com/Experimenters1/Node.js_design_pattern/assets/64000769/1e2551fe-e8f3-454c-bf40-97a8ca0e8771) <br><br>
+) **Creational Patterns:**  Các Design Pattern này giải quyết vấn đề tạo ra các đối tượng. <br><br>
+) **Structural Patterns:** Các Design Pattern này giải quyết vấn đề kết nối các đối tượng với nhau. <br><br>
+) **Behavioral Patterns:** Các Design Pattern này giải quyết vấn đề giao tiếp và tương tác giữa các đối tượng. <br><br>

**Khi nào nên sử dụng Design Pattern?** <br><br>

Design Pattern có thể được sử dụng trong nhiều tình huống khác nhau. Tuy nhiên, chúng đặc biệt hữu ích trong các trường hợp sau: <br><br>

+) Khi bạn gặp phải một vấn đề thiết kế phổ biến. <br><br>

+) Khi bạn muốn tạo ra một phần mềm dễ bảo trì và mở rộng. <br><br>

+) Khi bạn muốn cải thiện chất lượng phần mềm của mình. <br><br>

**Các Design Pattern phổ biến** <br><br>

Dưới đây là một số Design Pattern phổ biến: <br><br>

![image](https://github.com/Experimenters1/Node.js_design_pattern/assets/64000769/428e0b19-5158-4cd3-945f-55db450fed50) <br><br>
+) **Singleton Pattern:** Giúp đảm bảo rằng chỉ có một thể hiện duy nhất của một lớp trong một ứng dụng. <br><br>
+) **Factory Pattern:** Giúp tạo ra các đối tượng mà không cần tiết lộ thông tin về cách chúng được tạo ra. <br><br>
+) **Adapter Pattern:** Cho phép hai đối tượng với các giao diện không tương thích giao tiếp với nhau. <br><br>
+) **Decorator Pattern:** Cho phép thêm các chức năng bổ sung cho một đối tượng mà không cần thay đổi mã của đối tượng đó. <br><br>
+) **Observer Pattern:** Cho phép các đối tượng đăng ký để nhận thông báo từ các đối tượng khác. <br><br>
+) **Command Pattern:** Giúp tách rời các đối tượng thực hiện một hành động khỏi các đối tượng yêu cầu hành động đó được thực hiện. <br><br>
+) **Iterator Pattern:** Cho phép duyệt qua một tập hợp các đối tượng mà không cần biết cấu trúc cụ thể của tập hợp đó.<br><br>
+) **Composite Pattern:** Cho phép tạo các cấu trúc cây từ các đối tượng có thể là đơn giản hoặc phức tạp.

![image](https://github.com/Experimenters1/Node.js_design_pattern/assets/64000769/5e9531bc-a778-407c-97b4-61eacdd49d3b) <br><br>

**MVC** là một **Structural Design Pattern**, được sử dụng để tách rời các thành phần của một ứng dụng phần mềm thành ba phần: <br><br>
+) **Model:** Chứa dữ liệu và logic nghiệp vụ của ứng dụng. <br><br>
+) **View:** Hiển thị dữ liệu cho người dùng. <br><br>
+) **Controller:** Điều khiển giao diện giữa người dùng và ứng dụng. <br><br>

MVC có thể được áp dụng cho nhiều ngôn ngữ lập trình và nền tảng khác nhau. Nó là một mô hình kiến trúc phổ biến cho các ứng dụng web, nhưng cũng có thể được sử dụng cho các ứng dụng không dựa trên web.<br><br>

**Vị trí của MVC trong Design Pattern**<br><br>
**MVC** là một **Design Pattern** ở cấp độ kiến trúc, vì nó xác định cách các thành phần của một ứng dụng được tổ chức. Nó không giải quyết các vấn đề cụ thể trong việc tạo ra các đối tượng, kết nối các đối tượng với nhau hoặc giao tiếp và tương tác giữa các đối tượng.<br><br>
**MVC** thường được sử dụng kết hợp với các **Design Pattern** khác, chẳng hạn như:<br><br>
+) **Factory Pattern:** Để tạo ra các đối tượng **Model**.<br><br>
+) **Adapter Pattern:** Để kết nối các View với các **Model**.<br><br>
+) **Command Pattern:** Để điều khiển các hành động của **Model** từ **View**.<br><br>

**Strategy Pattern** là một **Design Pattern**, thuộc nhóm **Behavioral Pattern**. Nó được sử dụng để định nghĩa một tập hợp các thuật toán, đóng gói từng thuật toán lại và dễ dàng thay đổi linh hoạt các thuật toán bên trong **object**. **Strategy** cho phép thuật toán biến đổi độc lập khi người dùng sử dụng chúng.<br><br>
![Screenshot 2023-09-23 at 2 09 46 PM](https://github.com/Experimenters1/Node.js_design_pattern/assets/64000769/cdc4594e-778d-4663-993b-b91267aac4ed)<br><br>

**Repository storage pattern trong Node.js thường được sử dụng kết hợp với một database, chẳng hạn như MongoDB, PostgreSQL hoặc MySQL. Lớp Repository sẽ cung cấp các phương thức để tạo, đọc, cập nhật và xóa dữ liệu từ database.**

