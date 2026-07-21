---
title: "Worklog Tuần 7"
date: 2026-06-15
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 7:

* Tìm hiểu hệ thống giám sát và cảnh báo trên AWS[cite: 2].
* Thiết lập hệ thống thông báo sự cố tự động qua Email sử dụng Amazon SNS và CloudWatch[cite: 2].

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |  Nguồn tài liệu          |
| --- | --- | --- | --- |
| 2 - 3 | - Tìm hiểu hệ thống giám sát và cảnh báo trên AWS[cite: 2].<br>- Đọc tài liệu về cách thức hoạt động của Amazon CloudWatch và Amazon SNS. | 15/06/2026 | 16/06/2026 |  <https://cloudjourney.awsstudygroup.com/>  |
| 4 - 5 | - Thiết lập Amazon SNS Topic để nhận thông báo qua Email[cite: 2].<br>- Thực hành xác thực (Confirm Subscription) địa chỉ email nhận cảnh báo. | 17/06/2026 | 18/06/2026 |  <https://cloudjourney.awsstudygroup.com/> |
| 6 - 7 | - Cấu hình Amazon CloudWatch Alarm, bắt lỗi metric 5xx từ API Gateway để trigger cảnh báo[cite: 2].<br>- Chủ động tạo lỗi giả để test thử xem email cảnh báo có được gửi về không. | 19/06/2026 | 20/06/2026 |  <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được tuần 7:

* Nắm vững cơ chế theo dõi log và giám sát hệ thống của Amazon CloudWatch.
* Thiết lập thành công luồng thông báo tự động: Khi API Gateway gặp lỗi 5xx, hệ thống lập tức báo động qua CloudWatch và gửi email chi tiết thông qua SNS Topic.

### Hình ảnh minh chứng tuần 7:

![Cấu hình Amazon SNS Topic và xác nhận đặt phòng Email](/images/1-Worklog/1.7-Week7/sns-email-subscription.png)




