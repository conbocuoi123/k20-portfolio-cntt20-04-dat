# Nhật ký sửa lỗi

## Ảnh đại diện không hiển thị
- **Hiện tượng:** Trang portfolio không hiển thị ảnh và đường dẫn ảnh không đúng.
- **Nguyên nhân:** `index.html` chưa có thẻ ảnh; dự án cũng chưa có thư mục hoặc tệp ảnh.
- **Cách sửa:** Thêm ảnh minh họa SVG tại `images/avatar.svg` và tham chiếu bằng đường dẫn tương đối `images/avatar.svg` từ `index.html`. Thêm bố cục ảnh đáp ứng trên màn hình nhỏ và mô tả thay thế cho trình đọc màn hình.
- **Kiểm tra:** Đường dẫn `index.html` → `images/avatar.svg` tồn tại; ảnh SVG dùng đường dẫn tương đối, không phụ thuộc máy chủ hay kết nối mạng.
- **Lưu ý:** Đây là ảnh minh họa. Có thể thay `images/avatar.svg` bằng ảnh cá nhân và cập nhật `src` trong `index.html` nếu muốn dùng ảnh thật.
