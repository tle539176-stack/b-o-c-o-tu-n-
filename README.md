# Web báo cáo tuần kênh Bác sĩ Phúc

Đây là static site dùng một lần cho báo cáo giai đoạn 18 tháng 4 - 24 tháng 4.

## Cách xem local

Mở trực tiếp file:

```text
index.html
```

Không cần Node.js, npm, backend hay database.

## Cách deploy Vercel

Cách đơn giản nhất:

1. Đẩy thư mục `web-bao-cao` lên GitHub.
2. Import repository vào Vercel.
3. Khi Vercel hỏi framework, chọn `Other` hoặc để Vercel tự nhận static site.
4. Build command để trống.
5. Output directory để trống hoặc dùng mặc định.

Các file chính:
- `index.html`: nội dung và cấu trúc báo cáo.
- `styles.css`: giao diện responsive.
- `vercel.json`: cấu hình URL sạch cho static site.
