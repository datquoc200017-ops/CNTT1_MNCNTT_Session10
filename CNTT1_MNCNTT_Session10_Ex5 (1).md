# Bài Tập Về Nhà 

### Phần 1. Phân tích cốt lõi

-   **2 sai lầm của Nam:**
    
    1.  _Hiểu sai định dạng:_ File `.docx` là file nhị phân nén ZIPnhiều XML, GitHub không thể đọc và hiển thị nội dung trực tiếp trên web.
        
    2.  _Hiểu sai cơ chế Git:_ Git theo dõi thay đổi theo từng dòng văn bản đổi 1 dấu phẩy trong Word làm xáo trộn toàn bộ mã nhị phân, khiến Git báo toàn bộ file.
        
-   **Markdown an toàn & nhẹ hơn:**
    
    -   _Chống hư hại:_ File `.docx` mất 1 byte sẽ hỏng toàn bộ cấu trúc nén không mở được. File `.md` (Plain Text) mất 1 byte chỉ mất đúng ký tự đó, phần còn lại vẫn nguyên vẹn.
        
    -   _Dung lượng:_ Markdown chỉ vài KB vì chỉ chứa ký tự chữ thuần, không gánh XML và định dạng ẩn.
        

### Phần 2. Nội dung `README.md` (chuyển đổi từ Word)

Markdown

```
# 🌿 GreenTech: Nông Nghiệp Thông Minh IoT

> **GreenTech** là hệ thống tự động hóa vi khí hậu và giám sát môi trường vườn thông minh theo thời gian thực.

## 🎯 Mục Tiêu
- [x] Giảm 40% lượng nước tưới bằng cảm biến độ ẩm.
- [x] Tự động cảnh báo và điều hòa khi cây bị sốc nhiệt.

## 👥 Thành Viên
* **Phạm Quốc Đạt:** Quản lý tài liệu & Phần cứng IoT.
* **Nhóm phát triển:** Lập trình vi điều khiển & Giao diện Dashbo
```
