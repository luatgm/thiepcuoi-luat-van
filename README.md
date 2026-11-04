# Thiệp cưới Minh Luật & Đỗ Vân

Website tĩnh HTML/CSS/JavaScript, dựng lại giao diện từ ảnh tham khảo bằng code (không dùng ảnh thiệp gốc). Hai hình PNG trong `assets/` là QR được tạo mới để mở Google Maps.

## Deploy GitHub Pages

1. Tạo repository GitHub, ví dụ `thiep-cuoi`.
2. Upload **nội dung bên trong** thư mục này lên nhánh `main` tại root của repository (`index.html`, `style.css`, `script.js`, `assets/`).
3. Vào **Settings → Pages → Build and deployment → Deploy from a branch**; chọn `main` và `/ (root)`, rồi **Save**.
4. Sau khi GitHub Pages xuất bản, truy cập:
   - `https://USERNAME.github.io/thiep-cuoi/?side=trai`
   - `https://USERNAME.github.io/thiep-cuoi/?side=gai`

Thay `USERNAME` và `thiep-cuoi` bằng tên tài khoản/repository thực tế.

## Tuỳ chỉnh

- `script.js`: đối tượng `DATA` chứa tên, địa chỉ, thời gian và tên bố mẹ.
- `style.css`: bố cục, màu sắc, font chữ, hiệu ứng phong bì và responsive.
- `index.html`: khung HTML.
- `assets/qr-trai.png` và `assets/qr-gai.png`: QR chỉ đường đã tạo mới. Nếu thay đổi địa chỉ, hãy tạo lại QR tương ứng (link nút Google Maps được lấy từ `mapAddress` trong `script.js`).

**Lưu ý:** QR đang trỏ tới tìm kiếm địa chỉ trên Google Maps, chưa xác nhận ghim vị trí chính xác. Font sử dụng Google Fonts nên cần kết nối mạng để hiện giống mẫu nhất.
