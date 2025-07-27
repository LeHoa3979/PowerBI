# Power BI Project: Xu hướng giá thị trường chứng khoán Việt Nam: Mô hình tăng và giảm

## Tổng Quan
Dự án Power BI này tập trung vào việc phân tích xu hướng giá cổ phiếu trên thị trường chứng khoán Việt Nam. Thông qua việc trực quan hóa dữ liệu lịch sử, dashboard giúp người dùng theo dõi biến động giá, xác định các giai đoạn tăng/giảm mạnh, và áp dụng các chỉ báo kỹ thuật như đường trung bình động (Moving Average) để hỗ trợ ra quyết định đầu tư.

Dashboard cung cấp cái nhìn tổng thể và chi tiết về các mã cổ phiếu, theo thời gian, ngành và hiệu suất tương đối, giúp người dùng nhận diện mô hình biến động và xu hướng thị trường.

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
Bộ dữ liệu được sử dụng trong dự án là **dữ liệu lịch sử giá cổ phiếu của VanEck Vectors Vietnam ETF (VNM ETF)** – một quỹ ETF đại diện cho hiệu suất thị trường chứng khoán Việt Nam.

### 🧾 Các trường dữ liệu:

| Trường dữ liệu | Mô tả |
|----------------|-------|
| `Date`         | Ngày giao dịch |
| `Open`         | Giá mở cửa trong ngày |
| `High`         | Giá cao nhất trong ngày |
| `Low`          | Giá thấp nhất trong ngày |
| `Close`        | Giá đóng cửa trong ngày |
| `Adj Close`    | Giá đóng cửa đã điều chỉnh (đã tính cổ tức, chia tách...) |
| `Volume`       | Khối lượng giao dịch trong ngày |

### 📌 Ghi chú:

- Dữ liệu phản ánh hiệu suất giao dịch cổ phiếu theo từng ngày.
- Có thể dùng để tính toán các chỉ số phân tích kỹ thuật như **Moving Average (MA)**, **Relative Strength Index (RSI)**,...
- Dữ liệu phù hợp để trực quan hóa xu hướng giá trong Power BI.

> 📂 Nguồn dữ liệu: [Yahoo Finance](https://finance.yahoo.com/), [VanEck Vectors Vietnam ETF (VNM)](https://www.vaneck.com/us/en/investments/vnm/)


## Điểm Nổi Bật Của Dashboard
- **Biến Động Giá Cổ Phiếu Theo Ngày (%)**: Hiển thị mức độ dao động thị trường.
- **Xu Hướng Trung Bình Giá Cổ Phiếu 7 Ngày**: Nhận diện xu hướng ngắn hạn.
- **Chỉ Báo RSI (14)**: Hiển thị vùng quá mua hoặc quá bán.
- **Heatmap Lợi Nhuận Cổ Phiếu Theo Tháng**: Trực quan hiệu suất cổ phiếu theo tháng và năm.
- **Dự Báo Doanh Số 3 Năm Tới**: Mô hình dự đoán xu hướng doanh số trong tương lai.

  **DASHBOARD**
  ![Image](https://github.com/user-attachments/assets/a1b1299e-3e7d-44c9-8536-fa8bd61f21bd)


