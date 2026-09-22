# ♠️ Micro MTT 8-Max Assistant

Trợ lý tra cứu nhanh Ma trận Preflop (Range) và Chiến thuật Khai thác (Exploit) dành cho người chơi Poker giải đấu Micro-stakes định dạng **8-Max** (đặc biệt tối ưu cho môi trường GGPoker).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Tính Năng Nổi Bật

- **Tra cứu ma trận theo độ sâu Stack (BB):**
  - **< 12 BB:** Chiến thuật Push / Fold thuần túy.
  - **12 - 25 BB:** Kỹ thuật Resteal 3-Bet Shove & Steal blind.
  - **25 - 50 BB:** Main game, tối ưu C-bet & phòng thủ Postflop.
  - **> 50 BB:** Deep Stack, khai thác Implied Odds (Set-mining, Suited Connectors).
- **Đầy đủ 8 vị trí trên bàn:** UTG, UTG+1, MP, HJ, CO, BTN, SB, BB.
- **Gợi ý Bet Sizing:** Định mức size cược chuẩn cho từng tình huống và stack depth.
- **Bảng phân loại màu đối thủ (Player Profiling Quick-Notes):**
  - 🟢 **Calling Station:** Đánh Value to, không bluff, không slowplay.
  - 🔵 **Nit:** Tích cực steal blind, c-bet size nhỏ, fold khi bị raise.
  - 🔴 **Maniac:** Check bẫy (induce), mở rộng range call bài trung bình.
  - 🟡 **Regular:** Bám sát blueprint và khai thác tối đa lợi thế vị trí (IP).
- **Giao diện Dark Mode & Mobile Friendly:** Tối ưu kích thước nhẹ, phản hồi nhanh, dễ dàng tra cứu song song khi đang multi-tabling.

---

## 🚀 Hướng Dẫn Cài Đặt & Sử Dụng

Ứng dụng là một trang web đơn lẻ (**Single Page Application - SPA**), không cần cài đặt thêm thư viện hay server backend nào.

### 1. Sử dụng trực tiếp trên máy tính (Offline)
- Tải về hoặc mở file `index.html` bằng bất kỳ trình duyệt nào (Chrome, Edge, Safari, Firefox).

### 2. Triển khai online qua GitHub Pages (Khuyên dùng)
1. Fork hoặc Push mã nguồn lên Repository cá nhân trên GitHub.
2. Vào **Settings** $\rightarrow$ Chọn mục **Pages** ở thanh menu bên trái.
3. Tại phần **Build and deployment**:
   - **Source:** `Deploy from a branch`
   - **Branch:** chọn `main` / folder `/ (root)` $\rightarrow$ Nhấn **Save**.
4. Truy cập đường link được tạo để sử dụng mọi lúc trên điện thoại hoặc máy tính.

---

## 🎯 Cấu Trúc Thư Mục

```text
├── index.html        # Giao diện chính và toàn bộ logic xử lý
└── README.md         # Tài liệu hướng dẫn sử dụng
