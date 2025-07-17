# 🏠 Boston_Housing_Price_Prediction_using_Regression  
(Dự đoán giá nhà Boston bằng mô hình hồi quy)

## 🧾 Project Description | Mô tả dự án

We use real data from **Boston in 1978** to **predict house prices (`MEDV`)** based on features like crime rate, number of rooms, tax, etc.  
(Chúng ta sử dụng dữ liệu thực tế tại **Boston năm 1978** để **dự đoán giá nhà** dựa trên các yếu tố như tỉ lệ tội phạm, số phòng, thuế,...)

🎯 Mục tiêu: Giúp hiểu rõ **yếu tố nào ảnh hưởng đến giá nhà**, từ đó hỗ trợ mua, bán, đầu tư hoặc quy hoạch đô thị.

📥 **Dataset link:** [Kaggle – Boston Housing](https://www.kaggle.com/puxama/bostoncsv)

---

## 📊 Dataset Information | Thông tin dữ liệu

Tổng cộng **506 mẫu dữ liệu**, gồm **14 cột**:

| Column | Meaning | Giải thích |
|--------|---------|------------|
| `CRIM` | Crime rate | Tỉ lệ tội phạm |
| `ZN` | Large lot % | Diện tích đất dân cư lớn |
| `INDUS` | Industry land % | Tỉ lệ đất công nghiệp |
| `CHAS` | Near Charles River | Gần sông Charles (1 = Có) |
| `NOX` | Pollution (NOx) | Mức độ ô nhiễm khí NOx |
| `RM` | Rooms | Số phòng trung bình |
| `AGE` | Old houses % | % nhà xây trước 1940 |
| `DIS` | Distance to jobs | Khoảng cách đến trung tâm việc làm |
| `RAD` | Highway access | Mức độ gần đường lớn |
| `TAX` | Property tax | Thuế tài sản |
| `PTRATIO` | Student-teacher ratio | Tỉ lệ học sinh/giáo viên |
| `B` | Black population score | Thể hiện sắc tộc (công thức đặc biệt) |
| `LSTAT` | Lower class % | % dân cư có thu nhập thấp |
| `MEDV` | 🔥 Median house price | **Giá nhà trung bình (cần dự đoán)**

---

## 🛠️ Libraries used | Thư viện sử dụng

- `pandas` → xử lý dữ liệu  
- `matplotlib`, `seaborn` → vẽ biểu đồ  
- `scikit-learn` → mô hình học máy  
- `xgboost` → thuật toán nâng cao

---

## 🧠 Algorithms used | Thuật toán sử dụng

- Linear Regression  
- Decision Tree  
- Random Forest  
- Extra Trees  
- XGBoost

---

## 📉 Model Evaluation | Đánh giá mô hình

- Metric: **Mean Squared Error (MSE)**  
- Result: **10.0** (lower is better)

---

## 🎯 Real-world Use Case | Ứng dụng thực tế

✅ Dự án giúp:
- Dự đoán giá nhà dựa vào vị trí, môi trường, cơ sở hạ tầng  
- Hỗ trợ người mua, người bán hoặc nhà đầu tư ra quyết định  
- Phân tích quy hoạch đô thị, chính sách nhà ở

(Real estate agents, buyers or city planners can use this to:
- Predict home prices  
- Evaluate impact of location/environment on price  
- Support better housing policy or investment)

