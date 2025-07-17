# Retail_Sales_Forecasting_for_BigMart
(Dự đoán doanh số bán hàng cho BigMart bằng hồi quy)

## 🧾 Project Description | Mô tả dự án

We use 2013 sales data from BigMart to **predict sales (Item_Outlet_Sales)** of products in stores.  
(Chúng ta dùng dữ liệu năm 2013 của BigMart để **dự đoán doanh số** sản phẩm trong từng cửa hàng.)

This project helps BigMart understand:
- Which products sell more?
- Which store features affect sales?
→ From that, they can improve sales strategy.

(Dự án giúp BigMart hiểu:
- Sản phẩm nào bán chạy?
- Đặc điểm nào của cửa hàng ảnh hưởng đến doanh số?
→ Từ đó cải thiện chiến lược bán hàng.)

📥 **Data source:** [Kaggle - BigMart Dataset](https://www.kaggle.com/devashish0507/big-mart-sales-prediction)

---

## 📊 Dataset Information | Thông tin dữ liệu

**1559 products** from **10 stores**  
(Dữ liệu gồm 1559 sản phẩm từ 10 cửa hàng khác nhau.)

| Column name | Meaning | Ý nghĩa |
|-------------|---------|--------|
| `Item_Identifier` | Product ID | Mã sản phẩm |
| `Item_Weight` | Weight | Trọng lượng |
| `Item_Fat_Content` | Fat type | Loại chất béo (ít béo hay không) |
| `Item_Visibility` | Display % | Tỷ lệ hiển thị sản phẩm |
| `Item_Type` | Category | Loại sản phẩm |
| `Item_MRP` | Max Price | Giá bán lẻ tối đa |
| `Outlet_Identifier` | Store ID | Mã cửa hàng |
| `Outlet_Establishment_Year` | Store year | Năm mở cửa |
| `Outlet_Size` | Store size | Quy mô cửa hàng |
| `Outlet_Location_Type` | Store location | Loại khu vực cửa hàng |
| `Outlet_Type` | Store type | Loại cửa hàng |
| `Item_Outlet_Sales` | 🔥 Sales to predict | Doanh số cần dự đoán |

---

## 🛠️ Libraries used | Thư viện sử dụng

- `pandas` → Xử lý dữ liệu  
- `matplotlib`, `seaborn` → Vẽ biểu đồ  
- `scikit-learn` → Huấn luyện và đánh giá mô hình Machine Learning

---

## 🧠 Algorithms used | Thuật toán sử dụng

- Linear Regression  
- Ridge  
- Lasso  
- Decision Tree  
- Random Forest  
- Extra Trees

---

## 📉 Model Evaluation | Đánh giá mô hình

- Metric: **Mean Squared Error (MSE)**  
- Score: **0.28 (log scale)**  
→ Use `np.exp()` to get real value  
(*Dùng np.exp() để chuyển về giá trị thật*)

---

## 🎯 Real-world Impact | Ứng dụng thực tế

✅ BigMart (or any retail store) can:  
- Forecast sales of new/existing products  
- Improve inventory and pricing decisions  
- Analyze store performance by location or type

(BigMart hoặc các cửa hàng bán lẻ có thể:
- Dự đoán doanh số sản phẩm mới/cũ
- Cải thiện tồn kho & giá bán
- Phân tích hiệu suất theo khu vực/cửa hàng)

---

