# Yêu cầu chức năng (Functional Requirements)

Quy ước mã: `FR-<module>-<số>`.

## FR-1: Module Ôn tập lý thuyết theo chương (Theory Review)

- **FR-1.1** Trang danh sách 7 chương thi, hiển thị: tên chương, thời lượng chuẩn (phút),
  số lượng mục, % hoàn thành ôn tập của người dùng.
- **FR-1.2** Trang chi tiết chương hiển thị danh sách mục (section) theo đúng thứ tự syllabus
  (vd. Chapter 3 → 3.1.1 → 3.1.2 → ... → 3.4.3).
- **FR-1.3** Trang chi tiết mục hiển thị: nội dung tóm tắt, từ khóa (AI-specific keywords được
  đánh dấu riêng), mã LO + mức K áp dụng, điều hướng mục trước/sau trong cùng chương.
- **FR-1.4** Hỗ trợ đánh dấu "đã học" / "cần ôn lại" cho từng mục để phục vụ theo dõi tiến độ (FR-4).
- **FR-1.5** Hiển thị các bảng/công thức quan trọng dưới dạng có định dạng rõ ràng, ví dụ:
  - Công thức Accuracy, Precision, Recall, F1-score (3.3.1).
  - Bảng Confusion Matrix (Figure 2).
  - Bảng ví dụ risk & mitigation (5.1.1, 6.1.1, 7.1.1).
  - Bảng ví dụ Acceptance Criteria theo đặc tính chất lượng ISO/IEC 25059 (2.2.1).
- **FR-1.6** Tìm kiếm toàn văn trong nội dung lý thuyết theo từ khóa hoặc mã mục.
- **FR-1.7** Chức năng "Ôn nhanh trước ngày thi": hiển thị dạng flashcard gồm tất cả từ khóa +
  định nghĩa/ý chính, gom theo chương.

## FR-2: Module Từ điển thuật ngữ (Glossary)

- **FR-2.1** Danh sách thuật ngữ AI-specific (Chapter 9 của syllabus) sắp xếp A-Z, tìm kiếm theo tên.
- **FR-2.2** Danh sách viết tắt (Chapter 8) có chức năng tra cứu nhanh (vd. gõ "kMNC" ra định nghĩa).
- **FR-2.3** Mỗi thuật ngữ liên kết ngược tới (các) mục lý thuyết có sử dụng thuật ngữ đó.

## FR-3: Module Luyện thi (Quiz / Mock Exam)

- **FR-3.1** Chế độ **Luyện theo chương**: người dùng chọn 1 hoặc nhiều chương, hệ thống sinh
  bộ câu hỏi chỉ trong phạm vi LO của (các) chương đã chọn.
- **FR-3.2** Chế độ **Luyện theo mức K**: lọc câu hỏi theo K1/K2/K3/K4.
- **FR-3.3** Chế độ **Thi thử toàn bộ (Mock Exam)**: sinh đề bao phủ đủ 7 chương theo tỉ trọng
  số LO của từng chương (xem [04-ngan-hang-cau-hoi.md](04-ngan-hang-cau-hoi.md)), có tính giờ.
- **FR-3.4** Sau khi nộp bài (hoặc từng câu ở chế độ luyện tập), hiển thị: đáp án đúng, giải thích
  ngắn gọn, mục syllabus liên quan (liên kết trực tiếp tới FR-1.3).
- **FR-3.5** Hỗ trợ dạng câu hỏi: trắc nghiệm 1 đáp án đúng, trắc nghiệm nhiều đáp án đúng, và
  dạng tính toán (vd. tính Accuracy/Precision/Recall/F1 từ confusion matrix cho trước — ứng với
  LO AI-3.3.1 mức K3).
- **FR-3.6** Cho phép tạm dừng và tiếp tục bài thi thử đang làm dở.
- **FR-3.7** Kết thúc bài thi hiển thị: điểm số, tỷ lệ đạt/không đạt, breakdown theo chương và theo
  mức K, danh sách câu sai kèm link ôn tập lại.

## FR-4: Module Theo dõi tiến độ (Progress Tracking)

- **FR-4.1** Dashboard cá nhân hiển thị: % lý thuyết đã ôn theo từng chương, lịch sử các lần luyện
  thi/thi thử, điểm trung bình theo chương và theo Business Outcome (BO1–BO8).
- **FR-4.2** Gợi ý "chương cần ôn tập thêm" dựa trên tỷ lệ trả lời sai cao nhất.
- **FR-4.3** Lưu lịch sử để người dùng so sánh tiến bộ qua các lần thi thử.

## FR-5: Quản trị nội dung (Admin/Content Management)

- **FR-5.1** Cho phép quản trị viên thêm/sửa nội dung lý thuyết theo cấu trúc chương/mục đã định
  nghĩa ở [01-cau-truc-noi-dung-syllabus.md](01-cau-truc-noi-dung-syllabus.md).
- **FR-5.2** Cho phép quản trị viên thêm/sửa câu hỏi, gắn mã LO, mức K, chương, và (tuỳ chọn) mã BO.
- **FR-5.3** Hỗ trợ cập nhật nội dung khi syllabus có phiên bản mới (versioning theo số version
  syllabus, hiện tại v2.0 GA).

## FR-6: Tài khoản người dùng

- **FR-6.1** Đăng ký/đăng nhập để lưu tiến độ cá nhân.
- **FR-6.2** Cho phép dùng thử không cần đăng nhập (chế độ khách), nhưng không lưu lịch sử.
