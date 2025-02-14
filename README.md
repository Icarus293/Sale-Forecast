# Big Mart Sales Forecasting

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)

Dự đoán doanh số bán hàng của các sản phẩm tại các cửa hàng Big Mart bằng [Linear Regression](https://machinelearningcoban.com/2016/12/28/linearregression/) và [Random Forest](https://machinelearningcoban.com/tabml_book/ch_model/random_forest.html).

## **1. Bối cảnh và Nội dung**
Trong ngành bán lẻ cạnh tranh, việc dự đoán doanh số giúp:
- Tối ưu hóa quản lý kho
- Hiểu rõ các yếu tố ảnh hưởng đến doanh thu
- Đưa ra chiến lược kinh doanh

## **2. Đặc trưng dữ liệu**

- **Item_Identifier**: Mã sản phẩm duy nhất.
- **Item_Weight**: Trọng lượng của sản phẩm.
- **Item_Fat_Content**: Hàm lượng chất béo của sản phẩm.
- **Item_Visibility**: Tỷ lệ phần trăm tổng diện tích hiển thị của tất cả các sản phẩm trong một cửa hàng được phân bổ cho sản phẩm cụ thể.
- **Item_Type**: Danh mục sản phẩm.
- **Item_MRP**: Giá bán lẻ tối đa (giá niêm yết) của sản phẩm.
- **Outlet_Identifier**: Mã cửa hàng duy nhất.
- **Outlet_Establishment_Year**: Năm thành lập cửa hàng.
- **Outlet_Size**: Kích thước của cửa hàng theo diện tích mặt bằng.
- **Outlet_Location_Type**: Loại thành phố nơi cửa hàng tọa lạc.
- **Outlet_Type**: Loại hình cửa hàng (tạp hóa hoặc siêu thị).
- **Item_Outlet_Sales**: Doanh số bán sản phẩm tại cửa hàng cụ thể (biến mục tiêu cần dự đoán).

## **3. Ý tưởng thực hiện**

Đồ án được lấy ý tưởng từ cuộc thi [*Store Sales - Time Series Forecasting*](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data).

**Hạn chế:** 

- Mô hình chưa sử dụng được những mô hình có độ phức tạp cao nên độ chính xác vẫn còn hạn chế
- Chưa có kinh nghiệm xử lí dữ liệu cũng có thể là 1 trong những lí do dẫn đến mô hình có độ sai số tương đối

## **4. Nguồn dữ liệu và tham khảo**

Tham khảo chi tiết tại: [Big Mart Sale Forecast on Kaggle](https://www.kaggle.com/code/chanchal24/big-mart-sale-forecast/notebook)
