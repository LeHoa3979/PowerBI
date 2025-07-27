# Power BI Project: Xu hướng giá thị trường chứng khoán Việt Nam: Mô hình tăng và giảm

## Tổng Quan
Dự án Power BI này tập trung vào việc phân tích dữ liệu bán hàng từ bộ dữ liệu Superstore nhằm khám phá thông tin chi tiết, xác định xu hướng và dự báo doanh số trong tương lai.  
Dashboard cung cấp các biểu đồ tương tác về các chỉ số kinh doanh chính như doanh thu, lợi nhuận, xu hướng bán hàng và phân khúc khách hàng.

## Mục Tiêu
- Phân tích xu hướng doanh số và lợi nhuận trong quá khứ.
- Xác định các sản phẩm, khu vực và phân khúc khách hàng hoạt động hiệu quả nhất.
- Trực quan hóa xu hướng giá cổ phiếu với đường trung bình động và các chỉ báo kỹ thuật.
- Dự báo doanh số trong tương lai bằng các kỹ thuật phân tích dự đoán.

## Tính Năng Chính
- **Phân Tích Hiệu Suất Bán Hàng**: Phân tích xu hướng doanh thu, lợi nhuận và ảnh hưởng của chiết khấu.
- **Phân Khúc Khách Hàng**: Xác định khách hàng giá trị cao và mô hình mua hàng.
- **Hiệu Suất Sản Phẩm**: Đánh giá sản phẩm bán chạy nhất và kém lợi nhuận nhất.
- **Xu Hướng Bán Hàng Theo Khu Vực**: Phân tích sự khác biệt doanh số giữa các khu vực.
- **Thông Tin Thị Trường Chứng Khoán**: Tích hợp xu hướng giá cổ phiếu, độ biến động và chỉ báo RSI.
- **Mô-đun Dự Báo**: Dự đoán doanh số trong 3 năm tiếp theo.

## Công Cụ & Công Nghệ
- **Power BI Desktop**: Trực quan hóa dữ liệu và tạo dashboard.
- **SQL Server**: Trích xuất và chuyển đổi dữ liệu.
- **Excel**: Làm sạch và tiền xử lý dữ liệu.
- **Python (Jupyter Notebook)**: Phân tích nâng cao và dự báo.

## Bộ Dữ Liệu
Bộ dữ liệu được sử dụng là **Superstore Sales Dataset**, bao gồm các trường sau:
- **Thông Tin Đơn Hàng**: Order ID, Order Date, Ship Date, Customer ID, Product ID.
- **Chỉ Số Bán Hàng**: Sales, Profit, Discount, Quantity.
- **Dữ Liệu Khách Hàng & Khu Vực**: Customer Name, Segment, City, State, Region.
- **Thông Tin Sản Phẩm**: Category, Sub-Category, Product Name.

## Điểm Nổi Bật Của Dashboard
- **Biến Động Giá Cổ Phiếu Theo Ngày (%)**: Hiển thị mức độ dao động thị trường.
- **Xu Hướng Trung Bình Giá Cổ Phiếu 7 Ngày**: Nhận diện xu hướng ngắn hạn.
- **Chỉ Báo RSI (14)**: Hiển thị vùng quá mua hoặc quá bán.
- **Heatmap Lợi Nhuận Cổ Phiếu Theo Tháng**: Trực quan hiệu suất cổ phiếu theo tháng và năm.
- **Dự Báo Doanh Số 3 Năm Tới**: Mô hình dự đoán xu hướng doanh số trong tương lai.

  **DASHBOARD**
  ![Image](https://github.com/user-attachments/assets/a1b1299e-3e7d-44c9-8536-fa8bd61f21bd)


