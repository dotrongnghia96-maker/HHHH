THIỆP CƯỚI ONLINE – MẪU ANIMATION

TÍNH NĂNG
- Phong bì 3D và con dấu sáp.
- Hiệu ứng sao, cánh hoa rơi bằng Canvas.
- Parallax ảnh bìa, thanh tiến trình cuộn.
- Reveal animation khi cuộn trang.
- Hiệu ứng gõ chữ.
- Card sự kiện nghiêng 3D theo chuột.
- Đếm ngược ngày cưới.
- Album masonry và lightbox toàn màn hình.
- Nút tạo file lịch .ICS.
- Form RSVP bản demo.
- Cá nhân hóa khách mời bằng đường dẫn.
- Nút chia sẻ thiệp và modal thông tin mừng cưới.
- Hỗ trợ chế độ giảm chuyển động của thiết bị.

CÁCH DÙNG
1. Mở index.html bằng trình duyệt.
2. Mở index.html bằng Visual Studio Code và tìm:
   const weddingConfig = {
3. Sửa tên, ngày giờ, địa chỉ và đường dẫn bản đồ trong weddingConfig.
4. Thêm nhạc:
   - Chép file MP3 vào assets/music.mp3
5. Thay ảnh:
   - Tìm các đường dẫn https://images.unsplash.com/... trong index.html.
   - Đổi thành assets/ten-anh.jpg.
6. Cá nhân hóa khách mời:
   - Sau khi đăng website, thêm ?guest=Tên%20Khách vào cuối đường dẫn.
   - Ví dụ: https://tenmien.com/?guest=Nguyễn%20Văn%20A
7. Form RSVP hiện chỉ lưu vào localStorage của trình duyệt.
   Dùng thật cần nối với Google Forms, Google Apps Script, Formspree hoặc API riêng.
8. Thay số tài khoản:
   - Tìm groomAccount và brideAccount trong HTML.
9. Không muốn hiện phần mừng cưới:
   - Xóa section có class="gift-note" và div id="giftModal".

ĐƯA LÊN MẠNG
- Có thể dùng GitHub Pages, Netlify, Cloudflare Pages hoặc hosting tĩnh.
- File trang chủ cần giữ tên index.html.
- Nên nén ảnh về WebP/JPG dưới khoảng 500 KB mỗi ảnh để tải nhanh.
