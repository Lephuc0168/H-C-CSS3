# 🐟 HỒ CÁ CSS3 - BÀI THI GIỮA KỲ MÔN WEB

Bài tập ứng dụng Mô phỏng **Hồ Cá Thủy Sinh CSS3 & Web Audio API** với chuyển động động vật, thay đổi giao diện, âm thanh sống động và các hiệu ứng tương tác trực quan.

📌 **Link Demo Web (GitHub Pages):** [https://lephuc0168.github.io/H-C-CSS3/](https://lephuc0168.github.io/H-C-CSS3/)  
📌 **Link Mã Nguồn (GitHub Repository):** [https://github.com/Lephuc0168/H-C-CSS3](https://github.com/Lephuc0168/H-C-CSS3)

---

## 🌟 ĐẶC ĐIỂM NỔI BẬT & TÍNH NĂNG

### 1. 🐟 Mô Phỏng Cá Bơi & Animation Thuần CSS
- **5 Giống Cá Đa Dạng**: Cá Koi cam, cá xanh nhiệt đới, cá đỏ cảnh, cá tím loli, cá xanh lá nhỏ.
- **Chuyển Động Sống Động**:
  - Tự động bơi tuần hoàn từ mép này sang mép kia trong phạm vi hồ cá.
  - Vẫy đuôi linh hoạt (`tailWag`) và uốn lượn thân cá (`bodyWobble`).
  - **Tự động quay đầu (`scaleX(-1)`)** ngay khi chạm đúng thành hồ.

### 2. 🎨 Tùy Chỉnh Background (4 Chủ Đề Thủy Cung)
Cho phép người dùng thay đổi không gian bể cá nhanh chóng qua thanh điều khiển Glassmorphism:
- 🌊 **Biển Đêm (Deep Ocean)**: Gam màu xanh đậm lung linh bí ẩn.
- 🪸 **San Hô (Coral Reef)**: Gam màu xanh ngọc bích Rạn San Hô tươi sáng.
- 🌅 **Hoàng Hôn (Sunset Pond)**: Gam màu đỏ tím hoàng hôn huyền ảo.
- 🌿 **Thủy Sinh (Moss Aquarium)**: Gam màu xanh rêu thiên nhiên dịu mát.

### 3. 🎵 Âm Thanh Sống Động (Tích hợp Web Audio API)
Không phụ thuộc file nhạc MP3 bên ngoài (tránh lỗi load trên server), ứng dụng tự tổng hợp âm thanh bằng **Web Audio API**:
- 🔇 **Tắt Âm Thanh**: Chế độ yên tĩnh.
- 🫧 **Sóng Biển & Bọt Nước**: Tiếng sóng biển rì rào kết hợp tiếng nổ bọt khí lách tách.
- 🎶 **Nhạc Thư Giãn**: Giai điệu chuông ngọc (Chimes) du dương thư giãn.
- 🌧️ **Tiếng Nước Chảy**: Âm thanh tiếng nước chảy róc rách tự nhiên.

### 4. 💡 Hiệu Ứng Đèn LED & Chế Độ Ban Đêm (Night Mode)
- **Hệ Thống Đèn LED Đỉnh Bể**: Dải đèn neon sáng rực kết hợp 4 chùm vệt sáng chiếu xiên chéo (`skewX`).
- **Bật / Tắt Đèn Nổi Bật**: 
  - Khi tắt đèn, bể cá sẽ lập tức chuyển sang **Night Mode (Tối mờ `brightness: 0.4`)**.
  - Khi bật đèn, bể cá bừng sáng trở lại rực rỡ.

### 5. 🍞 Tương Tác Thả Thức Ăn Cho Cá
- Người dùng có thể **nhấp chuột trực tiếp vào bất kỳ vị trí nào trong bể cá** (hoặc bấm nút *Thả Thức Ăn*) để thả các hạt thức ăn màu vàng chìm dần xuống đáy.

---

## 🛠️ CÔNG NGHỆ SỬ DỤNG

- **HTML5**: Cấu trúc ngữ nghĩa bài tập Web.
- **CSS3 Pure**: 
  - `Keyframe Animation` & `Transform` (`skewX`, `scaleX`, `translateY`).
  - `Glassmorphism UI` (Effect kính mờ `backdrop-filter`).
  - `CSS Grid / Flexbox` tối ưu giao diện.
  - `Clip-path` tạo hiệu ứng chùm sáng nón.
- **JavaScript (ES6)**:
  - **Web Audio API** (Oscillator, GainNode, BiquadFilterNode) tự tổng hợp âm thanh.
  - Xử lý sự kiện click & DOM Manipulation.

---

## 📁 CẤU TRÚC THƯ MỤC

```text
H-C-CSS3/
├── index.html        # Trang chính hiển thị trên GitHub Pages
├── HoCa_CSS.html     # Mã nguồn trang Hồ cá CSS3
└── README.md         # File thuyết minh tính năng dự án
```

---

## 🚀 HƯỚNG DẪN CHẠY DỰ ÁN LOCALLY

1. Tải repository hoặc clone về máy:
   ```bash
   git clone https://github.com/Lephuc0168/H-C-CSS3.git
   ```
2. Mở trực tiếp file `index.html` hoặc `HoCa_CSS.html` bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox).

---

*Chúc cô có những phút giây thư giãn khi trải nghiệm Hồ Cá CSS3!* 🐟✨
