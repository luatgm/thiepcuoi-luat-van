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

Mã QR trong `assets` là hai ảnh QR do gia đình cung cấp. Nút Mở Google Maps vẫn dùng tìm kiếm địa chỉ; hãy kiểm tra QR và nút dẫn đến đúng địa điểm trước khi gửi thiệp.


## V3
- Monogram L ♥ V.
- Tên hai người trên phong bì luôn nằm ở hai dòng riêng.
- Ba tờ thiệp bên trong phong bì có thông tin xem trước và hiệu ứng nổi nhẹ.
- Trang tiệc giảm cỡ chữ và giữ đủ tên bố mẹ hai bên.

## V5
- Đồng bộ toàn bộ chữ lồng thành **L ♥ V**.
- Trang phong bì: tên thứ nhất và thứ hai nằm trên hai dòng riêng, không tách chữ **Đỗ Vân**.
- Thêm cache-busting `?v=5` cho CSS và JS.


## V6
Tên khách mời ở trang phong bì và tờ tiệc được căn giữa, dùng font Great Vibes màu đen.

## V7
- Thay ảnh QR của nhà trai và nhà gái bằng ảnh gia đình gửi.
- Sửa địa chỉ nhà gái thành **Số 30 Đường Đằng Tây**.
- Sửa tên mẹ cô dâu thành **Vương Thị Diên**.
- Tăng phiên bản tài nguyên lên v7.


## V8 – Google Maps trực tiếp

Mã QR được tạo từ đúng link Google Maps, không phải từ địa chỉ tìm kiếm. Nút Mở Google Maps trên trang cuối sử dụng cùng link.

- Nhà trai: https://maps.app.goo.gl/JpreXPfAyLoFNaKdA
- Nhà gái: https://maps.app.goo.gl/YMVATYxZhu6Zjr1p9

Khi cập nhật GitHub Pages, nhớ ghi đè cả hai ảnh trong `assets/`.


## V9 – Lịch ở trang 2
Tờ thiệp phía trước phong bì hiển thị lịch tháng 11/2026, khoanh ngày 28 (Tiệc cưới) và 29 (Lễ cưới). Dựng hoàn toàn bằng HTML/CSS, giữ các trang còn lại.


## V10
Page 2: lịch SAVE THE DATE theo bố cục ảnh tham khảo, chữ dọc, tên viết tay, lịch November 2026 với dấu trái tim ở 28 và 29. Giữ màu hồng đỏ của project; dựng bằng HTML/CSS.
