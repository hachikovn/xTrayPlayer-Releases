# xTrayPlayer v1.1.6 — Có gì mới

## Tải video, audio và phụ đề YouTube

- Cửa sổ tải hiển thị các lựa chọn **Video**, **Audio** và **Phụ đề / transcript** lấy trực tiếp từ video.
- Chọn độc lập Video và Audio để **Tải riêng** nhiều file hoặc **Ghép video + audio** khi FFmpeg sẵn sàng.
- Danh sách tải hiển thị trước các file sẽ tạo; hỗ trợ tiến trình riêng cho các luồng tải song song.
- Tên file theo quy tắc **Tiêu đề – YouTube media ID – Quality**.

## Tải nhanh trong trình duyệt YouTube

- Khi rê chuột lên video đang phát, nút **Tải về** xuất hiện ngay trên trình phát.
- Menu có mục đầu tiên **Chất lượng tốt nhất (video quality, audio quality)**, sau đó là các lựa chọn Video, Audio và phụ đề cụ thể.
- Có thể mở cửa sổ tải đầy đủ từ nút trên trình duyệt, Menu nhanh Widget hoặc menu tray icon.

## Visualizer Taskbar không chặn thao tác

- Củng cố native click-through để overlay visualizer không trở thành mục tiêu chuột của Widget/Taskbar.
- Không kích hoạt cửa sổ khi nhận thao tác chuột; tự áp lại style sau khi reposition, đổi z-order hoặc đổi màn hình.
- Ẩn hoàn toàn visualizer khi không có tín hiệu thay vì chỉ đặt opacity về 0.

## Đóng gói

- Setup và Portable đều là bản Windows x64 self-contained, đã kèm .NET 9 runtime và native TaskbarTap DLL.
- Microsoft Edge WebView2 Runtime vẫn cần có để dùng YouTube và PiP; Setup có tùy chọn mở liên kết tải chính thức.
