---
title: "Worklog Tuần 8"
date: 2026-06-22
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 8:

* Khởi tạo dự án Frontend bằng ReactJS và Vite[cite: 2].
* Viết logic fetch gọi API Gateway AWS, xử lý state (useState, useEffect) hiển thị dữ liệu ra UI[cite: 2].

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu          |
| --- | --- | --- | --- |
| 2 - 3 | - Khởi tạo dự án Frontend bằng ReactJS và Vite[cite: 2].<br>- Thiết lập cấu trúc thư mục Component-based (Header, Hero, HotelList)[cite: 2]. | 22/06/2026 | 23/06/2026 |<https://viblo.asia/p/cau-truc-thu-muc-va-cach-viet-component-chuan-trong-react-RQqKLxypK7z>   |
| 4 - 5 | - Cài đặt thư viện hỗ trợ gọi API.<br>- Viết logic fetch gọi API Gateway AWS để lấy dữ liệu danh sách khách sạn[cite: 2]. | 24/06/2026 | 25/06/2026 | <https://viblo.asia/p/tim-hieu-aws-api-gateway-RnB5pMW2KPG>  |
| 6 - 7 | - Xử lý state (useState, useEffect) hiển thị dữ liệu ra UI[cite: 2].<br>- Đảm bảo các component như `HotelList` render đúng danh sách phòng trả về từ Backend. | 26/06/2026 | 27/06/2026 | <https://cloudjourney.awsstudygroup.com/>  |

### Kết quả đạt được tuần 8:

* Khởi tạo thành công cấu trúc project ReactJS gọn gàng, chuẩn Component-based.
* Kết nối Frontend với API Gateway thành công, dữ liệu từ DynamoDB đã được fetch và hiển thị đầy đủ lên giao diện web.
* Sử dụng thành thạo các React Hooks (useState, useEffect) để quản lý trạng thái dữ liệu.

### Hình ảnh minh chứng tuần 8:

![Cấu trúc thư mục project ReactJS và Vite](/images/1-Worklog/1.8-Week8/react-folder-structure.png)

![Giao diện hiển thị danh sách khách sạn từ API](/images/1-Worklog/1.8-Week8/react-ui-fetch-api.png)


