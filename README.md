# GroundAtlas Desktop — Native C++20 Architectural Site Analysis Workstation

> **100% Pure Compiled Native C++20 / Qt 6.8 / OpenGL 3.3 / MapLibre Native (0% Electron · 0% WebView)**
> Nạp hiện trạng khu đất OpenStreetMap toàn cầu trong 2 giây, đè lớp quy hoạch 2D/3D, nhập trực tiếp SketchUp `.skp`, cắt mặt cắt A–A' sống và xuất trọn Bộ hồ sơ kiến trúc 8 tệp chỉ với 1 cú bấm.

<p align="center">
  <a href="https://github.com/hienkhang2004-coder/GroundAtlas/raw/main/GroundAtlas-Desktop-2.3.1-Setup.exe">
    <strong>⬇ Tải bản cài Windows x64 miễn phí (v2.3.1 · 20 MB)</strong>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://groundatlas-license-server.groundatlas.workers.dev/">
    <strong>⚡ Mua bản quyền Pro Trọn đời 2.x (Early Bird 99.000đ)</strong>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://groundatlas.groundatlas.workers.dev/">
    <strong>🌐 Phiên bản Web</strong>
  </a>
</p>

---

## Hình ảnh thực tế trên GPU

![GroundAtlas Desktop 3D Quy hoạch Hà Nội và Đổ bóng 4096px](docs/screenshots/desktop-3d-quyhoach.png)

| Đồ họa 3D Kiến trúc & 69 Sơ đồ | Mặt cắt A–A' trực tiếp (Dark Studio) |
|---|---|
| ![Archviz Showcase](docs/screenshots/desktop-archviz.png) | ![Live Section Dark](docs/screenshots/desktop-section-dark.png) |

---

## Tính năng nổi bật (Độc quyền bản Desktop Native)

- **Thuần mã máy C++20 / OpenGL 3.3 (180–500 Hz):** khởi động tức thì, chạy trực tiếp trên GPU Windows, đổ bóng mềm Poisson PCF **4096px** và bầu trời vật lý giờ vàng mượt từng phút.
- **Nạp khu đất OpenStreetMap toàn cầu siêu tốc (~2 giây):** tích hợp OSM REST API v0.6 + tự chia lưới 2×2 cho khu vực dày đặc + 4 máy chủ Overpass dự phòng.
- **Đè lớp Quy hoạch sử dụng đất 1-Click (2D & 3D):** hỗ trợ bật/tắt nhanh lớp quy hoạch Hà Nội (`qhpk`, `khsdd`, `qhct`) hoặc dán **Custom XYZ Tile URL** hợp pháp riêng, phủ trực tiếp lên Bản đồ, 2D và phối cảnh 3D có bóng đổ thật.
- **Nhập trực tiếp mô hình 3D SketchUp (`.skp`):** kéo thả thẳng file `.skp`, `.dae`, `.obj`, `.glb`, `.stl` vào hiện trạng khu đất thật.
- **Cắt mặt cắt A–A' sống & Concept Massing 3D:** kéo mặt cắt trực tiếp trên viewport 3D, dựng khối phương án tự tính diện tích sàn, mật độ xây dựng (BCR) & hệ số sử dụng đất (FAR).
- **Xuất Bộ hồ sơ 8 tệp chỉ 1 cú bấm:** CAD `.DXF` 3D, SketchUp `.DAE`, ảnh 4K PNG & 8K Alpha PNG (Photoshop), Báo cáo PDF A3, GIF Timelapse nắng 3D, Laser Cut & Mặt cắt `.SVG/.DXF`.
- **Tự động báo cập nhật ngay trong app:** miễn phí mọi bản vá lỗi & tính năng mới dòng `2.x`; cài đè tự động giữ nguyên bản quyền Pro đã kích hoạt trên máy.

---

## So sánh Bản Free vs Bản Pro (Mua đứt 1 lần · Trọn đời 2.x)

| Tính năng | Bản Free (0đ · Vĩnh viễn) | Bản Pro Trọn đời 2.x (1 Seat = 1 Máy) |
|---|:---:|:---:|
| Xem bản đồ toàn cầu & Nạp khu đất OSM mọi vị trí | ✅ Không giới hạn | ✅ Không giới hạn |
| Khung nhìn 2D / 3D / Tách tầng / Xoay nắng 180Hz / 69 sơ đồ | ✅ Full | ✅ Full |
| Bật/tắt lớp Quy hoạch (2D & 3D) + Xem mặt cắt live | ✅ Full | ✅ Full |
| Xuất CAD `.DXF` 3D, SketchUp `.DAE`, `.GLB`/`.STL`, Laser Cut | 🔒 | ✅ Không giới hạn |
| Xuất ảnh 4K / 8K Alpha PNG, Báo cáo PDF A3, GIF, **Bộ 8 tệp 1-click** | 🔒 | ✅ Không giới hạn |
| Nhập trực tiếp `.skp` / 3D & Dựng khối Massing FAR/BCR | 🔒 | ✅ Không giới hạn |
| Chạy Offline 14 ngày · Tự chuyển máy (2 lần / 6 tháng) | — | ✅ Có sẵn |

