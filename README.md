<div align="center">

# ⚡ Huy Pham Obfuscator

### Obfuscate code đa ngôn ngữ — Bảo vệ source code của bạn

**Version 7.1** · **AES-256-GCM** · **Offline 100%** · **Made in Vietnam** 🇻🇳

[![Version](https://img.shields.io/badge/version-7.1-blue?style=for-the-badge)](https://github.com/huypham36tb2-maker/Obfhuypham)
[![License](https://img.shields.io/badge/license-Free-green?style=for-the-badge)](LICENSE)
[![Offline](https://img.shields.io/badge/offline-100%25-brightgreen?style=for-the-badge)]()
[![AES](https://img.shields.io/badge/AES-256--GCM-purple?style=for-the-badge)]()

[🌐 Demo](https://huypham36tb2-maker.github.io/Obfhuypham/) · [📖 Docs](#-mục-lục) · [🐛 Báo lỗi](https://github.com/huypham36tb2-maker/Obfhuypham/issues) · [💡 Đề xuất](https://github.com/huypham36tb2-maker/Obfhuypham/discussions)

</div>

---

## 📋 Mục lục

<details open>
<summary><b>Nhấn để mở/đóng mục lục</b></summary>

### 📚 Tổng quan
- [Giới thiệu](#-giới-thiệu)
- [Điểm nổi bật](#-điểm-nổi-bật)
- [Ai nên dùng](#-ai-nên-dùng)
- [Screenshots](#-screenshots)

### ✨ Tính năng
- [Obfuscate](#-obfuscate)
- [Deobfuscate](#-deobfuscate)
- [Tài khoản](#-tài-khoản)
- [UI/UX](#-uiux)

### 🚀 Bắt đầu
- [Cách dùng nhanh](#-cách-dùng-nhanh)
- [Cài đặt local](#-cài-đặt-local)
- [Deploy](#-deploy)

### 🎛️ Cấu hình
- [Preset](#-preset)
- [Tuỳ chọn nâng cao](#-tuỳ-chọn-nâng-cao)
- [Kỹ thuật obfuscation](#-kỹ-thuật-obfuscation)

### 📖 Hướng dẫn chi tiết
- [Ví dụ từng ngôn ngữ](#-ví-dụ-từng-ngôn-ngữ)
- [Xử lý lỗi](#-xử-lý-lỗi)
- [Best practices](#-best-practices)

### 🔐 Bảo mật
- [Mô hình bảo mật](#-mô-hình-bảo-mật)
- [Giới hạn](#-giới-hạn)
- [Khuyến nghị](#-khuyến-nghị)

### 🤝 Cộng đồng
- [FAQ](#-faq)
- [Đóng góp](#-đóng-góp)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Credits](#-credits)

</details>

---

## 🎯 Giới thiệu

**Huy Pham Obfuscator** là một công cụ **obfuscate (làm rối) code đa ngôn ngữ** được thiết kế để chạy **hoàn toàn trên trình duyệt** — không cần server, không cần cài đặt, không upload code lên đâu cả.

Toàn bộ quá trình xử lý diễn ra **tại máy của bạn** (client-side), đảm bảo tính **riêng tư tuyệt đối** cho source code của bạn. Dù bạn đang viết Python, JavaScript, Lua hay HTML — công cụ này đều có thể giúp bạn bảo vệ code khỏi bị đọc trộm, copy, hoặc reverse-engineer.

### Tại sao cần obfuscate?

Trong thế giới phát triển phần mềm hiện đại, việc bảo vệ **intellectual property (IP)** ngày càng trở nên quan trọng:

- **Ngăn copy** — Người khác không thể copy-paste code của bạn
- **Bảo vệ thuật toán** — Logic độc quyền không bị lộ
- **Chống reverse** — Khó dịch ngược về code gốc
- **Bảo vệ license** — Ngăn chặn crack, mod
- **Bảo mật API key** — Giấu thông tin nhạy cảm

### Vì sao chọn Huy Pham Obfuscator?

| Ưu điểm | Chi tiết |
|:--------|:---------|
| ✅ **Offline 100%** | Không upload code lên server, an toàn tuyệt đối |
| ✅ **Đa ngôn ngữ** | Python, JS, Lua, HTML — 1 tool cho tất cả |
| ✅ **AES-256-GCM** | Chuẩn mã hoá quân sự, khó phá |
| ✅ **Miễn phí** | Không giới hạn, không subscription |
| ✅ **Không cài đặt** | Chạy ngay trên browser |
| ✅ **Mobile friendly** | Chạy mượt trên điện thoại |
| ✅ **Open source** | Có thể tự audit, tự sửa |
| ✅ **Made in Vietnam** | Hỗ trợ tiếng Việt 100% |

---

## 🌟 Điểm nổi bật

### 🎨 Giao diện hiện đại

- **Dark/Light/Auto theme** — Tự động theo hệ thống
- **Sidebar navigation** — Menu dọc chuyên nghiệp, gọn gàng
- **Responsive design** — Mobile, tablet, desktop
- **Toast notification** — Thông báo không che nội dung
- **Modal centered** — Popup giữa màn hình, không phải bottom-sheet
- **Micro-animations** — Mượt mà, không giật lag

### 🔒 Bảo mật cao cấp

- **AES-256-GCM** — Mã hoá đối xứng chuẩn quân sự
- **SHA-256 anti-tamper** — Phát hiện file bị sửa
- **Random IV** — Mỗi lần obf ra file khác nhau
- **Key derivation** — PBKDF2-like (SHA-256 + salt)
- **Domain lock** — Chỉ chạy trên domain cho phép
- **Expiry date** — File tự hết hạn
- **Version lock** — Chỉ chạy Python 3.8-3.13

### ⚡ Hiệu suất

- **Client-side only** — Không cần server round-trip
- **Deflate compression** — File nhỏ hơn 30-50%
- **Lazy loading** — Không tải thừa
- **LocalStorage cache** — Không mất data khi F5
- **Web Workers** — Không block UI

### 🎁 Trial Pro miễn phí

- **Đăng nhập Google** — 1 click, không cần đăng ký
- **Pro 5 ngày** — Full tính năng
- **Không cần thẻ** — Không thanh toán, không subscription
- **Không giới hạn** — Sau trial về Free, không bị chặn

---

## 👥 Ai nên dùng?

### 👨‍💻 Developer
- Bảo vệ code sản phẩm
- Phân phối tool/script
- Bán plugin/extension

### 🎓 Học sinh / Sinh viên
- Học về obfuscation
- Thực hành bảo mật
- Làm đồ án môn học

### 🔍 Security Researcher
- Test khả năng reverse
- Nghiên cứu malware
- Phân tích obf code

### 🏢 Doanh nghiệp
- Bảo vệ IP công ty
- Phân phối nội bộ
- Tích hợp CI/CD

### 🎮 Game Developer
- Bảo vệ game logic
- Chống cheat/mod
- Bảo vệ save file

---

## 📸 Screenshots

### 🖥️ Desktop view
