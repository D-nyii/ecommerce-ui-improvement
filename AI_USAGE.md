# AI Usage Log

## 1. Công cụ AI
ChatGPT (OpenAI).

## 2. Mục đích sử dụng
- Phân tích yêu cầu khảo sát website thương mại điện tử.
- Đề xuất giao diện thẻ sản phẩm và cách tổ chức HTML5/CSS3.
- Hỗ trợ giải thích mã nguồn, kỹ thuật responsive và các bước kiểm tra.
- Hướng dẫn cấu trúc repository, README và cách công khai mã nguồn trên GitHub.

## 3. Prompt đã sử dụng
Các yêu cầu nguyên văn trong cuộc trò chuyện có liên quan:
- “làm nhiệm vụ 3 giups mình”
- “làm lại chi tiết”
- “làm bài 4”

**Prompt mẫu chi tiết do AI đề xuất để ghi trong báo cáo (không trình bày là câu hỏi nguyên văn đã gửi):**
> Tôi khảo sát website WHOSE STUDIO. Hãy đề xuất thiết kế thẻ sản phẩm thời trang bằng HTML5/CSS3 với ít nhất 4 sản phẩm mẫu; mỗi sản phẩm có ảnh, tên, giá và nút thao tác. CSS phải tách riêng, hỗ trợ giao diện máy tính và điện thoại, không dùng backend. Giải thích các phần mã và cách kiểm tra.

## 4. Kết quả AI đề xuất
- Giao diện 4 thẻ sản phẩm với thông tin rõ ràng, thẻ giảm giá và giá gốc.
- Bố cục thay đổi theo chiều rộng màn hình (4 / 2 / 1 cột).
- Nút **Xem thông tin** dùng phần tử HTML `details` / `summary` không yêu cầu JavaScript.
- Tách mã CSS, dùng SVG minh họa tự tạo và tài liệu README.

## 5. Kiểm tra và điều chỉnh (SINH VIÊN TỰ ĐIỀN SAU KHI THỰC HIỆN)
- Tôi đã mở website trên trình duyệt: **[ĐIỀN]**
- Tôi kiểm tra trên thiết bị / chiều rộng màn hình: **[ĐIỀN]**
- Vấn đề tôi phát hiện: **[ĐIỀN]**
- Tôi đã chỉnh sửa: **[ĐIỀN TÊN FILE, THUỘC TÍNH, TRƯỚC/SAU]**
- Kết quả quan sát sau khi sửa: **[ĐIỀN]**
- Nội dung AI đề xuất tôi không sử dụng hoặc đã điều chỉnh: **[ĐIỀN]**

## 6. Phần tôi hiểu và có thể giải thích
- `article`: đánh dấu một thẻ sản phẩm độc lập.
- `img` + `alt`: hiển thị và mô tả ảnh.
- `strong` / `del`: trình bày giá bán mới / giá gốc.
- `details` / `summary`: xem thêm thông tin mà không cần JavaScript.
- CSS Grid (`display: grid`, `grid-template-columns`): chia cột sản phẩm.
- `@media`: điều chỉnh bố cục trên thiết bị khác nhau.

> Trước khi nộp bài, thay toàn bộ **[ĐIỀN]** bằng trải nghiệm và chỉnh sửa thật. Không xem nội dung AI là kết quả tự kiểm tra nếu chưa chạy thử.
