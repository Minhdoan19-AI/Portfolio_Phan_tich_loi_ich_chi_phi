# 📊 Phân tích Chi phí - Lợi ích (Cost-Benefit Analysis) cho Dự án Công

Kho lưu trữ này tổng hợp các mô hình Phân tích Chi phí - Lợi ích (CBA) nhằm đánh giá tính khả thi kinh tế của các dự án đầu tư cơ sở hạ tầng công cộng và môi trường. Các báo cáo tập trung vào việc tính toán dòng tiền, xác định chi phí cơ hội, định giá ngoại ứng (externalities) và phân tích các chỉ số tài chính cốt lõi nhằm hỗ trợ ra quyết định phân bổ ngân sách tối ưu.

## 🎯 Kỹ năng & Phương pháp áp dụng
*   **Mô hình hóa tài chính:** Xây dựng bảng dòng tiền chiết khấu (DCF) cho các dự án dài hạn (8-10 năm).
*   **Phân tích Kinh tế Công:** Chuyển đổi từ giá tài chính sang giá kinh tế (Shadow pricing), bóc tách các khoản thuế/trợ cấp, và tính toán chi phí cơ hội của lao động, đất đai.
*   **Đánh giá Ngoại ứng Môi trường:** Lượng hóa giá trị giảm phát thải khí nhà kính, chi phí khắc phục ô nhiễm và thặng dư tiêu dùng (Willingness to Pay - WTP).
*   **Chỉ số đo lường:** Net Present Value (NPV), Benefit-Cost Ratio (B/C).

## 📂 Danh mục Dự án

### 1. 💧 Dự án Đầu tư Trạm Xử lý Nước sạch 
*   **File dự án:** [`Phan_Tich_CBA_Du_An_De01.xlsx`](./Phan_Tich_CBA_Du_An_De01.xlsx)
*   **Mục tiêu:** Đánh giá tính khả thi kinh tế của trạm xử lý nước sạch công suất 1,2 triệu m³/năm phục vụ dân sinh trong vòng 10 năm.
*   **Điểm nhấn phân tích:**
    *   Tính toán thặng dư tiêu dùng dựa trên mức giá sẵn lòng trả (WTP) của người dân so với các nguồn nước thay thế đắt đỏ (nước giếng, xe bồn).
    *   Phân tích chi phí kinh tế của các nhóm lao động khác nhau (lao động nông nhàn, lao động thất nghiệp).
    *   Xác định giá kinh tế thực tế cho mỗi m³ nước sạch được cung cấp ra thị trường.

### 2. ☀️ Dự án Điện mặt trời áp mái cho Bệnh viện Công
*   **File dự án:** [`Phan_Tich_CBA_Du_An_De02.xlsx`](./Phan_Tich_CBA_Du_An_De02.xlsx)
*   **Mục tiêu:** Thẩm định dự án lắp đặt hệ thống điện mặt trời 2 MWp với vòng đời 8 năm nhằm nâng cao năng lực tự chủ năng lượng cho bệnh viện.
*   **Điểm nhấn phân tích:**
    *   Lượng hóa lợi ích môi trường thông qua việc tính toán lượng phát thải CO2 tránh được (0,75 kg CO2/kWh) và quy đổi thành giá trị kinh tế.
    *   Đánh giá lợi ích từ việc thay thế điện lưới và giá trị thặng dư khi mở rộng khả năng vận hành các thiết bị y tế chuyên dụng (kho lạnh dược phẩm, thiết bị phụ trợ).
    *   Tính toán chi phí quy dẫn và giá kinh tế của mỗi kWh điện mặt trời tạo ra.

### 3. ♻️ Dự án Trung tâm Xử lý Rác thải Sinh hoạt
*   **File dự án:** [`Phan_Tich_CBA_Du_An_De03.xlsx`](./Phan_Tich_CBA_Du_An_De03.xlsx)
*   **Mục tiêu:** Đánh giá hiệu quả kinh tế của trung tâm thu gom, phân loại và ủ compost (công suất 28.000 tấn/năm) nhằm giải quyết tình trạng quá tải tại các bãi chôn lấp lộ thiên.
*   **Điểm nhấn phân tích:**
    *   Lượng hóa chi phí cơ hội của quỹ đất và phần chi phí tiết kiệm được từ việc không phải khắc phục ô nhiễm môi trường do bãi rác cũ gây ra.
    *   Đưa mô hình kinh tế tuần hoàn vào dòng tiền thông qua doanh thu từ phụ phẩm (phân compost và phế liệu tái chế).
    *   Xác định mức giá kinh tế thực tế cho mỗi tấn rác được thu gom và xử lý an toàn.

## 🛠 Công cụ sử dụng
*   **Microsoft Excel:** Xây dựng cấu trúc Bảng thông số (Parameter Dashboard), hệ thống Bảng tính chi tiết cấu phần chi phí/lợi ích và tự động hóa kết xuất các chỉ số thẩm định (NPV, B/C).
