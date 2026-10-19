# Bản dựng Thảo — Một ngày chậm lại

Tải `Thao-ban-rut-gon-60s.zip`, giải nén, mở thư mục dự án.

Bản nháp Remotion dọc 720×1280, 30fps, dài 60,3 giây. Bao gồm tám clip nguồn, chữ nhấn lớn, phụ đề và biểu tượng động. Mỗi clip được dùng một lần.

Cần Node.js 20.19+, 22.13+ hoặc 24+. Trong thư mục đã giải nén, chạy:

```sh
npm ci
npm run dev -- --no-open
```

Mở địa chỉ Remotion in ra và chọn `Thao-MotNgay`.

Đây là dự án chỉnh sửa, chưa phải MP4 thành phẩm. Chưa có giọng nữ AI; âm nguồn đang tắt. Phụ đề dùng thời gian dự kiến, cần căn theo giọng đọc sau khi kết nối ElevenLabs.

Lời đọc rút gọn: `public/loi-doc.txt`. Phụ đề: `public/phu-de-ban-nhap.srt`.
