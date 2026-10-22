# Cảm Xúc Club — Landing page tuyển thành viên

Website tĩnh HTML/CSS/JavaScript. Không cần npm, API key hay bước build. Bao gồm logo, 5 ảnh và font tiếng Việt lưu trong thư mục assets.

## Đưa lên GitHub và Vercel
1. Giải nén ZIP, tải TOÀN BỘ nội dung bên trong lên repository GitHub. File index.html phải nằm ở thư mục gốc repository, cùng cấp assets và vercel.json.
2. Trong Vercel chọn Add New → Project → Import repository vừa tạo.
3. Framework Preset: Other. Root Directory: ./ (gốc repository). Build Command: để trống. Output Directory: . (dấu chấm). Install Command: để trống.
4. Chọn Deploy. Khi cập nhật file trên GitHub, Vercel có thể tự triển khai lại.

## Xem trên máy
Mở index.html bằng trình duyệt hoặc chạy `python -m http.server 8000` trong thư mục rồi mở http://localhost:8000.

## Font chữ
Playfair Display dùng cho tiêu đề, Dancing Script cho câu nhấn đầu trang, Be Vietnam Pro cho nội dung. Font được lưu ngay trong assets/fonts, không gọi Google Fonts khi khách xem trang. Các tệp giấy phép SIL Open Font License đi kèm trong cùng thư mục.

## Đăng ký thành viên
Biểu mẫu soạn lời nhắn trên thiết bị; không lưu thông tin vào máy chủ. Người dùng sao chép lời nhắn và tự gửi qua https://www.facebook.com/Camxuc.club. Chỉ khi họ gửi tin nhắn thì CLB mới nhận được đăng ký.

## Chỉnh nội dung
Sửa index.html; thay ảnh trong assets và giữ đúng tên hoặc sửa đường dẫn tương ứng. Nội dung dùng UTF-8. Không đổi tên thư mục fonts hoặc xóa các tệp font khi đưa lên GitHub.
