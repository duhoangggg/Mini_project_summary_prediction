# 🚲 Bike_Rental_Demand_Forecasting_using_Regression  
(Dự đoán nhu cầu thuê xe đạp bằng mô hình hồi quy)

## 🧾 Project Description | Mô tả dự án

This project uses bike rental data to **predict the number of rented bikes (`cnt`)** in a city.  
(Dự án sử dụng dữ liệu thuê xe đạp để **dự đoán số lượt thuê xe (`cnt`)** trong thành phố.)

Bike sharing systems help:
- Reduce traffic
- Protect the environment
- Improve public health

(Hệ thống xe đạp công cộng giúp:
- Giảm tắc đường  
- Bảo vệ môi trường  
- Cải thiện sức khỏe cộng đồng)

The system records: time, weather, weekday, season, and number of users.  
→ It works like a **sensor** for city mobility!  
(Hệ thống này ghi lại dữ liệu thời gian, thời tiết, ngày trong tuần, mùa,...  
→ Hoạt động như một **bộ cảm biến** giúp theo dõi sự di chuyển trong thành phố.)

📥 **Dataset link:**  
https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset

---

## 📊 Dataset Information | Thông tin dữ liệu

📁 2 file chính: `day.csv` và `hour.csv`  
(day.csv cho theo ngày, hour.csv cho theo giờ)

| Column | Meaning | Giải thích |
|--------|---------|------------|
| `instant` | Row ID | ID dòng dữ liệu |
| `dteday` | Date | Ngày |
| `season` | Season | Mùa (1–4) |
| `yr` | Year | Năm (0 = 2011, 1 = 2012) |
| `mnth` | Month | Tháng |
| `hr` | Hour | Giờ (chỉ trong hour.csv) |
| `holiday` | Is holiday | Có phải ngày nghỉ lễ không |
| `weekday` | Weekday | Thứ trong tuần |
| `workingday` | Is working day | Ngày làm việc |
| `weathersit` | Weather situation | Thời tiết (1–4) |
| `temp` | Normalized temp | Nhiệt độ chuẩn hóa |
| `atemp` | Feels-like temp | Nhiệt độ cảm nhận |
| `hum` | Humidity | Độ ẩm (chuẩn hóa) |
| `windspeed` | Wind speed | Gió (chuẩn hóa) |
| `casual` | Casual users | Người thuê không đăng ký |
| `registered` | Registered users | Người dùng đăng ký |
| `cnt` | 🔥 Total users | **Tổng số lượt thuê xe (biến cần dự đoán)**

---

## 🛠️ Libraries used | Thư viện sử dụng

- `pandas` → xử lý dữ liệu  
- `matplotlib`, `seaborn` → trực quan hóa dữ liệu  
- `scikit-learn` → huấn luyện mô hình

---

## 🧠 Algorithms used | Thuật toán sử dụng

- Linear Regression  
- Ridge  
- Huber Regressor  
- ElasticNet  
- Gradient Boosting  
- Decision Tree  
- Random Forest  
- Extra Trees

---

## 📉 Model Evaluation | Đánh giá mô hình

- Metric: **Mean Squared Error (MSE)**  
- Result: **0.3890**

---

## 🎯 Real-world Use Case | Ứng dụng thực tế

✅ Thành phố hoặc doanh nghiệp có thể dùng để:
- Dự đoán nhu cầu thuê xe theo giờ/ngày  
- Quản lý phân bổ xe tại các trạm  
- Quy hoạch giao thông, giảm tắc nghẽn

(City or business can:
- Predict bike demand by hour/day  
- Manage bike supply per station  
- Plan better traffic systems)

