---
title: "Worklog Tuần 10"
date: 2026-07-06
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}


### Mục tiêu tuần 10:

* Đóng gói mã nguồn (Build) và triển khai (Deploy) website lên dịch vụ AWS S3[cite: 2].
* Viết báo cáo tổng kết quá trình thực tập[cite: 2].

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành |  Nguồn tài liệu          |
| --- | --- | --- | --- |
| 2 - 3 | - Kiểm tra lại toàn bộ source code Frontend.<br>- Tiến hành đóng gói mã nguồn (Build) bằng lệnh `npm run build` để tối ưu hóa dung lượng ứng dụng[cite: 2]. | 06/07/2026 | 07/07/2026 | <https://aws.amazon.com/blogs/compute/uploading-to-amazon-s3-directly-from-a-web-or-mobile-application/> |
| 4 - 5 | - Cấu hình Bucket trên Amazon S3 (mở Public Access, thiết lập Bucket Policy).<br>- Triển khai (Deploy) website lên dịch vụ AWS S3 để chạy dạng Static Website Hosting[cite: 2]. | 08/07/2026 | 09/07/2026 |<https://cloudjourney.awsstudygroup.com/>  |
| 6 - 7 | - Tổng hợp lại nhật ký công việc từ tuần 1 đến tuần 10.<br>- Bắt tay vào viết báo cáo tổng kết quá trình thực tập dựa trên template của trường[cite: 2]. | 10/07/2026 | 11/07/2026 | <http://localhost:1313/1-worklog/> |

### Kết quả đạt được tuần 10:

* Website MINI Traveloka booking đã chính thức lên (Production), có thể truy cập công khai thông qua đường link cấp bởi AWS S3.
* Hoàn thành bộ khung sườn và kiểm tra của bản Báo cáo thực tập tốt nghiệp.

### Hình ảnh minh chứng tuần 10:

![Build thành công và upload các file tĩnh lên S3](/images/1-Worklog/1.10-Week10/s3-upload-build.png)

![Trang web Traveloka hoạt động trên link AWS S3](/images/1-Worklog/1.10-Week10/website-live-s3.png)


