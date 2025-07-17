# 🚄 JetRail_Traffic_Forecasting_using_Time_Series  
(Dự báo lưu lượng hành khách JetRail bằng phân tích chuỗi thời gian)

## 🧾 Project Description | Mô tả dự án

Unicorn Ventures is considering investment in **JetRail**, a new high-speed rail system using jet propulsion.  
(Unicorn Ventures đang xem xét đầu tư vào **JetRail**, một hệ thống tàu cao tốc sử dụng công nghệ phản lực.)

🎯 Goal: **Forecast monthly traffic for the next 7 months**  
→ So they can decide whether JetRail will **reach 1 million users/month in 18 months**.  
(Mục tiêu: **Dự đoán số lượt hành khách trong 7 tháng tới**  
→ Để quyết định JetRail có đạt được **1 triệu lượt/tháng trong 18 tháng tới hay không**.)

📥 **Dataset link:**  
https://datahack.analyticsvidhya.com/contest/practice-problem-time-series-2/

---

## 📊 Dataset Information | Thông tin dữ liệu

| Column | Meaning | Giải thích |
|--------|---------|------------|
| `Datetime` | Date & time | Ngày và giờ |
| `Count` | 🔥 Number of users | **Số lượt hành khách mỗi giờ** (biến cần dự đoán)

---

## 🛠️ Libraries used | Thư viện sử dụng

- `pandas` → xử lý dữ liệu  
- `matplotlib`, `seaborn` → vẽ biểu đồ trực quan  
- `scikit-learn` → tiền xử lý  
- `fbprophet` → mô hình dự báo chuỗi thời gian

---

## 🧠 Algorithm used | Thuật toán sử dụng

- **Facebook Prophet**:  
→ A powerful tool for time series forecasting by Facebook  
(Một công cụ mạnh để dự báo chuỗi thời gian do Facebook phát triển)

---

## 🎯 Real-world Use Case | Ứng dụng thực tế

✅ Dự án giúp:
- Dự đoán lượng hành khách tương lai  
- Hỗ trợ quyết định đầu tư  
- Lập kế hoạch phát triển hạ tầng, dịch vụ  
- Phân tích tính khả thi về tài chính và tốc độ tăng trưởng

(Used to:
- Predict future traffic  
- Support investor decisions  
- Plan operations and infrastructure  
- Evaluate business growth potential)

