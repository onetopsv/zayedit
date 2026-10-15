# ZayEdit Studio — web prototype

## Chạy thử
- Giải nén thư mục.
- Mở `index.html` bằng Chrome/Edge hoặc triển khai thư mục lên GitHub + Vercel.
- Để cài như PWA, dùng HTTPS (Vercel cung cấp HTTPS).

## Đã có trong prototype
- Nhập video/ảnh/âm thanh, thêm chữ và sticker dạng chữ.
- Timeline nhiều lớp, chọn clip, tách clip, sao chép, xóa, thay media.
- Điều chỉnh vị trí, kích thước, xoay, opacity, bộ lọc, sáng/bão hòa, tốc độ, animation preset.
- Keyframe cho X/Y/scale/rotation/opacity, nội suy linear/ease/ease-in/ease-out và đồ thị đường cong.
- Mặt nạ tròn/chữ nhật cơ bản, xuất WebM từ canvas nếu trình duyệt hỗ trợ.

## Giới hạn cần biết
Đây là prototype web, chưa phải trình dựng chuyên nghiệp hoàn chỉnh. Xuất WebM hiện ghi lại canvas; âm thanh chưa được trộn vào bản xuất. Chroma key trong giao diện chưa có xử lý pixel hoàn chỉnh. Dự án JSON hiện lưu metadata chứ không nhúng file media và chưa tự relink media khi mở. Tính năng xóa nền AI không có; chroma key phù hợp với phông màu đồng nhất. Để phát hành nghiêm túc cần hoàn thiện render pipeline, xử lý âm thanh, chroma key, kéo thả timeline, lưu/khôi phục media và kiểm thử thiết bị.
