# Thiệp cưới Minh Luật & Đỗ Vân — GitHub Pages

Website viết bằng HTML, CSS, JavaScript; không sử dụng ảnh chụp thiệp mẫu. Phần QR sử dụng ảnh mã QR tạo sẵn trong `assets/`.

## Các trang
- `index.html`: trang quản lý, nhập tên khách (mỗi dòng một tên), tạo link, sao chép hoặc xuất CSV.
- `nha-trai.html`: thiệp nhà trai.
- `nha-gai.html`: thiệp nhà gái.
- `script.js`: nội dung và chuyển 5 trang thiệp.
- `style.css`: giao diện.
- `generator.js`: tạo link cá nhân hóa.

## Triển khai GitHub Pages
Upload **toàn bộ file và thư mục bên trong** ZIP lên root của repository, vào Settings > Pages > Deploy from a branch > main / (root).

Ví dụ nếu URL website là `https://username.github.io/thiep-cuoi/`:
- Trang tạo link: `https://username.github.io/thiep-cuoi/`
- Nhà trai: `https://username.github.io/thiep-cuoi/nha-trai.html`
- Nhà gái: `https://username.github.io/thiep-cuoi/nha-gai.html`
- Khách riêng: `https://username.github.io/thiep-cuoi/nha-trai.html?to=Anh%20Nguyen%20Van%20A`

Trang `index.html` là công cụ tạo link, không có đăng nhập. Nếu không muốn khách truy cập trang quản lý, hãy tách công cụ sang repository riêng hoặc thêm xác thực bằng dịch vụ phù hợp. Tên khách nằm trong URL và có thể nhìn thấy khi chia sẻ; không dùng cho dữ liệu nhạy cảm. GitHub Pages là hosting tĩnh, không tự gửi tin nhắn đến khách.

Mã QR trong `assets` hiện là đường chỉ dẫn theo địa chỉ tìm kiếm; cần kiểm tra lại điểm đến chính xác trước khi phát thiệp.


## V3
- Monogram L ♥ V.
- Tên hai người trên phong bì luôn nằm ở hai dòng riêng.
- Ba tờ thiệp bên trong phong bì có thông tin xem trước và hiệu ứng nổi nhẹ.
- Trang tiệc giảm cỡ chữ và giữ đủ tên bố mẹ hai bên.

## V5
- Đồng bộ toàn bộ chữ lồng thành **L ♥ V**.
- Trang phong bì: tên thứ nhất và thứ hai nằm trên hai dòng riêng, không tách chữ **Đỗ Vân**.
- Thêm cache-busting `?v=5` cho CSS và JS.
