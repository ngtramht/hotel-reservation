# hotel-reservation
## Giới thiệu
Dự án tập trung vào các yếu tố ảnh hưởng đến việc đặt và hủy phòng dựa trên tập dữ liệu, sử dụng các yếu tố đó để báo cáo xu hướng và dự đoán lượng đặt phòng trong tương lai.
Bộ dữ liệu được thu thập trong 2 năm 2017 và 2018.

## Phương pháp
### Data Cleaning:
-	Thu thập Dữ liệu: Tìm kiếm và thu thấp bộ dữ liệu từ Kaggle
-	Kiểm Tra Dữ Liệu Thiếu: Kiểm tra và xử lý các giá trị thiếu trong dữ liệu.
-	Loại Bỏ Dữ Liệu Trùng Lặp: Kiểm tra và loại bỏ các dòng dữ liệu trùng lặp.
-	Xử Lý Ngoại Lệ: Kiểm tra và xử lý các ngoại lệ trong dữ liệu.
### EDA (Exploratory Data Analysis):
-	Thống Kê Mô Tả: Tính toán và hiển thị thống kê mô tả cơ bản của dữ liệu.
-	Visualizations: Sử dụng biểu đồ và đồ thị để hiểu rõ hơn về phân phối và mối quan hệ trong dữ liệu.
-	Phân Tích Ý Nghĩa: Rút ra những kết luận và đề xuất dựa trên những quan sát từ EDA.
### Thư viện sử dụng
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Dataset
### Data source
link kaggle: [https://www.kaggle.com/datasets/ahsan81/hotel-reservations-classification-dataset/data](url)
### Thuộc tính
- Tên thuộc tính:	Mô tả thuộc tính
- Booking_ID:	Mã định danh duy nhất mỗi lần đặt phòng.
- no_of_adults:	Số lượng người lớn
- no_of_children:	Số lượng trẻ em
- no_of_weekend_nights:	Số đêm cuối tuần khách đặt hoặc ở lại
- no_of_week_nights:	Số đêm trong tuần mà khách đặt hoặc ở lại
- type_of_meal_plan:	Loại gói bữa ăn do khách đặt
- required_car_parking_space:	Khách có yêu cầu bãi đỗ xe không
- room_type_reserved:	Loại phòng khách hàng đặt
- lead_time:	Số ngày đăt phòng 
- arrival_year:	Năm đến
- arrival_month:	Tháng đến
- arrival_date:	Ngày đến
- market_segment_type:	Phân khúc thị trường
- repeated_guest:	Khách hàng có phải đã từng đến không
- no_of_previous_cancellations:	Số lần đặt chỗ trước đó khách hàng đã hủy
- no_of_previous_bookings_not_canceled:	Số lần đặt chỗ trước đó khách hàng không hủy
- avg_price_per_room:	Giá trung bình mỗi ngày đặt phòng
- no_of_special_requests:	Tổng số yêu cầu đặc biệt của khách hàng (ví dụ: tầng cao, góc nhìn từ phòng, v.v.)
- booking_status:	tình trạng đặt phòng
