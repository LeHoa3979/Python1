# Dự đoán giá cổ phiếu VNM bằng Machine Learning

## Tổng quan dự án
Dự án này nhằm xây dựng một mô hình machine learning có khả năng **dự đoán giá cổ phiếu VNM vào ngày hôm sau** dựa trên dữ liệu lịch sử. Mô hình được kiểm chứng bằng **17 năm dữ liệu lịch sử** để đảm bảo độ tin cậy và độ chính xác trong dự đoán.

## Tính năng
- **Mô phỏng dữ liệu lịch sử cho cổ phiếu VNM**
- **Làm sạch và trực quan hóa dữ liệu**
- **Huấn luyện mô hình machine learning để dự đoán giá**
- **Đánh giá sai số và kiểm định mô hình trong 17 năm**
- **Cải thiện mô hình với các đặc trưng dự báo bổ sung**

## Quy trình thực hiện
1. **Tải dữ liệu lịch sử cổ phiếu VNM**
2. **Làm sạch & trực quan hóa dữ liệu**: Loại bỏ điểm bất thường và hiển thị xu hướng
3. **Đặt mục tiêu ML & huấn luyện mô hình ban đầu**
4. **Đánh giá sai số & kiểm định mô hình**: Đo lường độ chính xác qua thời gian dài
5. **Cải tiến mô hình với các đặc trưng bổ sung**

## Công nghệ sử dụng
- **Python**
- **Pandas, NumPy** (Xử lý dữ liệu)
- **Matplotlib, Seaborn** (Trực quan hóa dữ liệu)
- **Scikit-learn** (Mô hình machine learning)
- **Backtesting framework** (Xác thực mô hình)

## Bắt đầu sử dụng
### Yêu cầu hệ thống
Đảm bảo bạn đã cài đặt:
- Python 3.x
- Các thư viện cần thiết (cài đặt bằng `pip install -r requirements.txt`)

### Cài đặt
1. Tải mã nguồn từ GitHub:
   ```sh
   git clone https://github.com/your-repo/vnm-stock-prediction.git
   cd vnm-stock-prediction

## Kết quả & Đánh giá
Dự án bao gồm **phân tích backtesting** để đánh giá hiệu suất của mô hình trong suốt 17 năm, đảm bảo độ tin cậy cho các dự đoán.

## Cải tiến trong tương lai
- Tích hợp **mô hình deep learning** để cải thiện độ chính xác
- Bổ sung **các chỉ số kinh tế vĩ mô** để tăng khả năng dự đoán
- Triển khai **cập nhật dữ liệu theo thời gian thực**

## Tham khảo
- Historical stock data sourced from [VanEck Vectors Vietnam ETF (VNM ETF)]
- [Predict The Stock Market With Machine Learning And Python](https://www.youtube.com/watch?v=1O_BenficgE)

## License
This project is licensed under the MIT License.

