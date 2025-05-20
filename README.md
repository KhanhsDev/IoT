Ứng dụng Giám Sát & Điều Khiển IoT


👨‍💻 Nhóm thực hiện

Bùi Văn Khánh

Trần Nam Khánh

Lương Hoàng Nam

📌 Tính năng chính

Giám sát nhiệt độ và độ ẩm từ cảm biến.

Điều khiển bật/tắt LED thông qua app.

Lưu và hiển thị dữ liệu thời gian thực lên Firebase Realtime Database.

Ứng dụng Android giao diện trực quan dễ sử dụng.

📸 Hình ảnh minh họa


![anh 1](https://github.com/user-attachments/assets/d9b2fbb4-aa5b-4188-a330-d41479b7ca13)

📌 Ảnh code :


![anh 3](https://github.com/user-attachments/assets/af78d55b-b0a6-4854-bc96-6acbd69ecf73)

![anh 2](https://github.com/user-attachments/assets/70604273-d64f-413d-8c61-9839d2f4ae76)

📌 Ảnh thiết kế app : 


![anh 5](https://github.com/user-attachments/assets/2ef50310-6e35-4a9a-991b-f0214eeec5f9)


![anh 4](https://github.com/user-attachments/assets/52295c9b-c035-41c4-8232-17ff339be1df)

📌 Ảnh thực tế :


![anh 6](https://github.com/user-attachments/assets/85d45fb3-c940-467e-9ef4-f8cd283cfde9)

📌 Video demo :


https://github.com/user-attachments/assets/467709d8-a422-45e1-987d-9e66afbcfee7

🛠️ Hướng dẫn cài đặt:

📌 1. Cài đặt Arduino IDE

Tải và cài Arduino IDE từ: https://www.arduino.cc/en/software

📌 2. Thêm board ESP32 cho Arduino IDE:

Vào File > Preferences

Tại Additional Board Manager URLs dán: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

Vào Tools > Board > Boards Manager

Tìm ESP32 và cài đặt


📌 3. Cài đặt thư viện:


Firebase ESP Client

DHT sensor library

Cài trực tiếp trong Tools > Manage Libraries


📌 4. Kết nối Firebase:

Tạo Realtime Database trên Firebase Console

Lấy Database URL và Secret key để khai báo vào code Arduino

📌 5. Làm App bằng Mit App Inventor:


Vào https://ai2.appinventor.mit.edu/

Import file thiết kế blocks hoặc làm theo demo ảnh Blocks.png

Kết nối API Firebase và control thiết bị

📥 Clone project từ GitHub:

https://github.com/KhanhsDev/IoT.git




