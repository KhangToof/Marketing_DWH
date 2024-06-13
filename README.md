# Marketing_DWH
 **Market Analysis Data Warehouse**
## 1. Dataset
- Data: [Marketing Campaign](https://github.com/YuehHanChen/Marketing_Analytics/blob/main/marketing_data.csv)
- Dữ liệu về các chiến dịch marketing được public vào tháng 12 năm 2020 và thu nhập trong 2 năm (từ năm 2012-2014).
- Thông qua dữ liệu, người dùng có thể biết được thông tin của khách hàng, số tiền đã chi trả cho từng loại hàng hóa, số hóa đơn đã đặt theo các hình thức khác nhau, phản hồi của khách hàng,…
- Dữ liệu bao gồm 28 cột, 2240 dòng.
--------------------------------------
## 2. Dimension and Fact tables
### a. DimDate table
- Chứa thông tin về các mốc thời gian được ghi nhận.
- Bao gồm những thuộc tính như là năm, quý, ngày và tháng.
- Khoá chính của bảng sẽ là DateKey.
### b. DimCustomer table
- Chứa thông tin về khách hàng được ghi nhận.
- Bao gồm những thuộc tính như là thu nhập, tình trạng hôn nhân, số tiền đã chi trả cho từng loại hàng hóa,...
- Khoá chính của bảng sẽ là CustomerKey
### c. Fact_MarketingAnalytic table
- Chứa thông tin về các ảnh hưởng của khách hàng đến chiến dịch Marketing.
- Bao gồm những thuộc tính như là sự phàn nàn, tổng chiến dịch được chấp thuận, tổng chi,...
- Bảng này sẽ tham chiếu đến 2 bảng Dimension trước để thiết lập các mối quan hệ.
Ở đây sẽ có tham chiếu khoá ngoại để đảm bảo tính toàn vẹn của dữ liệu.
--------------------------------------
## 3. Schema
![Schema](https://github.com/KhangToof/Marketing_DWH/assets/93634247/a8dfc778-441e-4c36-9b2e-5226c67bc0ea)
--------------------------------------
## 4. ETL Process
![ETL](https://github.com/KhangToof/Marketing_DWH/assets/93634247/55b2b546-eba9-4ee0-9acf-caf606ab2960)
--------------------------------------
**Nếu bạn có thắc mắc gì về bài làm, hãy liên hệ tôi qua email sau:** 
💬︎ ntk29072003@gmail.com
