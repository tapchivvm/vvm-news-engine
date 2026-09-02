VVM NEWS ENGINE — PWA
=======================

Mục tiêu:
- Cài VVM News Engine như một ứng dụng trên iPhone/Android.
- Khi bấm "MỞ HỆ THỐNG", mở hệ thống Google Apps Script hiện tại:
https://script.google.com/macros/s/AKfycbwY5eaU3mxKJPFEgASUWeanrhYRxw2esp44rUFBfc8i5cqFuUQxu1ODQfslHrTkYA/exec

Cách triển khai:
1. Upload toàn bộ các file trong thư mục này lên một nơi HTTPS có hỗ trợ static hosting.
2. Mở index.html bằng HTTPS, không dùng file://.
3. Android: Chrome -> mở trang -> menu -> "Cài đặt ứng dụng" / "Thêm vào màn hình chính".
4. iPhone: Safari -> Chia sẻ -> "Thêm vào Màn hình chính".

Lưu ý:
Đây là lớp PWA truy cập nhanh. Hệ thống AI/Blogger/dữ liệu phía Google Apps Script không bị thay đổi.
