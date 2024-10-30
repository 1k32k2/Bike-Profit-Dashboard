# Bike-Profit-Dashboard
Bảng thông tin thể hiện lợi nhuận của cửa hàng cho thuê xe đạp.

Trong dự án này, mình đã xây dựng nên một màn hình cho phép chủ cửa hàng có thể nhìn thấy được lợi nhuận qua giờ, tháng và quý; từ đó có nên ra quyết định tăng giá sản phẩm hay không.

Ngôn ngữ và công nghệ đã sử dụng: **Python**, **SQL** và **Power BI**

#### Bước 1: Tiền xử lý dữ liệu
Dữ liệu ban đầu ở dạng file CSV, do cột ngày chưa ở đúng dạng nên mình đã dùng **Pandas** để biến chúng về dạng month/day/year. 

![](https://raw.githubusercontent.com/1k32k2/Bike-Profit-Dashboard/refs/heads/main/img/data_preprocessing.PNG)

#### Bước 2: Xây dựng cơ sở dữ liệu
Sau khi biến đổi về dạng chuẩn, mình tiến hành nhập dữ liệu vào **SQL Server** thông qua các file CSV vừa chuẩn hóa.

![](https://raw.githubusercontent.com/1k32k2/Bike-Profit-Dashboard/refs/heads/main/img/database.PNG)

#### Bước 3: Xây dựng bảng điều khiển
Cuối cùng, mình kết nối dữ liệu từ SQL Server vào Power BI và tiến hành dựng nên bảng điều khiển sau

![](https://raw.githubusercontent.com/1k32k2/Bike-Profit-Dashboard/refs/heads/main/img/Dashboard.png)
