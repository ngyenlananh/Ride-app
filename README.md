**🏥CLINIC AI MANAGER🤖**

**HỆ THỐNG QUẢN LÝ PHÒNG KHÁM THÔNG MINH TÍCH HỢP AI**

**👨‍💻 TRIỂN KHAI BỞI: NHÓM 03 - LỚP N03**

**📍 Trường Đại học Phenikaa**

👥 Thành viên nhóm:

🆔 Nguyễn Thị Lan Anh 

🆔 Dương Kim Chi

🆔 Quang 

**🎯 MỤC TIÊU BÀI THỰC HÀNH SỐ 02**

Dự án tập trung vào việc làm chủ các kỹ thuật xử lý dữ liệu nền tảng trong Flutter & Dart:

**✅ Variables** :  Quản lý biến đa kiểu dữ liệu (String, int, double).

**✅ Collections**: Tổ chức dữ liệu phức tạp bằng List và Map.

**✅ UI Rendering**: Hiển thị dữ liệu từ Collections lên giao diện người dùng bằng các Widget chuyên dụng.

**🛠️ CHI TIẾT KỸ THUẬT TRIỂN KHAI**

**1️⃣ Quản lý biến hệ thống 📋**

Sử dụng các biến để định nghĩa bối cảnh phòng khám và nhân sự:

tenPhongKham: Định danh cơ sở y tế.

tenBacSi & idBacSi: Thông tin định danh bác sĩ trực ca.

chuyenKhoa & phongLamViec: Thông tin vị trí công tác.

**2️⃣ Cấu trúc dữ liệu Collections 🗄️**

Dữ liệu được mô phỏng như một hệ thống thực tế:

thongTinBenhNhan (Map): Lưu trữ thông tin chi tiết: ID, Tên, Tình trạng lâm sàng, Chẩn đoán AI.

listLichKham (List): Danh sách các phiếu chỉ định dịch vụ gồm: Mã phiếu, Tên dịch vụ, Phòng ban, Giờ hẹn.

**3️⃣ Giao diện người dùng (User Interface) 📱**

Dữ liệu được render trực quan thông qua các khối:

Khối hành chính: Sử dụng Container và Decoration để làm nổi bật thông tin bệnh nhân.

Bảng dịch vụ: Sử dụng Row kết hợp Expanded để tạo bố cục cột chuyên nghiệp cho danh sách lịch khám.

**📂 CẤU TRÚC THƯ MỤC DỰ ÁN**

Plaintext

**📂 CLINIC_AI_MANAGER**

 ┣ 📂 lib
 
 ┃ ┗ 📜 main.dart    # 🧩 File thực thi chính (Biến, Dữ liệu, UI)
 ┣ 📂 assets              # 🖼️ Tài nguyên hình ảnh, Icons
 ┣ 📜 pubspec.yaml        # ⚙️ Cấu hình Dependency
 ┗ 📜 README.md           # 📖 Tài liệu hướng dẫn dự án
 
**🚀 HƯỚNG DẪN KHỞI CHẠY**

**Cài đặt các thư viện cần thiết:**

Bash
flutter pub get
Kết nối thiết bị (Máy ảo/Máy thật):

Bash
flutter devices


3. **Chạy ứng dụng:**
   ```bash
   flutter run
   
**📊 KẾT QUẢ ĐẠT ĐƯỢC**

🌟 Giao diện: Trực quan, hiện đại, phân tách rõ ràng các khu vực chức năng.

🌟 Dữ liệu: Quản lý khoa học, dễ dàng mở rộng và bảo trì.

🌟 Tư duy: Áp dụng đúng nguyên tắc lập trình hướng đối tượng cơ bản.

**🔮 HƯỚNG PHÁT TRIỂN TIẾP THEO**

🔄 Model hóa: Chuyển từ Map sang các Class (Model) để quản lý dữ liệu chặt chẽ hơn.

➕ Interaction: Thêm chức năng thêm/xóa bệnh nhân và lịch khám.

🔍 Search Filter: Bộ lọc tìm kiếm bệnh nhân theo ID hoặc Tên.
