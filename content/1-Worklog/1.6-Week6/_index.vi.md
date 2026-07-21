---
title: "Worklog Tuần 6"
date: 2026-06-08
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 6:

* Thiết lập API Gateway, cấu hình Route GET /hotels kết nối trực tiếp vào Lambda[cite: 2].
* Cấu hình CORS và test API[cite: 2].

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu          |
| --- | --- | --- | --- |
| 2 - 3 | - Khởi tạo API trên Amazon API Gateway.<br>- Tạo Route `GET /hotels` và trỏ (tích hợp) trực tiếp vào hàm `getHotelsList` trên Lambda[cite: 2]. | 08/06/2026 | 09/06/2026 | <https://cloudjourney.awsstudygroup.com/>  |
| 4 - 5 | - Cấu hình CORS (Cross-Origin Resource Sharing) để Frontend có thể gọi API mà không bị chặn[cite: 2]. | 10/06/2026 | 11/06/2026 | <https://viblo.asia/p/cach-khac-phuc-loi-cors-policy-khi-goi-api-tu-frontend-gDVK23aeZLj> |
| 6 - 7 | - Dùng Postman test API, đảm bảo trả về đúng định dạng JSON[cite: 2]. | 12/06/2026 | 13/06/2026 | <https://viblo.asia/p/huong-dan-su-dung-postman-cho-test-api-aWj53Lb1K6m>  |

### Kết quả đạt được tuần 6:

* API Gateway đã cấu hình thành công, tích hợp trơn tru với Lambda.
* Giải quyết triệt để vấn đề CORS, API đã trả về chuỗi JSON danh sách khách sạn chính xác khi test bằng Postman.

### Hình ảnh minh chứng tuần 6:



