# 🎯 CS16-Launcher

<div align="center">

  <img src="https://raw.githubusercontent.com/khanhtg2011/CS16-Launcher/main/assets/banner.png" alt="CS16 Launcher Banner" width="100%" onerror="this.style.display='none'"/>

  <p align="center">
    <strong>Trình khởi chạy Counter-Strike 1.6 hiện đại, tối ưu hóa hiệu năng và quản lý cấu hình tất cả-trong-một.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/khanhtg2011/CS16-Launcher/releases"><img src="https://img.shields.io/github/v/release/khanhtg2011/CS16-Launcher?style=for-the-badge&color=blue" alt="Latest Release"></a>
    <a href="https://github.com/khanhtg2011/CS16-Launcher/blob/main/LICENSE"><img src="https://img.shields.io/github/license/khanhtg2011/CS16-Launcher?style=for-the-badge&color=green" alt="License"></a>
    <a href="https://github.com/khanhtg2011/CS16-Launcher/stargazers"><img src="https://img.shields.io/github/stars/khanhtg2011/CS16-Launcher?style=for-the-badge&color=yellow" alt="Stars"></a>
    <a href="https://github.com/khanhtg2011/CS16-Launcher/issues"><img src="https://img.shields.io/github/issues/khanhtg2011/CS16-Launcher?style=for-the-badge&color=red" alt="Issues"></a>
    <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows" alt="Platform">
  </p>

  <p align="center">
    <a href="#-tính-năng-nổi-bật">Tính năng</a> •
    <a href="#-ảnh-chụp-giao-diện">Ảnh chụp</a> •
    <a href="#-cài-đặt--tải-về">Cài đặt</a> •
    <a href="#-hướng-dẫn-sử-dụng">Hướng dẫn</a> •
    <a href="#-build-từ-mã-nguồn">Build mã nguồn</a> •
    <a href="#-đóng-góp">Đóng góp</a> •
    <a href="#-tuyên-bố-miễn-trừ-trách-nhiệm">Tuyên bố</a>
  </p>

</div>

---

## 📖 Giới thiệu

**CS16-Launcher** là công cụ hỗ trợ khởi chạy và tùy biến chuyên sâu dành cho tựa game huyền thoại **Counter-Strike 1.6 (Half-Life: Counter-Strike)**.

Dự án ra đời nhằm giải quyết các bất tiện phổ biến khi chơi CS 1.6 trên các hệ điều hành hiện đại (Windows 10, Windows 11) như: lỗi độ phân giải, chuột bị gia tốc (mouse acceleration), khó quản lý nhiều file config (`.cfg`), và thiếu công cụ kết nối nhanh đến danh sách server ưa thích.

---

## ✨ Tính năng nổi bật

### ⚡ Khởi chạy & Tối ưu hóa chuyên sâu (Launch & Optimization)
- **Tùy biến tham số dòng lệnh 1-Click:** Dễ dàng bật/tắt các lệnh chuẩn thi đấu:
  - `-noforcemaccel -noforcemparms -noforcemspd` (Loại bỏ hoàn toàn gia tốc chuột)
  - `-freq <Hz>` (Tùy chỉnh tần số quét màn hình 60Hz, 75Hz, 144Hz, 240Hz,...)
  - `-nofbo -nomsaa` (Khắc phục lỗi màn hình mờ, tụt FPS trên card đồ họa thế hệ mới)
  - `-stretchaspect` (Hỗ trợ kéo dãn tỉ lệ 4:3 trên màn hình Wide 16:9/16:10)
- **Thiết lập Renderer & Độ phân giải:** Lựa chọn linh hoạt giữa **OpenGL**, **Direct3D (D3D)** hoặc **Software Mode**, cùng các độ phân giải kinh điển (640x480, 800x600, 1024x768, 1920x1080).

### 🎯 Quản lý Cấu hình & Profiles (Config Manager)
- Chuyển đổi linh hoạt giữa nhiều profile cấu hình khác nhau (VD: *Match / Public / Deathmatch / Movie Making*).
- Tích hợp sẵn bộ thiết lập Rate chuẩn thi đấu (`rate 25000`, `cl_updaterate 101`, `cl_cmdrate 101`, `fps_max 99.5`).
- Sao lưu và khôi phục cài đặt gốc của game chỉ với một cú nhấp chuột.

### 🌐 Quản lý Server & Fast Connect
- Lưu danh sách máy chủ yêu thích (Favorites Server List) kèm kiểm tra ping trực tiếp.
- Kết nối trực tiếp vào máy chủ mà không cần mở console gõ lệnh `connect <IP:Port>`.
- Khôi phục danh sách Master Server (tìm kiếm server online quốc tế & Việt Nam).

### 📦 Quản lý Mod, Skin & Map
- Tự động nhận diện và cài đặt model vũ khí (`v_`, `p_`, `w_`), nhân vật, âm thanh (`sound`), và bản đồ (`.bsp`).
- Hỗ trợ bật/tắt nhanh các gói skin mặc định (Classic) hoặc skin nâng cấp (CS:GO / HD Remastered).
- Tích hợp quản lý Bot thông minh (YaPB / POD-Bot) cho chế độ luyện tập offline.

---

## 🖥 Ảnh chụp giao diện

<div align="center">
  <img src="https://raw.githubusercontent.com/khanhtg2011/CS16-Launcher/main/assets/preview.png" alt="Giao diện CS16-Launcher" width="85%" onerror="this.style.display='none'"/>
  <p><em>(Hình ảnh minh họa giao diện chính của CS16-Launcher)</em></p>
</div>

---

## 📥 Cài đặt & Tải về

