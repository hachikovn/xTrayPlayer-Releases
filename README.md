# 🎵 xTrayPlayer Releases

Kho lưu trữ các bản phát hành chính thức của **xTrayPlayer** — trình phát nhạc, YouTube và Taskbar Widget cho Windows 10/11.

## 📦 Phiên bản mới nhất: v1.1.4

| Gói | Định dạng | Tải xuống |
| :--- | :--- | :--- |
| **Bản cài đặt (Setup)** | `.exe` | [xTrayPlayer_Setup_v1.1.4.exe](https://github.com/hachikovn/xTrayPlayer-Releases/releases/download/v1.1.4/xTrayPlayer_Setup_v1.1.4.exe) |
| **Bản portable đầy đủ runtime** | `.zip` | [xTrayPlayer_Portable_v1.1.4.zip](https://github.com/hachikovn/xTrayPlayer-Releases/releases/download/v1.1.4/xTrayPlayer_Portable_v1.1.4.zip) |

Khuyến nghị dùng **Setup** để cập nhật bản đang cài. Setup sẽ đóng ứng dụng trước khi ghi đè, yêu cầu quyền UAC khi cần và có tùy chọn mở trang tải WebView2 Runtime chính thức. Bản portable là ZIP đầy đủ, chỉ cần giải nén rồi chạy `xTrayPlayer.exe`.

## ✨ Có gì mới trong v1.1.4?

* 🎨 **Taskbar Appearance:** hỗ trợ Clear, Solid và Acrylic trên Windows 11 qua XAML Diagnostics TAP; giữ nguyên mô hình single-owner.
* 🧪 **Acrylic ổn định hơn:** sửa cách ánh xạ opacity để tint không bị áp dụng hai lần và không che backdrop ngoài ý muốn.
* 🖥️ **Multi-monitor & Explorer resilience:** phát hiện lại Taskbar sau khi Explorer khởi động lại và tái áp dụng trạng thái.
* 🔄 **Cập nhật ứng dụng đáng tin cậy hơn:** ưu tiên Setup, tải vào file tạm, kiểm tra SHA-256 khi GitHub cung cấp digest và chỉ khởi chạy Setup sau khi app thoát sạch.
* 📦 **Gói portable đầy đủ:** ZIP self-contained .NET 9 gồm native TAP DLL, WebView2 bindings và uBlock Origin assets; không dùng bản publish rút gọn hoặc single-file thiếu DLL native.
* 🌐 **WebView2 fallback rõ ràng:** nếu máy chưa có Microsoft Edge WebView2 Runtime, app hướng dẫn người dùng tải từ Microsoft.

## 🖥️ Yêu cầu hệ thống

* Windows 10 hoặc Windows 11 64-bit.
* Bản Setup/Portable đã kèm .NET 9 runtime và thư viện ứng dụng.
* **Microsoft Edge WebView2 Runtime** cần có để dùng YouTube/PiP. Nếu thiếu, tải [WebView2 Evergreen Bootstrapper](https://go.microsoft.com/fwlink/p/?LinkId=2124703); Setup cũng có tùy chọn mở liên kết này sau khi cài.
* Windows Transparency effects cần bật để Acrylic có thể hiển thị backdrop blur; khi tắt, Windows có thể dùng màu fallback.

## 👨‍💻 Tác giả & Hỗ trợ

* **Ý tưởng & Kiểm thử:** Đỗ Hồng Minh
* **Phát triển & Lập trình:** Antigravity (Google DeepMind) & Codex (OpenAI)
* **Website:** [dohongminh.com](https://dohongminh.com)
* **Zalo:** [0965 92 4444](https://zalo.me/0965924444)
* **Mã nguồn riêng:** [github.com/hachikovn/xTrayPlayer](https://github.com/hachikovn/xTrayPlayer)
* **Báo lỗi/hỗ trợ:** mở Issue trên kho Releases hoặc liên hệ qua website/Zalo.

## 📄 Giấy phép

Dự án phát triển cho mục đích cá nhân & cộng đồng.
