# luxury-garage

#  Luxury Garage - Website Thương Mại Điện Tử Bán Siêu Xe

Luxury Garage là dự án website thương mại điện tử chuyên cung cấp thông tin và hỗ trợ đặt cọc các dòng siêu xe cao cấp trực tuyến. Hệ thống được thiết kế với giao diện mang phong cách sang trọng, hiện đại, sử dụng tông màu tối (đen/đỏ) làm chủ đạo nhằm tối ưu trải nghiệm người dùng (UI/UX).

## 🛠️ Công nghệ sử dụng

* **Frontend:** HTML, CSS, JavaScript.
* **Backend & Database:** Java (JSP/Servlets), JDBC, MySQL (cho phiên bản đầy đủ chức năng).
* **Kiến trúc:** Mô hình MVC (Model - View - Controller).

## Hướng dẫn xem trực tiếp dự án

Để thuận tiện cho quá trình đánh giá, dự án được đóng gói thành 2 phiên bản. Bạn có thể lựa chọn 1 trong 2 cách dưới đây để trải nghiệm:
### Cách 1: Xem giao diện tĩnh (Thuần Frontend - Đề xuất)
Phiên bản này dành riêng cho việc đánh giá thiết kế giao diện (UI/UX), cấu trúc HTML/CSS và các tương tác JavaScript phía client mà không cần cài đặt môi trường Backend phức tạp.
1. Tải file `LuxuryGarage_UI_HTML.rar`.
2. Giải nén thư mục.
3. Click đúp vào file `index.html` (hoặc kéo thả vào bất kỳ trình duyệt web nào như Chrome, Edge, Cốc Cốc).
4. Bạn có thể điều hướng trực tiếp để xem toàn bộ các giao diện: Trang chủ, Giới thiệu, Danh sách sản phẩm, Chi tiết xe, Giỏ hàng, Đăng nhập/Đăng ký và Trang quản trị (Admin).


### Cách 2: Chạy đầy đủ chức năng hệ thống (Fullstack)
Phiên bản này bao gồm toàn bộ mã nguồn Frontend, Backend và Cơ sở dữ liệu, cho phép trải nghiệm các luồng nghiệp vụ thực tế như: thêm vào giỏ hàng, đặt cọc xe, và quản lý CRUD trong trang Admin.
**Yêu cầu hệ thống:**
* Phần mềm quản lý CSDL: XAMPP hoặc MySQL Workbench.
* Máy chủ web (Web Server): Apache Tomcat.
* IDE: Eclipse hoặc IntelliJ IDEA.
**Các bước cài đặt:**

1. Tải file nén `LuxuryGarage_FullSource.war` và giải nén.
2. Mở IDE (Eclipse), chọn **File > Import > Web > WAR file** và trỏ đến thư mục mã nguồn.
3. Cấu hình lại thông tin kết nối Database trong file `DBConnect.java` (username/password) nếu cần.
4. Chạy dự án (Run on Server) bằng Apache Tomcat và truy cập qua đường dẫn Localhost trên trình duyệt.

## 👤 Vai trò trong dự án
Nhóm trưởng
* Thiết kế toàn bộ UI/UX, lập trình cấu trúc HTML/CSS và xử lý tương tác giao diện.
* Đảm bảo tính đáp ứng (Responsive Design), giúp website hiển thị tốt trên các thiết bị di động và máy tính.
* Tích hợp mã nguồn Frontend với hệ thống Backend Java.
