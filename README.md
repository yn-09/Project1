# Project1
Phân tích rủi ro tín dụng
## Đóng góp cá nhân

Trong dự án nhóm, tôi phụ trách **câu 3, 4 của phần 1**, tập trung vào xây dựng, đánh giá và so sánh các mô hình dự đoán lãi suất khoản vay.

### 3. Xây dựng mô hình hồi quy tuyến tính

* Xây dựng mô hình **hồi quy tuyến tính đa biến** để dự đoán biến mục tiêu `int_rate`.
* Kiểm tra các giả định của mô hình thông qua:

  * Histogram và Q-Q Plot của phần dư.
  * Kiểm định **Shapiro-Wilk**.
  * Phân tích hiện tượng đa cộng tuyến bằng **Variance Inflation Factor (VIF)**.
* Thực hiện **Feature Engineering**, bao gồm xây dựng biến tương tác và biến đổi logarit đối với một số biến phù hợp.
* Áp dụng **Ridge Regression** và **Lasso Regression** nhằm hạn chế overfitting và ảnh hưởng của đa cộng tuyến.
* Sử dụng **K-Fold Cross Validation** để đánh giá độ ổn định của mô hình.
* Đánh giá mô hình bằng các chỉ số **R², MAE và RMSE**.

### 4. So sánh với các mô hình học máy phi tuyến

* Xây dựng mô hình **Random Forest** và **XGBoost** để dự đoán `int_rate`.
* Thực hiện tối ưu hóa một số siêu tham số của mô hình.
* Phân tích và trực quan hóa **Feature Importance** để xác định các đặc trưng có ảnh hưởng đến kết quả dự đoán.
* So sánh hiệu quả giữa các mô hình hồi quy tuyến tính và mô hình học máy phi tuyến dựa trên **R², MAE và RMSE**.
* Đánh giá sự khác biệt về khả năng dự đoán và tổng quát hóa giữa các mô hình.
