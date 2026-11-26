# YarnLoop · by @lenmomam

Nhật ký đan & móc len — web app chạy offline (PWA), dữ liệu chỉ lưu trên máy người dùng.

Mở app: xem mục GitHub Pages của repo này.

## Có gì mới ở v1.1.0
- **Ghi chú row có trường "Số row"**: nhập Từ–Đến thì số row tự tính, hoặc nhập Số row thì Đến tự điền. Số hàng đã đan tự cập nhật theo row lớn nhất đã ghi (nếu bộ đếm đang lớn hơn thì giữ nguyên số của bộ đếm).
- **Mẫu áo tham chiếu**:
  - Lưu số mũi và số đo theo từng size, gauge, len và ảnh sơ đồ của mẫu.
  - Có sẵn bộ mốc chuẩn cho 4 kiểu dựng: bottom-up, top-down raglan, round/European yoke, drop shoulder.
  - Dán text pattern vào là app tự tách các dãy số theo size.
  - Khi gắn mẫu vào dự án, app quy đổi số mũi theo gauge của bạn ở từng mốc (lấy size gần nhất).
- **Chart màu kiểu pixel**:
  - 1 ô = 1 mũi. Vẽ bằng bút, tẩy, đổ màu, đường thẳng, hình chữ nhật; đánh dấu mũi K/P.
  - Hoàn tác, phóng to và dùng 2 ngón để zoom.
  - Nhập ảnh để tự chuyển thành chart; cảnh báo sợi nổi dài hơn 5 mũi; thống kê màu.
  - Xuất PNG, in kèm pattern; hàng đang đan được tô sáng theo Row Counter.
- **Ảnh cuộn len trong kho**: tối đa 4 ảnh cho mỗi loại len, ảnh đầu làm hình đại diện. App lấy màu chủ đạo từ ảnh để gợi ý màu cho chart.
- **Sao lưu** có tuỳ chọn kèm ảnh hoặc không kèm ảnh.
