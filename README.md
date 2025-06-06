# Drone Light Show Simulation

Đây là dự án mô phỏng hệ thống trình diễn ánh sáng bằng drone sử dụng Unity. Dự án tích hợp các kỹ thuật tối ưu như thuật toán Hungarian, trường thế nhân tạo (Artificial Potential Field - APF), điều phối chuyển động và giao diện thiết kế hoạt cảnh.

## 📦 Yêu cầu hệ thống

- Unity Editor phiên bản **2022.3.51f1** (khuyến nghị)
- Unity Hub để quản lý dự án
- Các module cần thiết:
  - Windows Build Support
  - Android Build Support (nếu cần)

## 🚀 Cài đặt và chạy mô phỏng

### 1. Cài đặt Unity

- Truy cập [https://unity.com/download](https://unity.com/download) để tải **Unity Hub**.
- Trong Unity Hub, vào tab **Installs** → **Add** → chọn phiên bản **2022.3.51f1**.
- Cài đặt các module cần thiết như Windows Build Support.

### 2. Tải mã nguồn

Bạn có thể tải mã nguồn theo một trong hai cách:

#### Cách 1: Clone bằng Git
```bash
git clone https://github.com/ducvu25/DoAnTN.git
```

#### Cách 2: Tải ZIP
- Truy cập [https://github.com/ducvu25/DoAnTN](https://github.com/ducvu25/DoAnTN)
- Nhấn **Code** → **Download ZIP**
- Giải nén thư mục tải về

### 3. Mở dự án bằng Unity

- Mở **Unity Hub**
- Chọn tab **Projects** → **Add**
- Duyệt đến thư mục chứa dự án vừa tải về hoặc clone
- Chọn **Open** để mở dự án

### 4. Chạy mô phỏng

- Trong Unity Editor, vào thư mục `Assets/Scenes`
- Mở file `Menu.unity` (Scene chính)
- Nhấn nút **Play** để bắt đầu mô phỏng

## 📂 Cấu trúc thư mục chính

```plaintext
DoAnTN/
├── Assets/
│   ├── Scenes/            # Các file scene của Unity
│   ├── Scripts/           # Mã nguồn C#
│   ├── Prefabs/           # Các mẫu đối tượng
│   └── ...
├── ProjectSettings/
├── Packages/
└── README.md              # Tệp này
```

## 📚 Tài liệu tham khảo

- Hungarian Algorithm: Tối ưu phân công nhiệm vụ drone
- Artificial Potential Field: Tránh va chạm và điều hướng
- Unity DOTween: Hiệu ứng động
- Unity Addressables & Object Pooling: Quản lý hiệu suất

---

> Được phát triển bởi Vũ Trung Đức – Dự án khóa luận tốt nghiệp tại Đại học Công nghệ – ĐHQGHN.
