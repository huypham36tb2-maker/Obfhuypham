<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=240&section=header&text=Huy%20Pham%20Obfuscator&fontSize=72&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Obfuscate%20Code%20%C4%90a%20Ng%C3%B4n%20Ng%E1%BB%AF%20%C2%B7%20B%E1%BA%A3o%20V%E1%BB%87%20Source%20Code%20C%E1%BB%A7a%20B%E1%BA%A1n&descAlignY=58&descSize=20" width="100%"/>

# ⚡ Huy Pham Obfuscator

### Công cụ obfuscate code đa ngôn ngữ — Bảo vệ source code của bạn khỏi reverse engineering

**Version 7.1** · **AES-256-GCM** · **Offline 100%** · **Made in Vietnam** 🇻🇳

[![Version](https://img.shields.io/badge/version-7.1-blue?style=for-the-badge&logo=github)](https://github.com/huypham36tb2-maker/Obfhuypham)
[![License](https://img.shields.io/badge/license-Free-green?style=for-the-badge)](LICENSE)
[![Offline](https://img.shields.io/badge/offline-100%25-brightgreen?style=for-the-badge)]()
[![AES](https://img.shields.io/badge/AES-256--GCM-purple?style=for-the-badge&logo=letsencrypt)]()

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)]()
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()

[🌐 Demo](https://huypham36tb2-maker.github.io/Obfhuypham/) · [📖 Docs](#-mục-lục) · [🐛 Báo lỗi](https://github.com/huypham36tb2-maker/Obfhuypham/issues) · [💡 Đề xuất](https://github.com/huypham36tb2-maker/Obfhuypham/discussions) · [⭐ Star](https://github.com/huypham36tb2-maker/Obfhuypham/stargazers)

</div>

---

<div align="center">

## 📊 Thông số dự án

| | | | |
|:---:|:---:|:---:|:---:|
| **4**<br>Ngôn ngữ | **6**<br>Preset | **10**<br>Lớp tối đa | **100%**<br>Offline |
| **AES-256**<br>Mã hoá | **SHA-256**<br>Anti-tamper | **0đ**<br>Miễn phí | **∞**<br>Không giới hạn |

</div>

---

## 📋 Mục lục chi tiết

<details open>
<summary><b>🔽 Nhấn để mở/đóng toàn bộ mục lục</b></summary>

### 📚 PHẦN 1 — TỔNG QUAN DỰ ÁN
- [1. Giới thiệu](#1-giới-thiệu)
  - [1.1. Tổng quan](#11-tổng-quan)
  - [1.2. Tại sao cần obfuscate?](#12-tại-sao-cần-obfuscate)
  - [1.3. Vì sao chọn Huy Pham Obfuscator?](#13-vì-sao-chọn-huy-pham-obfuscator)
  - [1.4. So sánh với các tool khác](#14-so-sánh-với-các-tool-khác)
  - [1.5. Lịch sử phiên bản](#15-lịch-sử-phiên-bản)
- [2. Điểm nổi bật](#2-điểm-nổi-bật)
  - [2.1. Giao diện hiện đại](#21-giao-diện-hiện-đại)
  - [2.2. Bảo mật cao cấp](#22-bảo-mật-cao-cấp)
  - [2.3. Hiệu suất](#23-hiệu-suất)
  - [2.4. Trial Pro miễn phí](#24-trial-pro-miễn-phí)
  - [2.5. Hỗ trợ đa nền tảng](#25-hỗ-trợ-đa-nền-tảng)
- [3. Ai nên dùng](#3-ai-nên-dùng)
  - [3.1. Developer](#31-developer)
  - [3.2. Học sinh / Sinh viên](#32-học-sinh--sinh-viên)
  - [3.3. Security Researcher](#33-security-researcher)
  - [3.4. Doanh nghiệp](#34-doanh-nghiệp)
  - [3.5. Game Developer](#35-game-developer)
  - [3.6. Freelancer](#36-freelancer)
- [4. Screenshots](#4-screenshots)
  - [4.1. Desktop view](#41-desktop-view)
  - [4.2. Mobile view](#42-mobile-view)
  - [4.3. Modal đăng nhập Google](#43-modal-đăng-nhập-google)
  - [4.4. Modal Pro](#44-modal-pro)
  - [4.5. Tab Deobfuscate](#45-tab-deobfuscate)
- [5. Demo](#5-demo)

### ✨ PHẦN 2 — TÍNH NĂNG CHI TIẾT
- [6. Obfuscate](#6-obfuscate)
  - [6.1. Pipeline tổng quan](#61-pipeline-tổng-quan)
  - [6.2. Python chi tiết](#62-python-chi-tiết)
  - [6.3. JavaScript chi tiết](#63-javascript-chi-tiết)
  - [6.4. Lua chi tiết](#64-lua-chi-tiết)
  - [6.5. HTML chi tiết](#65-html-chi-tiết)
- [7. Deobfuscate](#7-deobfuscate)
- [8. Tài khoản & Phân quyền](#8-tài-khoản--phân-quyền)
- [9. UI/UX](#9-uiux)

### 🚀 PHẦN 3 — BẮT ĐẦU
- [10. Cách dùng nhanh](#10-cách-dùng-nhanh)
- [11. Cài đặt local](#11-cài-đặt-local)
- [12. Deploy](#12-deploy)
- [13. Cấu hình](#13-cấu-hình)

### 🛠️ PHẦN 4 — KỸ THUẬT
- [14. Kỹ thuật obfuscation](#14-kỹ-thuật-obfuscation)
- [15. Preset chi tiết](#15-preset-chi-tiết)
- [16. Tuỳ chọn nâng cao](#16-tuỳ-chọn-nâng-cao)

### 📖 PHẦN 5 — HƯỚNG DẪN
- [17. Ví dụ từng ngôn ngữ](#17-ví-dụ-từng-ngôn-ngữ)
- [18. Xử lý lỗi](#18-xử-lý-lỗi)
- [19. Best practices](#19-best-practices)
- [20. FAQ](#20-faq)

### 🔐 PHẦN 6 — BẢO MẬT
- [21. Mô hình bảo mật](#21-mô-hình-bảo-mật)
- [22. Giới hạn](#22-giới-hạn)
- [23. Khuyến nghị](#23-khuyến-nghị)
- [24. License](#24-license)

### 🤝 PHẦN 7 — CỘNG ĐỒNG
- [25. Đóng góp](#25-đóng-góp)
- [26. Roadmap](#26-roadmap)
- [27. Credits](#27-credits)
- [28. Liên hệ](#28-liên-hệ)

</details>

---

# 📚 PHẦN 1 — TỔNG QUAN DỰ ÁN

## 1. Giới thiệu

### 1.1. Tổng quan

**Huy Pham Obfuscator** là một công cụ **obfuscate (làm rối) code đa ngôn ngữ** được thiết kế để chạy **hoàn toàn trên trình duyệt** — không cần server, không cần cài đặt, không upload code lên đâu cả.

Toàn bộ quá trình xử lý diễn ra **tại máy của bạn** (client-side), đảm bảo tính **riêng tư tuyệt đối** cho source code của bạn. Dù bạn đang viết Python, JavaScript, Lua hay HTML — công cụ này đều có thể giúp bạn bảo vệ code khỏi bị đọc trộm, copy, hoặc reverse-engineer.

#### Đặc điểm chính

| Đặc điểm | Chi tiết |
|:---------|:---------|
| **Tên** | Huy Pham Obfuscator |
| **Phiên bản** | 7.1 |
| **Tác giả** | Huy Pham |
| **Nền tảng** | Web browser (client-side) |
| **Ngôn ngữ hỗ trợ** | Python, JavaScript, Lua, HTML |
| **Thuật toán mã hoá** | AES-256-GCM |
| **Nén** | Deflate raw (RFC 1951) |
| **Encoding** | Base64 |
| **Anti-tamper** | SHA-256 |
| **License** | Free (không giới hạn) |
| **Made in** | Vietnam 🇻🇳 |

#### Triết lý thiết kế

1. **Privacy first** — Code của user **không bao giờ** rời khỏi máy họ
2. **No server** — Không có backend, không tracking, không analytics
3. **Simple but powerful** — UI đơn giản nhưng kỹ thuật mạnh mẽ
4. **Free forever** — Core features miễn phí vĩnh viễn
5. **Open source** — Ai cũng có thể audit code

### 1.2. Tại sao cần obfuscate?

Trong thế giới phát triển phần mềm hiện đại, việc bảo vệ **intellectual property (IP)** ngày càng trở nên quan trọng. Dưới đây là những lý do chính:

#### 1.2.1. Bảo vệ thuật toán độc quyền

Khi bạn phát triển một thuật toán mới, công thức độc quyền, hoặc logic phức tạp — đó là **tài sản trí tuệ** của bạn. Nếu để dạng plain text, bất kỳ ai cũng có thể:

- Copy-paste vào project của họ
- Reverse-engineer để hiểu logic
- Sử dụng miễn phí mà không trả tiền

**Giải pháp:** Obfuscate code → khó đọc, khó hiểu, khó copy.

#### 1.2.2. Chống reverse engineering

Reverse engineering (dịch ngược) là quá trình phân tích code đã compile để hiểu logic gốc. Với code không obfuscate:

```python
# Code gốc — ai cũng đọc được
def calculate_price(quantity, unit_price):
    discount = 0.1 if quantity > 100 else 0
    return quantity * unit_price * (1 - discount)