- **Đợt 1 · Early Bird (100 suất đầu):** Cá nhân `1 Seat` chỉ **99.000đ** · Nhóm `3 Seats` **249.000đ** · Studio `5 Seats` **399.000đ** · Công ty `10 Seats` **690.000đ**.
- Thanh toán **VietQR** đối soát tự động — nhận mã bản quyền `GA2X-XXXX-XXXX-XXXX` ngay sau 5 giây tại [trang bản quyền chính thức](https://groundatlas-license-server.groundatlas.workers.dev/).

---

## Yêu cầu hệ thống & Cài đặt

- **Hệ điều hành:** Windows 10 / 11 (64-bit), card đồ họa hỗ trợ OpenGL 3.3 trở lên.
- **Tùy chọn 1 — Bộ cài tiêu chuẩn (Khuyên dùng, 20.3 MB):** Tải [`GroundAtlas-Desktop-2.3.1-Setup.exe`](https://github.com/hienkhang2004-coder/GroundAtlas/raw/main/GroundAtlas-Desktop-2.3.1-Setup.exe) và mở chạy trực tiếp — không cần quyền Admin, tự tạo biểu tượng Desktop/Start Menu và liên kết file `.gatlas`.
- **Tùy chọn 2 — Bản Portable không cần cài đặt (27.5 MB):** Tải [`GroundAtlas-Desktop-2.3.1-Portable-Win64.zip`](https://github.com/hienkhang2004-coder/GroundAtlas/raw/main/GroundAtlas-Desktop-2.3.1-Portable-Win64.zip) → giải nén → mở `GroundAtlas.exe` chạy ngay.

### 🛡️ Lưu ý khi Windows hiện cảnh báo xanh (Windows SmartScreen / Smart App Control)

Vì **GroundAtlas Desktop** là phần mềm độc lập mới phát hành chưa gắn chứng chỉ ký số trả phí của Microsoft, lần đầu mở file vừa tải từ mạng Windows có thể hiện màn hình xanh **"Windows protected your PC" (*Unknown publisher*)**. Ứng dụng hoàn toàn sạch 100% (thuần mã máy C++20/Qt6/OpenGL):

1. **Cách nhanh nhất (SmartScreen):** Bấm chữ **`More info` (Thông tin thêm)** → bấm nút **`Run anyway` (Vẫn chạy)** để cài đặt bình thường.
2. **Hoặc bỏ chặn trước khi mở:** Chuột phải vào file vừa tải → chọn **Properties (Thuộc tính)** → ở góc dưới tích ô **`Unblock` (Bỏ chặn)** → bấm **Apply → OK**, rồi mở file (nếu dùng bản `.zip`, hãy `Unblock` file `.zip` trước khi giải nén).
3. **Kiểm chứng toàn vẹn tệp (`SHA-256`) & Quét VirusTotal:**

| Tệp phát hành | Dung lượng | Mã băm `SHA-256` ([`SHA256SUMS.txt`](SHA256SUMS.txt)) | Kiểm tra |
|---|---:|---|---|
| `GroundAtlas-Desktop-2.3.1-Setup.exe` | 20.31 MB | `8a6146c4401466cec472fe34cd34761b6e5b0af43535ae0f657bb4fb381bf338` | [VirusTotal ↗](https://www.virustotal.com/gui/file/8a6146c4401466cec472fe34cd34761b6e5b0af43535ae0f657bb4fb381bf338) |
| `GroundAtlas-Desktop-2.3.1-Portable-Win64.zip` | 27.47 MB | `ca0819beafb04b723f54603a998d314ed54f297b1c7a3ec54d87c685181547ff` | [VirusTotal ↗](https://www.virustotal.com/gui/file/ca0819beafb04b723f54603a998d314ed54f297b1c7a3ec54d87c685181547ff) |

## Giấy phép nguồn mở & Dữ liệu

Chi tiết giấy phép các thư viện nguồn mở được sử dụng (Qt 6.8 LGPLv3 liên kết động, MapLibre Native BSD-2, Monocypher CC0/BSD-2, Earcut ISC, OpenStreetMap ODbL 1.0) xem tại tệp [`LICENSES.txt`](LICENSES.txt).
