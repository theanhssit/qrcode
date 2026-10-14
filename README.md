# Qrio — Trình tạo mã QR miễn phí

Trang web tạo mã QR tĩnh, giao diện tiếng Việt, tương thích điện thoại và máy tính. Mã QR được tạo ngay trên trình duyệt; nội dung người dùng nhập không được gửi lên máy chủ.

## Tính năng

- Tạo QR cho liên kết, văn bản, Wi-Fi, email và số điện thoại.
- Đổi màu mã và màu nền, xuất ảnh PNG ở kích thước 256, 512 hoặc 1024 px.
- Bố cục responsive, không cần tài khoản hoặc backend.
- Có thể chạy trực tiếp bằng GitHub Pages.

## Chạy trên máy

Mở `index.html` trong trình duyệt. Trang tải thư viện QRCode.js từ CDN, vì vậy cần kết nối Internet để tạo mã.

## Đưa lên GitHub Pages

1. Tạo repository và tải các tệp trong thư mục này lên nhánh `main`.
2. Vào **Settings → Pages**.
3. Trong **Build and deployment**, chọn **Deploy from a branch**, chọn nhánh `main` và thư mục `/(root)`, rồi lưu.
4. Đợi GitHub Pages triển khai và mở URL được hiển thị tại trang Pages.

## Công nghệ

HTML, CSS và JavaScript thuần; [QRCode.js](https://github.com/davidshimjs/qrcodejs) được tải từ cdnjs.
