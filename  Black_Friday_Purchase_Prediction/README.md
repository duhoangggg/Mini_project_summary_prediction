# 🛍️ Black_Friday_Purchase_Prediction_using_Regression  
(Dự đoán chi tiêu Black Friday bằng mô hình hồi quy)

## 🧾 Project Description | Mô tả dự án

We use real retail data to **predict customer purchase amount** during Black Friday sales.  
(Chúng ta sử dụng dữ liệu bán lẻ thực tế để **dự đoán số tiền chi tiêu của khách hàng** trong dịp Black Friday.)

This is a **regression problem** with over **550,000 rows**.  
(Đây là bài toán hồi quy với hơn **550.000 dòng dữ liệu**.)

Goal: Understand **who spends more and on what**, so businesses can create better offers and marketing.  
(Mục tiêu: Hiểu **ai là người chi tiêu nhiều và họ mua gì**, từ đó giúp doanh nghiệp đưa ra chiến lược ưu đãi và tiếp thị tốt hơn.)

📥 **Dataset link:** [Black Friday Sales – Kaggle](https://www.kaggle.com/kkartik93/black-friday-sales-prediction)

---

## 📊 Dataset Information | Thông tin dữ liệu

| Column | Meaning | Giải thích |
|--------|---------|------------|
| `User_ID` | Customer ID | Mã khách hàng |
| `Product_ID` | Product ID | Mã sản phẩm |
| `Gender` | Male/Female | Giới tính |
| `Age` | Age group | Nhóm tuổi |
| `Occupation` | Job code | Nghề nghiệp |
| `City_Category` | City type | Loại thành phố |
| `Stay_In_Current_City_Years` | Years in city | Sống bao lâu tại thành phố |
| `Marital_Status` | Married or not | Tình trạng hôn nhân |
| `Product_Category_1/2/3` | Product type | Loại sản phẩm |
| `Purchase` | 🔥 Purchase amount | **Số tiền chi tiêu (biến cần dự đoán)**

---

## 🛠️ Libraries used | Thư viện sử dụng

- `pandas` → xử lý dữ liệu  
- `matplotlib`, `seaborn` → trực quan hóa dữ liệu  
- `scikit-learn` → xây dựng mô hình học máy

---

## 🧠 Algorithms used | Thuật toán sử dụng

- Linear Regression  
- Decision Tree  
- Random Forest  
- Extra Trees

---

## 🚀 Future Work | Hướng phát triển

- 🔧 Hyperparameter Tuning (tối ưu tham số)  
- 🤖 Try more models (thử thêm mô hình khác)  
- 🧱 Feature Engineering (tạo đặc trưng mới)  
- ⚖️ Normalization (chuẩn hóa dữ liệu)

---

## 🎯 Real-world Use Case | Ứng dụng thực tế

✅ Dữ liệu này giúp:
- Dự đoán người dùng nào có khả năng chi tiêu cao  
- Phân nhóm khách hàng tiềm năng  
- Cá nhân hóa ưu đãi trong các đợt sale lớn  
- Cải thiện chiến dịch tiếp thị và phân phối sản phẩm

(Businesses can:
- Predict high-spending users  
- Segment customers  
- Personalize promotions  
- Improve marketing strategy)

