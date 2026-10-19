# xTrayPlayer v1.1.8 — Nhớ tiến độ YouTube

## Tiếp tục clip đang xem dở

- Tự lưu tiến độ theo ID video YouTube. Mở lại từ YouTube Browser, Playlist hoặc Lịch sử sẽ tiếp tục ở mốc đã xem, kể cả sau khi thoát app hoặc khởi động lại máy.
- Các URL của cùng video (watch, youtu.be, Shorts và YouTube Music) dùng chung tiến độ; không phụ thuộc việc đăng nhập Google.
- Lưu định kỳ khoảng 5 giây, khi pause, tua và chuyển clip; ghi nốt dữ liệu đã nhận khi thoát app hoặc Windows kết thúc phiên.

## Thông báo tiếp tục xem khi mở lại app

- Hiện tiêu đề và mốc đã xem của clip cuối còn xem dở, với hai nút **Tiếp tục / Để sau**.
- Không tự phát và không giành focus. Thông báo chỉ dành cho lần mở lại app, không xuất hiện mỗi lần chuyển clip trong cùng phiên.
- Tùy chọn **Thông báo tiếp tục xem clip khi mở lại app** nằm trong **Cài đặt → YouTube**, mặc định bật. Tắt thông báo vẫn giữ chức năng nhớ tiến độ; cũng có thể tắt ngay trên thông báo.

## Kiểm soát phát lại

- Thêm **Phát lại từ đầu** vào menu chuột phải của YouTube Browser và các bài YouTube trong Playlist.
- Ưu tiên mốc thời gian rõ ràng trong URL, kể cả `t=0`; video đã xem hết hoặc gần hết được phát lại từ đầu.
- Chờ đúng video có metadata/vùng tua hợp lệ rồi mới khôi phục một lần; không gọi play khi tua về mốc đã lưu, nên không làm clip đang pause tự phát.
- Bỏ qua quảng cáo/livestream; tránh ghi đè tiến độ bằng thời gian 0 do tải hoặc dừng và tránh lưu nhầm giữa các clip khi YouTube chuyển trang.
- Kế thừa các bản sửa PiP 1.1.7: đóng PiP giữ đúng trạng thái pause/play và tiếp tục âm thanh liền mạch.

## Lưu ý dữ liệu

- Tiến độ bắt đầu được ghi từ **v1.1.8**; không tái tạo được các mốc mà phiên bản cũ chưa lưu.
- Dữ liệu nằm cục bộ trên máy, tối đa 1.000 video gần nhất; không đồng bộ với Chrome, điện thoại hoặc tài khoản Google.
- Nếu tiến trình bị tắt đột ngột, có thể mất vài giây cuối. Clip xem quá ngắn (dưới 3 giây) không được đề xuất trong thông báo khởi động.
- Tính năng dành cho YouTube; cơ chế phát file cục bộ không thay đổi.

## Đóng gói

- **Setup** và **Portable ZIP** dành cho Windows 10/11 x64, self-contained, kèm **.NET 9 runtime**, native **TaskbarTap DLL**, WebView2 bindings và tài nguyên uBlock Origin.
- **Microsoft Edge WebView2 Runtime** vẫn cần được cài trên máy để dùng YouTube/PiP. Setup có tùy chọn mở liên kết tải chính thức từ Microsoft.

