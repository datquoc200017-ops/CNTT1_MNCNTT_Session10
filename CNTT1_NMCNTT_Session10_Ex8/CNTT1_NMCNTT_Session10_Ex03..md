# Bài tập về nhà
**Phần 1. Phân tích:** Mô tả sơ đồ cây cấu trúc Heading cho file SRS.
📁 Tài liệu Đặc tả Yêu cầu Hệ thống (SRS) - PTIT-Learning
 ├── 1. Giới thiệu chung (Heading 2)
 ├── 2. Mục đích phạm vi (Heading 2)
 ├── 3. Tổng quan hệ thống (Heading 2)
 ├── 4. Yêu cầu chức năng - Phòng học ảo (Heading 2)
 ├── 5. Yêu cầu chức năng - Quản lý điểm danh (Heading 2)
 ├── 6. Yêu cầu chức năng - Quản lý khóa học (Heading 2)
 ├── 7. Yêu cầu phi chức năng (Heading 2)
 ├── 8. Giao diện người dùng (Heading 2)
 ├── 9. Kịch bản kiểm thử (Heading 2)
 └── 10. Phụ lục và Thuật ngữ (Heading 2)

- Giải pháp xử lý lỗi 
-   **Bước 1:** Chèn một cột phụ trợ trợ giúp (Helper Column) bên cạnh cột bị lỗi (ví dụ: tại cột F, đặt tên là `HoTen_ChuanHoa`).
    
-   **Bước 2:** Sử dụng hàm `TRIM` để loại bỏ toàn bộ khoảng trắng thừa:
    
    Excel
    
    ```
    =TRIM(B2)
    
    ```
    
-   **Bước 3:** Kéo công thức xuống cho toàn bộ 200 dòng dữ liệu.
    
-   **Bước 4:** Copy cột dữ liệu đã chuẩn hóa, sử dụng lệnh **Paste as Values** đè lên cột dữ liệu gốc hoặc tiếp tục sử dụng cột mới để thực hiện AutoFilter đa điều kiện (Khoa = "CNTT" và Điểm chuyên cần < 7) một cách chính xác tuyệt đối.