### Cách 1: Tải bản cài đặt đóng gói sẵn (Khuyến nghị)
1. Truy cập mục [**Releases**](https://github.com/khanhtg2011/CS16-Launcher/releases).
2. Tải về file nén mới nhất (ví dụ: `CS16-Launcher-v1.0.0.zip` hoặc `CS16-Launcher-Setup.exe`).
3. Giải nén vào thư mục bạn muốn hoặc chạy bộ cài đặt.
4. Mở `CS16-Launcher.exe` và trải nghiệm!

### Cách 2: Sử dụng Git
```bash
git clone https://github.com/khanhtg2011/CS16-Launcher.git
cd CS16-Launcher
```

---

## 🚀 Hướng dẫn sử dụng

1. **Chọn thư mục game:** 
   - Lần đầu mở ứng dụng, nhấn **Chọn đường dẫn game** (Browse Game Path) và trỏ đến thư mục chứa file `hl.exe` của Counter-Strike 1.6 (hoặc thư mục game trên Steam: `steamapps/common/Half-Life`).
2. **Cấu hình thông số:**
   - Điều chỉnh độ phân giải, chế độ toàn màn hình / cửa sổ.
   - Nhập hoặc tick chọn các tham số khởi chạy mong muốn.
3. **Lưu cấu hình & Khởi chạy:**
   - Nhấn **Lưu cấu hình** (Save Settings).
   - Nhấn nút **Bắt đầu chơi (Launch Game)** để vào game ngay lập tức!

---

## 🛠 Hướng dẫn Build từ mã nguồn

Dự án được xây dựng với cấu trúc mã nguồn rõ ràng và dễ bảo trì. Bạn có thể tự biên dịch dự án theo các bước sau:

### Yêu cầu môi trường
- Hệ điều hành: Windows 10/11 (64-bit hoặc 32-bit)
- Git
- Runtime tương ứng (ví dụ: `.NET 6.0/8.0 SDK`, `Visual Studio 2022`, hoặc môi trường lập trình của dự án)

### Các bước biên dịch

```bash
# 1. Clone repository về máy
git clone https://github.com/khanhtg2011/CS16-Launcher.git
cd CS16-Launcher

# 2. Cài đặt các gói phụ thuộc (Dependencies)
dotnet restore

# 3. Biên dịch và tạo bản phát hành
dotnet build --configuration Release

# Hoặc xuất ra file thực thi (.exe) độc lập duy nhất:
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true
```

---

## 📁 Cấu trúc thư mục

```text
CS16-Launcher/
├── 📁 assets/             # Hình ảnh, biểu tượng, tài nguyên giao diện
├── 📁 src/                # Mã nguồn chính của Launcher
│   ├── 📁 Core/           # Logic khởi chạy game, quản lý tiến trình hl.exe
│   ├── 📁 Config/         # Đọc/ghi cấu hình launcher & file config.cfg
│   ├── 📁 Models/         # Định nghĩa dữ liệu (Server, Profile, Mods)
│   └── 📁 Views/          # Giao diện người dùng (UI Components)
├── 📁 docs/               # Tài liệu chi tiết và hướng dẫn bổ sung
├── 📄 .gitignore          # Danh sách file bỏ qua khi commit Git
├── 📄 LICENSE             # Giấy phép mã nguồn mở (MIT)
└── 📄 README.md           # Tài liệu hướng dẫn dự án
```

---

## 🗺 Lộ trình phát triển (Roadmap)

- [x] Giao diện khởi chạy cơ bản và chỉnh sửa launch parameters.
- [x] Quản lý cấu hình độ phân giải và tần số quét màn hình.
- [ ] Tích hợp tính năng tự động tải và cập nhật Masterserver.
- [ ] Hỗ trợ tải Map trực tiếp từ FastDL Server.
- [ ] Thêm chế độ hiển thị OSD / Kiểm tra Ping trong launcher.
- [ ] Hỗ trợ đa ngôn ngữ (Tiếng Việt, Tiếng Anh).

---

## 🤝 Đóng góp (Contributing)

Mọi đóng góp nhằm hoàn thiện và phát triển dự án đều được hoan nghênh nồng nhiệt!

1. **Fork** repository này về tài khoản của bạn.
2. Tạo một branch mới cho tính năng hoặc bản sửa lỗi:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit các thay đổi của bạn:
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. Đẩy branch lên GitHub:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Mở một **Pull Request** và mô tả chi tiết các cải tiến bạn đã thực hiện.

---

## ⚠️ Tuyên bố miễn trừ trách nhiệm (Disclaimer)

- **Counter-Strike 1.6** và **Half-Life** là tài sản thuộc bản quyền của **Valve Corporation**.
- Phần mềm này là một công cụ tiện ích độc lập của cộng đồng, **không** phân phối lại các tệp tin có bản quyền của trò chơi và **không** liên kết chính thức với Valve Corporation.
- Người dùng cần sở hữu bản quyền hợp pháp của Counter-Strike 1.6 trên Steam hoặc phương tiện chính thức để sử dụng launcher này.

---

## 📄 Giấy phép (License)

Dự án được phân phối dưới giấy phép **MIT License**. Bạn có toàn quyền sử dụng, sửa đổi và phân phối theo các điều khoản trong file [LICENSE](LICENSE).

---

## 👤 Tác giả & Liên hệ

- **Tác giả:** [@khanhtg2011](https://github.com/khanhtg2011)
- **GitHub Repository:** [khanhtg2011/CS16-Launcher](https://github.com/khanhtg2011/CS16-Launcher)
- **Báo cáo lỗi & Góp ý:** [Issues Tracker](https://github.com/khanhtg2011/CS16-Launcher/issues)

<div align="center">
  Nếu bạn thấy dự án hữu ích, đừng quên tặng dự án một ⭐️ <strong>Star</strong> trên GitHub nhé!
</div>
