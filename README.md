Phân Tích Phân Khúc Khách Hàng và Dự Đoán Điểm Chi Tiêu

Giới Thiệu

Đây là dự án bài tập lớn cho học phần Dữ Liệu Lớn tại trường Đại học Đại Nam, Khoa Công Nghệ Thông Tin. Dự án tập trung vào việc phân tích phân khúc khách hàng và dự đoán điểm chi tiêu dựa trên tập dữ liệu từ Kaggle.

Thành Viên Nhóm

Nguyễn Đức Duy - 1671020060

Nguyễn Minh Đức - 1671020089

Nguyễn Tất Toàn - 1671020330

Nguyễn Tiến Dũng - 1671020068

Giảng Viên Hướng Dẫn

TS. Trần Quý Nam

ThS. Lê Thị Thùy Trang

Mục Tiêu Dự Án

Phân tích hành vi tiêu dùng của khách hàng.

Áp dụng mô hình RFM (Recency, Frequency, Monetary) để phân khúc khách hàng.

Xây dựng mô hình hồi quy để dự đoán điểm chi tiêu.

Sử dụng Apache Spark và ngôn ngữ R để xử lý dữ liệu lớn.

Dữ Liệu

Nguồn dữ liệu: Kaggle

Tập dữ liệu: Online Retail

Số lượng mẫu: 143,505

Số biến: 9 (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, TotalPrice)

Công Nghệ Sử Dụng

R và RStudio

Apache Spark (Sparklyr)

Dplyr, ggplot2, caret, Metrics

Hadoop

Các Bước Thực Hiện

1. Tiền Xử Lý Dữ Liệu

Xóa các giá trị thiếu và không hợp lệ.

Tính tổng doanh thu, tần suất và thời gian mua hàng.

2. Phân Tích Phân Khúc Khách Hàng

Áp dụng mô hình RFM.

Nhóm khách hàng theo các phân khúc: VIP, Trung thành, Khách vãng lai, v.v.

Trực quan hóa dữ liệu bằng biểu đồ cột và bản đồ doanh thu.

3. Dự Đoán Điểm Chi Tiêu

Sử dụng mô hình hồi quy tuyến tính.

Đánh giá mô hình bằng các chỉ số: RMSE, MAE, R².

4. Lưu Trữ và Xuất Dữ Liệu

Xuất dữ liệu phân khúc ra file CSV.

Ngắt kết nối Spark để tối ưu tài nguyên.

Kết Quả

Phân tích phân khúc khách hàng chính xác.

Mô hình dự đoán đạt RMSE = 1.094, MAE = 0.934, R² = 0.414.

Ứng Dụng Thực Tiễn

Tối ưu chiến lược tiếp thị.

Dự đoán nhu cầu và hành vi mua sắm.

Nâng cao trải nghiệm khách hàng.

Hướng Dẫn Cài Đặt

Cài đặt R và RStudio.

Cài đặt Apache Spark và thư viện sparklyr.

Chạy các file script R trong thư mục src.

Thông Tin Liên Hệ

Email: duc1608204@gmail.com

Trường Đại học Đại Nam, Khoa Công Nghệ Thông Tin


