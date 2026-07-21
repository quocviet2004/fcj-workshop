---
title: "Worklog Tuần 5"
date: 2026-06-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 5:

* Bắt đầu dự án thực tế (wed du lịch Traveloka)[cite: 2].
* Tích hợp AWS Lambda với DynamoDB bằng AWS SDK v3 (@aws-sdk/client-dynamodb)[cite: 2].

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |  Nguồn tài liệu          |
| --- | --- | --- | --- |
| 2 - 3 | - Khởi tạo project cho Backend, cài đặt thư viện `AWS SDK v3`. | 01/06/2026 | 02/06/2026 | <https://aws.amazon.com/sdk-for-java/> |
| 4 - 5 | - Kết nối hàm Lambda với bảng `Hotels` trên DynamoDB đã tạo ở Tuần 3. | 03/06/2026 | 04/06/2026 |  <https://cloudjourney.awsstudygroup.com/> |
| 6 - 7 | - Viết hàm `getHotelsList` dùng `ScanCommand` lấy danh sách khách sạn[cite: 2]. | 05/06/2026 | 06/06/2026 |  <https://cloudjourney.awsstudygroup.com/>  |

### Kết quả đạt được tuần 5:

* Hoàn thành script Node.js cho Lambda, sử dụng thành công `ScanCommand` để truy vấn dữ liệu từ DynamoDB.

### Hình ảnh minh chứng tuần 5:

![Đoạn code ScanCommand dùng AWS SDK v3](/images/1-Worklog/1.5-Week5/lambda-dynamodb-code.png)
