## HƯỚNG DẪN CÀI ĐẶT
# CẢM BIẾN ĐỘ ẨM
## CHO TRANG TRẠI LAN
1. TỔNG QUAN
Cảm biến độ ẩm giúp theo dõi độ ẩm không khí trong nhà lưới, đảm bảo môi trường tối ưu cho Lan phát triển.
![Cảm biến nhiệt độ độ ẩm phòng  - MTEE.vn](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkoekAcX3TWG9GjH_uRwAEtKbUO0-yymMqfeEF39AxGQ&s=10)




THIẾT BỊ CẦN CHUẨN BỊ
--
- Cảm biến độ ẩm (DHT22 / AM2302)
- Raspberry Pi / Jetson / Soc ![Tìm hiểu về vi mạch điện tử: Khái niệm và ưu - nhược điểm](https://cdn2.fptshop.com.vn/unsafe/1920x0/filters:format(webp):quality(75)/2024_1_24_638417231775199576_vi-mach-dien-tu.jpg)
- Tua vít, băng keo, ốc vít
- Thẻ nhớ đã cài hệ điều hành
  
KÝ HIỆU TRONG TÀI LIỆU
--- 
💬 Văn bản giải thích (đọc và làm theo hướng dẫn)
🧑‍💻Câu lệnh cần gõ vào Terminal (sao chép và dán hoặc gõ chính xác)

❓2. CÁC BƯỚC CÀI ĐẶT
1️⃣ Cập nhật hệ thống 
``` sudo apt update && sudo apt upgrade -y```
2️⃣ Cài đặt thư viện cho cảm biến DHT22

`sudo apt unstall -y git python3-pip 
sudo pip3 install Adafruit_DHT`
3️⃣ Kích hoạt giao tiếp 1-Wire 
`sudo raspi-config`
4️⃣ Kiểm tra module đã nhận được
`ls /sys/bus/w1/devices/`
5️⃣ Chạy thử chương trình đọc cảm biến
`python3 AdafruitDHT.py 22 4`
6️⃣ Tự động chạy khi khởi động
`crontab -e`

📃 3. SƠ ĐỒ KẾT NỐI
DHT22 | Raspberry Pi (BCM)
|-|-
VCC | 3.3V
GND | GND
DATA | GPIO4
NC | (không kết nối)

💬 NHỮNG ĐIỀU BẠN ĐÃ HOÀN THÀNH

 - [X] Bạn đã cài hết theo các bước hướng dẫn chưa.
 - [x] Bạn đã hiểu rõ sơ đồ kết nối chưa.
 - [x] Bạn có hiểu rõ phương thức thực hiện không.

