---
title: "Worklog Tuần 3"
date: 2026-05-18
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 3:

* Thiết kế cơ sở dữ liệu NoSQL trên Amazon DynamoDB.
* Định hình cấu trúc dữ liệu JSON cho các bảng cốt lõi (Hotels, Users) và nạp dữ liệu mẫu.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
|| 2 - 3 | - Tạo bảng `Hotels` và `Users` trên giao diện DynamoDB.<br>- Xác định Khóa chính (Partition Key) và Khóa sắp xếp (Sort Key) để tối ưu luồng truy vấn cho chức năng tìm phòng. | 18/05/2026 | 19/05/2026 |<https://cloudjourney.awsstudygroup.com/>|
| 4 - 5 | - Cấu hình dung lượng đọc/ghi (RCU/WCU) ở mức Free Tier để tối ưu chi phí.<br>- Soạn thảo cấu trúc file JSON mẫu chứa thông tin phòng (Tên, Giá, URL Hình ảnh, Tiện ích). | 20/05/2026 | 21/05/2026 |<https://cloudjourney.awsstudygroup.com/>|
| 6 - 7 | - Sử dụng tính năng "Explore table items" để chèn (Insert) các dữ liệu phòng khách sạn mẫu vào database.<br>- Kiểm tra lại các query để đảm bảo dữ liệu hiển thị đúng. | 22/05/2026 | 23/05/2026 |<https://cloudjourney.awsstudygroup.com/>|

### Kết quả đạt được tuần 3:

* Hoàn thiện 100% cấu trúc cơ sở dữ liệu NoSQL cho ứng dụng Traveloka trên DynamoDB.
* Các bảng dữ liệu đã được nạp sẵn thông tin phòng khách sạn, sẵn sàng cho việc kết nối và gọi API ở tuần sau.
* Nắm vững cách thiết kế Partition Key và truy cập dữ liệu hiệu quả mà không cần dùng câu lệnh SQL truyền thống.

### Hình ảnh minh chứng tuần 3:
![Bảng dữ liệu Hotels trên DynamoDB](/images/1-Worklog/1.3-Week3/dynamodb-hotels.png)

