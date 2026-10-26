# 🧵 SẮC ZÈNG CHỮ VIỆT 🏔️
### Ứng Dụng Học Tập Tương Tác Tiếng Việt 1 & Xóa Mù Chữ Vùng Cao A Lưới
**Hội thi Thiết bị dạy học tự làm - Năm học 2026 - 2027**

---

## 🌟 Giới Thiệu Dự Án
**"Sắc Zèng Chữ Việt"** là đồ dùng dạy học số hóa kết hợp di sản văn hóa phi vật thể quốc gia – **Nghề dệt Dèng (Zèng) truyền thống của đồng bào Pa Cô (huyện A Lưới, tỉnh Thừa Thiên Huế)** với phương pháp giáo dục hiện đại (EdTech & Gamification). 

Ứng dụng được thiết kế tối ưu cho màn hình cảm ứng tương tác, tivi thông minh và máy chiếu lớp học (tỉ lệ chuẩn 16:9), phục vụ giảng dạy Tiếng Việt lớp 1 và các lớp Xóa mù chữ tại vùng đồng bào dân tộc thiểu số.

---

## ✨ Điểm Nhấn & Tính Năng Nổi Bật

- 🎲 **Boardgame Hành Trình A Lưới 20 Chặng:** Mô phỏng con đường học chữ xuyên qua các địa danh nổi tiếng (Thác A Nôr, Đèo A Co, Suối A Lin, Rừng đỗ quyên, Làng Dèng...).
- 🪡 **Cơ Chế Dệt Thoi Hoạt Họa (Loom Shuttle):** Mỗi lượt quay xúc xắc là một động tác phóng thoi dệt cườm hoa văn Zèng độc đáo.
- 🗣️ **Hệ Thống Âm Thanh Đa Ngữ (Neural Audio):** 
  - Đọc mẫu tiếng Việt chuẩn (giọng Thầy giáo & Cô giáo).
  - Tích hợp tiếng Pa Cô bản địa thân thuộc giúp học sinh và bà con dễ dàng liên hệ, hiểu sâu nhớ lâu.
- 👥 **Chế Độ Thi Đấu 2 Đội Sôi Nổi:** Đội **A Keng** (chàng trai khèn bè) và Đội **A Mây** (cô gái gùi chữ).
- 🎯 **Bảng Điều Khiển Sư Phạm (Teacher Controls):** Cho phép giáo viên can thiệp số bước xúc xắc, chọn chặng bài học, tùy chỉnh âm thanh và chuyển chế độ toàn màn hình dễ dàng.

---

## 📁 Cấu Trúc Thư Mục
```text
├── index.html                  # Trang chính của ứng dụng web (Vercel Entrypoint)
├── game_sac_zeng_chu_viet.html # Bản game gốc (đồng bộ với index.html)
├── vercel.json                 # Cấu hình tối ưu cache & audio streaming trên Vercel
├── .gitignore                  # Bỏ qua file rác hệ điều hành
├── favicon.ico                 # Icon trang web
└── assets/                     # Tài nguyên đa phương tiện
    ├── Colorful Mountain...    # Bản đồ thung lũng A Lưới độ nét cao
    ├── akeng_*.png             # Mascot & Avatar Đội A Keng
    ├── amay_*.png              # Mascot & Avatar Đội A Mây
    ├── favicon-*.png           # Bộ icon đa kích thước
    └── audio/                  # 63 file phát âm chuẩn (Việt Nam, Nữ, Tiếng Pa Cô)
```

---

## 🚀 Hướng Dẫn Triển Khai (Deploy)

### 1. Chạy trực tiếp tại máy tính lớp học (Offline)
- Chỉ cần nhấp đúp mở file `index.html` bằng trình duyệt Google Chrome, Edge hoặc Cốc Cốc.
- Không cần cài đặt máy chủ hay kết nối Internet phức tạp.

### 2. Triển khai lên Vercel (Online)
1. Đẩy thư mục này lên GitHub (Repository: `sac-zeng-chu-viet`).
2. Truy cập [vercel.com](https://vercel.com) và bấm **Add New Project**.
3. Chọn kho lưu trữ GitHub vừa tạo -> Framework Preset chọn **Other**.
4. Nhấn **Deploy** — Ứng dụng sẽ hoạt động ngay lập tức với domain riêng dạng: `https://sac-zeng-chu-viet.vercel.app`.

---

## 🏆 Đơn Vị & Tác Giả
- **Dự án:** Thiết bị dạy học tự làm cấp Huyện/Tỉnh 2026 - 2027.
- **Bản quyền nội dung & Ý tưởng sư phạm:** Giáo viên thực hiện dự án "Sắc Zèng Chữ Việt".
