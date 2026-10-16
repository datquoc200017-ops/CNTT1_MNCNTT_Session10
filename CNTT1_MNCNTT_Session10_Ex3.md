# Bài Tập Về Nhà 
## Phần 1. Phân tích bài toán: Markdown giúp AI xử lý nhanh hơn như thế nào?
1. Cơ chế chia nhỏ Token trong LLM
- Các mô hình AI ngôn ngữ lớn như GPT, Claude, Genimi bình thường không đọc văn bản theo thứ tự mà dùng bộ mã hóa token
- Token thường có thể là một từ hoặc phần tử hay kí tự vân...vân..
2.  VD về các AI đọc Token
- Một từ in đậm **Rikkeisoft**
-  Bộ token thường chỉ mất 1-2 token cho dấu *
3. Tác động đến chi phí và tốc độ xử lý
- Tốc độ phản hồi: Thời gian AI cho ra văn bản tỉ lệ thuận với số lượng token, ít token hơn giúp giảm thời  gian cho ra văn bản nhanh hơn.
- Chí phí API: Nhà cung cấp tính tiền trên mỗi 1000 token. Cắt giảm token giúp cú pháp hệ thông tiết kiệm chi phí cho nội dung.
## Phần 2. So sánh, Đánh giá & Giải pháp cho hệ thống GreenTech
1. Bảng so sánh Markdown và HTML

Tiêu chí | Markdown | HTML
|-|:-:|:-:|
Số lượng ký tự | Tối giản, dùng ký tự dễ hiểu (**,#,-..). |Rườm rà yêu cầu thẻ mở đóng.
Tiêu tốn Token của AI | Thấp, tiết kiệm | Cao 
Tính độ hiểu của người đọc | Rất cao | Kém
Khả năng hiển thị đa nền tảng | Ít lỗi cú pháp | Cần web-viewcode | 
2. Đề xuất giải pháp tối ưu cho hệ thống **GreenTech**
Hệ thống nên yêu cầu AI sinh dữ liệu hoàn toàn dưới dạng **Markdown** và thiết bị của người dùng tự render giao diện.
1️⃣Thân thiện với người nông dân.
2️⃣Tiết kiệm chi phí vận hành. 
3️⃣Tối ưu hóa độ trễ trên mạng di động 4G/5G.
4️⃣An toàn bảo mật. 
