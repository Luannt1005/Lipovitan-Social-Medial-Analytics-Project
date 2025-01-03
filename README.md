# README: Social Media Data Analytics for Lipovitan

## 1. Giới thiệu Dự án

Dự án này nhằm phân tích dữ liệu truyền thông xã hội của thương hiệu **Lipovitan** thông qua các nền tảng YouTube, Facebook, và TikTok. Chúng tôi sử dụng các phương pháp xử lý dữ liệu, phân tích dữ liệu thăm dò (EDA), và mô hình học sâu để thực hiện phân tích cảm xúc và đưa ra các gợi ý cải tiến chiến lược truyền thông.

---

## 2. Nội dung Dự án

### Chương 1: Giới thiệu về Lipovitan
- Tổng quan về thương hiệu Lipovitan.
- Phân tích đối thủ cạnh tranh chính: Red Bull, Monster Energy, Rockstar.
- Chiến lược kênh truyền thông của Lipovitan: Owned Media, Paid Media, Earned Media.

### Chương 2: Xử lý dữ liệu và EDA
- **YouTube:** Xử lý dữ liệu video, phân tích lượng tương tác (views, likes, comments), biểu đồ từ khoá.
- **Facebook:** Làm sạch dữ liệu bài đăng, phân tích xu hướng tương tác qua thời gian và các ngày trong tuần.
- **TikTok:** Phân tích dữ liệu bình luận, phân phối chiều dài bình luận, và mối quan hệ giữa các chỉ số tương tác.

### Chương 3: Phân tích cảm xúc
- Sử dụng mô hình PhoBERT để phân tích cảm xúc (positive, neutral, negative) từ các bình luận trên Facebook, YouTube, TikTok.
- Đánh giá xu hướng cảm xúc qua thời gian.

### Chương 4: Gợi ý và Kết luận
- Tổng kết kết quả đạt được.
- Đánh giá các hạn chế và đề xuất cải tiến.
- Định hướng nghiên cứu và ứng dụng trong tương lai.

---

## 3. Công cụ và Công nghệ

- **Python**: pandas, matplotlib, seaborn, NLP libraries (PhoBERT, Hugging Face).
- **Công cụ crawl dữ liệu**: Selenium, Google API, Apify.
- **Nền tảng phân tích**: Jupyter Notebook.

---

## 4. Quy trình Thực hiện

1. **Thu thập Dữ liệu**:
   - Sử dụng API và các công cụ tự động hoá để lấy dữ liệu từ YouTube, Facebook, TikTok.
2. **Xử lý Dữ liệu**:
   - Làm sạch dữ liệu, chuẩn hoá định dạng ngày tháng, xử lý giá trị thiếu.
3. **Phân tích Thăm dò (EDA)**:
   - Khám phá và trực quan hoá dữ liệu để tìm ra các mẫu và xu hướng.
4. **Phân tích Cảm xúc**:
   - Sử dụng PhoBERT để phân tích cảm xúc từ bình luận.
5. **Đề xuất Chiến lược**:
   - Đưa ra gợi ý cải thiện chiến lược truyền thông dựa trên phân tích.

---

## 5. Kết quả Dự án

- **YouTube**: Các video của Lipovitan có lượng tương tác cao vào các dịp đặc biệt như Tết Nguyên Đán.
- **Facebook**: Tương tác cao nhất vào giữa tuần (Thứ Ba, Thứ Tư). 
- **TikTok**: Bình luận chủ yếu ngắn, với nhiều ý kiến trái chiều.
- **Phân tích cảm xúc**: Đa số bình luận tích cực, tuy nhiên có một số điểm cần cải thiện.

---

## 6. Hạn chế và Định hướng Tương Lai

### Hạn chế:
- Dữ liệu thu thập từ TikTok có thể chưa đầy đủ.
- Mô hình phân tích cảm xúc có thể cần cải thiện độ chính xác.

### Định hướng:
- Mở rộng thu thập dữ liệu từ các kênh khác như Instagram, Twitter.
- Tích hợp thêm mô hình học sâu tiên tiến để phân tích ngữ nghĩa.

---

