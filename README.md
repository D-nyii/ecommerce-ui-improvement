# E-commerce UI Improvement — WHOSE STUDIO (tham khảo)

## 1. Giới thiệu
Bài tập cá nhân Chương 1 — môn Phát triển ứng dụng WEB/TMĐT. Dự án thiết kế **giao diện thẻ sản phẩm thời trang mô phỏng** bằng HTML5/CSS3, lấy cảm hứng từ việc khảo sát website WHOSE STUDIO.

> Đây là sản phẩm học tập độc lập; **không phải** website chính thức của WHOSE STUDIO. Tên, giá và ảnh sản phẩm trong giao diện là **dữ liệu minh họa**, không sao chép mã nguồn hoặc hình ảnh của thương hiệu.

## 2. Website tham khảo
- **Tên:** WHOSE STUDIO
- **URL:** https://whosestudio.vn/
- **Các khu vực cần khảo sát:** trang chủ; danh mục sản phẩm; chi tiết sản phẩm; tìm kiếm; giỏ hàng.
- **Khu vực lựa chọn cải tiến:** thẻ sản phẩm trong danh sách sản phẩm.

## 3. Chức năng
- Giao diện minh họa **4 sản phẩm thời trang** (áo thun, hoodie, quần jeans, áo khoác).
- Mỗi thẻ có hình ảnh, tên, mô tả, giá bán, giá gốc, nhãn giảm giá và nút **Xem thông tin**.
- Thao tác **Xem thông tin** mở nội dung ngay trong thẻ bằng HTML `details`/`summary`.
- Bố cục **responsive**: 4 cột trên desktop, 2 cột trên tablet và 1 cột trên điện thoại nhỏ.
- Chưa triển khai giỏ hàng thật, thanh toán, đăng nhập, backend hoặc cơ sở dữ liệu.

## 4. Công nghệ
- HTML5 (cấu trúc nội dung).
- CSS3 (CSS Grid, Flexbox, Media Queries).
- Hình minh họa SVG tự dựng, lưu nội bộ tại `images/`.

## 5. Cách chạy
1. Tải hoặc clone repository.
2. Mở file **`index.html`** bằng Chrome, Edge hoặc trình duyệt thông dụng.
3. Kiểm tra 4 sản phẩm, ảnh, giá và nút **Xem thông tin**.
4. Để xem dạng điện thoại: nhấn `F12` → chọn biểu tượng thiết bị → thử chiều rộng 390px; thử thêm 820px và máy tính.

**Cấu trúc thư mục**

```text
ecommerce-ui-improvement/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── tshirt.svg
│   ├── hoodie.svg
│   ├── jeans.svg
│   └── jacket.svg
├── README.md
└── AI_USAGE.md
```

## 6. Cải tiến đã thực hiện
- Trình bày thẻ sản phẩm đồng nhất, dễ quét thông tin.
- Nhấn mạnh giá mới; gạch ngang giá gốc và hiển thị phần trăm giảm giá.
- Tối ưu lại bố cục theo kích thước màn hình.

**Phần tự kiểm tra và điều chỉnh của sinh viên (phải điền trước khi nộp):**
- Vấn đề tự phát hiện: **[ĐIỀN]**
- Mã HTML/CSS đã sửa: **[ĐIỀN]**
- Kết quả sau sửa: **[ĐIỀN]**

## 7. Hỗ trợ từ AI
ChatGPT đã hỗ trợ phân tích yêu cầu, đề xuất bố cục và giải thích mã nguồn HTML/CSS. Tôi cần tự chạy website, đối chiếu, đánh giá và điều chỉnh mã theo thực tế. Chi tiết prompt và quá trình kiểm tra được ghi trong [`AI_USAGE.md`](AI_USAGE.md).

## 8. Liên kết sau khi đăng (bổ sung khi đã xuất bản)
- **GitHub repository:** [ĐIỀN LINK SAU KHI TẠO]
- **GitHub Pages:** [ĐIỀN LINK SAU KHI BẬT PAGES]

## 9. Lưu ý về quyền riêng tư
Repository được thiết lập Public để giảng viên xem mã nguồn. Không đăng mật khẩu, token hoặc thông tin cá nhân nhạy cảm.
