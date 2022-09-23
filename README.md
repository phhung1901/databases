# Cơ sở dữ liệu
## DBMS
- **DBMS** là viết tắt của **Database Management System**, có nghĩa là **Hệ quản trị cơ sở dữ liệu**.
- DBMS là phần mềm được thiết kế để có thể xác định, tiến hành các thao tác, truy xuất và quản lý dữ liệu trong Cơ sở dữ liệu.
- Một vài DBMS phổ biến:
  - MySQL 
  - SQL Server
  - Oracle
  - dBASE
  - FoxPro
## SQL
- **SQL** là viết tắt của **Structured Query Language**, có nghĩa là ngôn ngữ truy vấn có cấu trúc được sử 
dụng để giao tiếp với cơ sở dữ liệu.
- Nó là ngôn ngữ tiêu chuẩn cho các hệ quản trị cơ sở dữ liệu quan hệ.
- Các lệnh SQL tiêu chuẩn để tương tác với cơ sở dữ liệu quan hệ là CREATE, SELECT, INSERT, UPDATE, DELETE và DROP. Các lệnh này có thể được phân thành các nhóm sau dựa trên bản chất của chúng.

*DDL – Ngôn ngữ định nghĩa dữ liệu (Data Definition Language)* bao gồm các lệnh SQL có thể được sử dụng để xác định lược đồ cơ sở dữ liệu.
![](./img/DDL.png)

*DML – Ngôn ngữ thao tác dữ liệu(Data Manipulation Language)* 
![](./img/DML.png)

*DCL – Ngôn ngữ điều khiển dữ liệu (Data Control Language)* bao gồm các lệnh như GRANT và REVOKE chủ yếu giải quyết các quyền, quyền hạn và các điều khiển khác của hệ thống cơ sở dữ liệu. 

## NoSQL DATABASES
### Định nghĩa
- Cơ sở dữ liệu NoSQL là một Hệ thống quản lý dữ liệu không quan hệ (non-relational Data Management System) có lược đồ (schema) linh hoạt.
- Thuật ngữ NoSQL đánh dấu bước phát triển của thế hệ database mới: distributed (phân tán) + non-relational (không ràng buộc). Đây là 2 đặc tính quan trọng nhất.
#### Đặc điểm
- Nó dễ mở rộng. Mục đích chính của việc sử dụng cơ sở dữ liệu NoSQL là dành cho các kho dữ liệu phân tán với nhu cầu lưu trữ dữ liệu lớn. 
- NoSQL được sử dụng cho Dữ liệu lớn (Big Data) và ứng dụng web thời gian thực.

![](./img/SQL-RDBMS-vs-NoSQL-DBMS.png.webp)

### Đặc điểm chung
- High Scalability: Gần như không có một giới hạn cho dữ liệu và người dùng trên hệ thống.
- High Availability: Do chấp nhận sự trùng lặp trong lưu trữ nên nếu một node (commodity machine) nào đó bị chết cũng không ảnh hưởng tới toàn bộ hệ thống.
- Consistency: chấp nhận tính nhất quán yếu, có thể không thấy ngay được sự thay đổi mặc dù đã cập nhật dữ liệu.
- Durability: dữ liệu có thể tồn tại trong bộ nhớ máy tính nhưng đồng thời cũng được lưu trữ lại đĩa cứng.
- Deployment Flexibility: việc bổ sung thêm/loại bỏ các node, hệ thống sẽ tự động nhận biết để lưu trữ mà không cần phải can thiệp bằng tay. Hệ thống cũng không đòi hỏi cấu hình phần cứng mạnh, đồng nhất.

### Phân loại 

-  Key - Value:
   - Dữ liệu được lưu trữ trong các cặp khóa / giá trị (Key/Value Pair).
   - Nó được thiết kế theo cách để xử lý nhiều dữ liệu và tải nặng.
   ![](https://itguru.vn/blog/wp-content/uploads/2020/12/Key-value-Pair-2.jpg.webp)
   - 