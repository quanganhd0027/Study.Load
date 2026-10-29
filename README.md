# StudyLoad

Ứng dụng quản lý học tập cho học sinh, giáo viên và Admin. Bản demo chạy hoàn toàn trên trình duyệt.

## Cấu trúc
- `index.html`: khung trang
- `styles.css`: giao diện
- `app.js`: toàn bộ logic

## Chạy thử
Mở `index.html` hoặc chạy `python -m http.server 8000` rồi vào http://localhost:8000

## Triển khai Vercel
Đẩy cả thư mục lên GitHub, import vào Vercel, Framework Preset chọn **Other**, không cần lệnh build.

## Lưu ý bảo mật
Dữ liệu, tài khoản và phân quyền lưu trong localStorage của trình duyệt, không đồng bộ giữa các máy và không an toàn cho dữ liệu thật. Muốn dùng thật cần backend (ví dụ Supabase) với xác thực, phân quyền và RLS phía máy chủ.

Admin dự kiến: `quanganhd2011@gmail.com` (lần đầu đăng nhập sẽ đặt mật khẩu, tối thiểu 8 ký tự).
