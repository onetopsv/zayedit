# ZayEdit — Mobile Video Editor Prototype

## Mở thử
- Mở `index.html` trong trình duyệt để xem bản demo.
- Để cài như một web app (PWA), tải các file lên dịch vụ hosting tĩnh có HTTPS rồi mở đường link trên điện thoại.
- Android/Chrome: menu ⋮ → **Cài đặt ứng dụng** hoặc **Thêm vào màn hình chính**.
- iPhone/Safari: nút Chia sẻ → **Thêm vào MH chính**.

## Bao gồm
- Giao diện ưu tiên điện thoại.
- Thêm video/ảnh, xem trước clip, timeline cơ bản.
- Overlay chữ/sticker, filter preview, chỉnh sáng/tương phản/bão hòa, tốc độ preview.
- Chọn file âm thanh (prototype chưa trộn nhạc vào video xuất).
- Lưu metadata dự án JSON và thử xuất WebM nếu trình duyệt hỗ trợ.
- PWA manifest, icon và service worker để hỗ trợ cài lên màn hình chính/offline shell.

## Giới hạn hiện tại
Đây là prototype, chưa phải trình thay thế CapCut hoàn chỉnh. Chia clip thực sự, timeline đa lớp có render, trộn âm thanh, xuất MP4/H.264, phụ đề tự động và AI cần phát triển thêm. Service worker/PWA cần chạy qua HTTPS hoặc localhost; mở file trực tiếp không kích hoạt cài đặt PWA.

## Đưa lên mạng
Có thể triển khai thư mục này lên GitHub Pages, Netlify, Vercel hoặc hosting static tương tự. Mình chưa tự xuất bản được một URL công khai từ phiên này, nên gói này là mã nguồn sẵn để triển khai.
