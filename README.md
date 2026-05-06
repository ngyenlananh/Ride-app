🏥 CLINIC AI MANAGER - PHẦN MỀM QUẢN LÝ PHÒNG KHÁM THÔNG MINH
1. Tổng quan dự án
CLINIC AI MANAGER là hệ thống quản lý phòng khám tích hợp trí tuệ nhân tạo, giúp tối ưu hóa quy trình tiếp đón bệnh nhân, sắp xếp lịch khám và hỗ trợ chẩn đoán. Dự án được thực hiện bởi Nhóm 03 lớp N03 - Đại học Phenikaa.

2. Thông tin nhóm thực hiện
Lớp: N03 - Trường Đại học Phenikaa.

Nhóm: 03.

Thành viên:

Nguyễn Thị Lan Anh (Trưởng nhóm - SV ngành Công nghệ thông tin).

Dương Kim Chi.

Quang.

3. Mục tiêu bài thực hành số 02
Trọng tâm của giai đoạn này là xây dựng nền tảng dữ liệu tĩnh và giao diện hiển thị cơ bản trong Flutter:

Quản lý biến: Khai báo và sử dụng các kiểu dữ liệu cơ bản trong main.dart.

Cấu trúc dữ liệu: Sử dụng Collections (List, Map) để tổ chức dữ liệu bệnh nhân và lịch khám.

Xây dựng giao diện (UI): Hiển thị dữ liệu từ Collections lên màn hình ứng dụng thông qua các Flutter Widgets như Column, Row, Container, và Text.

4. Chi tiết kỹ thuật triển khai
4.1. Khai báo biến (Variables)
Hệ thống sử dụng các biến định danh cơ bản để mô tả ngữ cảnh phòng khám:

tenPhongKham: Tên đơn vị quản lý.

nhomThucHien: Thông tin nhóm phát triển.

idBacSi, tenBacSi, chuyenKhoa: Thông tin định danh nhân sự trực ca.

4.2. Quản lý dữ liệu bằng Collections
Dữ liệu được tổ chức để mô phỏng thực tế hoạt động của phòng khám:

Map thongTinBenhNhan: Chứa thông tin chi tiết của một bệnh nhân đang được xử lý (id, tên, tình trạng lâm sàng, và kết quả chẩn đoán từ AI).

List listLichKham: Danh sách các phiếu hẹn/dịch vụ khám bệnh bao gồm các trường dữ liệu: mã phiếu, tên dịch vụ (xét nghiệm, siêu âm...), số lượng, phòng ban và giờ hẹn.

4.3. Cấu trúc giao diện trong hàm build
Giao diện được thiết kế khoa học với hai khối dữ liệu chính:

Khối thông tin bệnh nhân: Sử dụng Container với BoxDecoration để tạo khung nổi bật, thông tin hiển thị qua các Row chứa Icon và Text.

Khối danh sách lịch khám: Sử dụng ListView hoặc vòng lặp để render các dòng dữ liệu. Mỗi dòng là một Row chia theo tỷ lệ (dùng Expanded) để tạo thành bảng dữ liệu chuyên nghiệp.

5. Cấu trúc thư mục dự án
Plaintext
CLINIC_AI_MANAGER/
├── lib/
│   └── main.dart        # File chính chứa biến, dữ liệu và UI bài 2
├── assets/              # Hình ảnh và logo phòng khám (nếu có)
├── pubspec.yaml         # Quản lý dependency Flutter
└── README.md            # Tài liệu hướng dẫn dự án
6. Hướng dẫn cài đặt và khởi chạy
Để chạy dự án này trên máy địa phương hoặc trình giả lập, thực hiện các bước sau:

Bước 1: Cài đặt các gói phụ thuộc

Bash
flutter pub get
Bước 2: Kiểm tra kết nối thiết bị

Bash
flutter devices
Bước 3: Chạy ứng dụng

Bash
flutter run
7. Đánh giá kết quả đạt được
✅ Hoàn thành khai báo và sử dụng biến đa kiểu dữ liệu (String, int).

✅ Xây dựng thành công bộ dữ liệu mẫu bằng List và Map.

✅ Giao diện hiển thị trực quan, phân tách rõ ràng giữa thông tin hành chính và danh mục chuyên môn.

✅ Tuân thủ các nguyên tắc thiết kế UI hiện đại (sử dụng màu sắc hài hòa, bố cục cân đối).
