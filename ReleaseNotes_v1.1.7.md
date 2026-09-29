# xTrayPlayer v1.1.7 — PiP phát liên tục

## Đóng YouTube PiP đúng trạng thái phát

- Khi video đang **tạm dừng**, bấm nút **X** để ẩn PiP không còn làm video tự phát lại.
- Khi video đang **phát**, bấm nút **X** sẽ đóng PiP mà vẫn giữ âm thanh phát liên tục, không có khoảng khựng do lệnh pause rồi phát lại.
- Việc nhận diện nút X được giới hạn cho cửa sổ PiP của chính xTrayPlayer, không can thiệp PiP của ứng dụng WebView2 khác.

## Đóng gói

- Setup và Portable là bản Windows x64 self-contained, đã kèm .NET 9 runtime và native TaskbarTap DLL.
- Microsoft Edge WebView2 Runtime vẫn cần có để dùng YouTube và PiP; Setup có tùy chọn mở liên kết tải chính thức.
