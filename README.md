# [Vận dụng chuyên sâu - 3] THIẾT KẾ CẶP SPRINT REVIEW VÀ SPRINT RETROSPECTIVE - RIKKEIASSIST

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1 - Kiểm tra Increment

Dưới đây là bảng kiểm tra trạng thái thực tế của 5 PBI trong Sprint 12 dựa trên điều kiện Definition of Done (DoD). DoD yêu cầu PBI phải đạt Acceptance Criteria, đã tích hợp trên môi trường thử nghiệm, không còn lỗi mức nghiêm trọng cao, và các hạng mục dữ liệu cá nhân phải qua kiểm tra quyền riêng tư.

- Lưu ý: Mọi PBI chưa thỏa mãn toàn bộ tiêu chí trên đều phải được phân loại là Chưa Done và không được đem ra demo tính năng chính thức trong Sprint Review.

| PBI | Trạng thái thực tế | Điều kiện Done làm căn cứ đánh giá |
| --- | --- | --- |
| PBI-51: Hướng dẫn đổi hàng lỗi kỹ thuật | Đã Done | Đạt 32/32 ca Acceptance Criteria; đã tích hợp thành công trên môi trường thử nghiệm. |
| PBI-52: Hướng dẫn trả hàng theo nhóm sản phẩm | Chưa Done | Bị chặn do chính sách đồ điện tử còn 2 phiên bản chưa chốt; 114 hội thoại chưa kết luận. Chưa đạt DoD. |
| PBI-53: Chuyển khiếu nại nghiêm trọng | Chưa Done | Đang chờ kiểm thử, có 3/50 ca phân loại sai và lỗi mức cao còn mở. Chưa đạt tiêu chuẩn không lỗi nghiêm trọng. |
| PBI-54: Hiển thị lịch sử cho nhân viên tiếp nhận | Đã Done | Đạt trên môi trường thử nghiệm; đã qua kiểm tra quyền riêng tư gắt gao. |
| PBI-58: Xóa dữ liệu cá nhân khỏi nội dung báo cáo | Chưa Done | Vẫn còn tồn tại 2 mẫu chứa số điện thoại trên tổng số 12 mẫu, chưa đạt kiểm tra quyền riêng tư hoàn toàn. |

## Phần 2 - Chuẩn bị và lịch trình Sprint Review

Quy trình chuẩn bị buổi Sprint Review 75 phút được thực hiện tuần tự qua các bước cụ thể để giải quyết triệt để các bẫy dữ liệu và ràng buộc thời gian của các Stakeholder:

- Bước 1: Rà soát danh sách PBI và xác thực trạng thái Done (chỉ đưa PBI-51 và PBI-54 lên bàn demo).
- Bước 2: Thống nhất với Product Owner về việc sử dụng video quay sẵn (đã chuẩn bị từ Ngày 10) để minh họa cho phần hướng dẫn trả hàng đồ điện tử (PBI-52) nhằm tránh tranh cãi chính sách pháp lý giữa các Stakeholder.
- Bước 3: Gửi thư mời họp có giới hạn thời gian rõ ràng: Đại diện chính sách chỉ tham gia 30 phút đầu; Đại diện bảo vệ dữ liệu tham gia từ xa để kiểm tra nhanh 2 mẫu lỗi của PBI-58.
- Bước 4: Dựng một User Journey thực tế từ các PBI Done (Ví dụ: Khách hàng hỏi đổi hàng lỗi -> Hệ thống tra cứu lịch sử qua PBI-54 -> Đưa ra hướng dẫn chuẩn qua PBI-51).
- Bước 5: Thiết lập không gian phòng họp và môi trường demo trực tuyến mượt mà, sẵn sàng ghi nhận feedback nhưng không hứa hẹn chỉnh sửa ngay tại chỗ theo đúng quy tắc nghiệp vụ.

| Thời gian | Hoạt động | Ai đóng góp |
| --- | --- | --- |
| 15 phút đầu | Product Owner mở đầu, tóm tắt các PBI đã hoàn thành (PBI-51 và PBI-54) và chiếu User Journey thực tế từ hai tính năng này. | Product Owner trình bày; Scrum Master điều phối thời gian; Developers hỗ trợ kỹ thuật nền. |
| 10 phút tiếp theo | Trình bày video quay sẵn cho các phần tính năng chưa ổn định hoặc chưa Done (PBI-52, PBI-53, PBI-58) theo đề xuất của PO. | Product Owner dẫn dắt thảo luận; Stakeholders quan sát và đặt câu hỏi. |
| 25 phút giữa | Lắng nghe feedback từ các Stakeholder. Giải quyết trực tiếp ý kiến của Đại diện chính sách (về việc AI trả lời khi chính sách chưa rõ) và Đại diện bảo vệ dữ liệu (xem xét 2 mẫu lỗi chứa số điện thoại của PBI-58). Đại diện chính sách rời họp sau phút thứ 30. | Chủ cửa hàng thí điểm, Đại diện chính sách, Đại diện bảo vệ dữ liệu đưa ra feedback; Product Owner tiếp nhận và làm rõ giới hạn rủi ro. |
| 15 phút cuối | Product Owner tổng hợp lại các phản hồi, phân loại feedback thành các nhóm cần nghiên cứu thêm, khẳng định không hứa hẹn đưa vào Sprint sau ngay lập tức và khép lại buổi Review. | Product Owner chủ trì kết luận; Scrum Master chốt giờ giấc. |
| 10 phút dự phòng | Thời gian đệm cho các vấn đề kết nối từ xa của Đại diện bảo vệ dữ liệu và các câu hỏi phát sinh nhanh. | Toàn bộ thành viên tham gia. |

## Phần 3 - Kế hoạch Sprint Retrospective

Sau khi phân tích Insight, Scrum Team thảo luận và thống nhất chọn ra đúng 1 Improvement duy nhất, thiết thực và khả thi nhất để triển khai cho Sprint sau theo bảng sau:

- Dữ liệu 1 (Data): Ngày 4, Khánh Vy (Developer phụ trách kiểm thử) mới có quyền truy cập đầy đủ môi trường thử nghiệm; kết hợp với việc IM-11-02 lặp lại chưa đạt.
- Dữ liệu 2 (Data): Ngày 5, Developers và nhân viên CSKH phát hiện đang hiểu khác nhau về khái niệm 'khiếu nại nghiêm trọng', dẫn đến PBI-53 bị phân loại sai 3/50 ca.

| Hành động cải tiến (Improvement) | Người/nhóm theo dõi | Khi kiểm tra | Bằng chứng xác thực |
| --- | --- | --- | --- |
| IM-12-01: Scrum Master đứng ra yêu cầu IT Infrastructure cấp sẵn quyền môi trường thử nghiệm trước 9h sáng Ngày 1 của Sprint mới; đồng thời tổ chức 1 buổi Workshop 30 phút giữa Developers và đại diện CSKH ngay ngày đầu để chốt chính xác định nghĩa 'khiếu nại nghiêm trọng' bằng văn bản. | Scrum Master và Developers phụ trách kiểm thử | Ngày đầu tiên của Sprint tiếp theo (Sprint 13) và kiểm tra lại tại Sprint Retrospective 13 | Biên bản xác nhận cấp quyền thành công trước Ngày 1 và tài liệu Glossary 'khiếu nại nghiêm trọng' có chữ ký chung. |

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt3.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
