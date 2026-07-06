# Yêu cầu ngân hàng câu hỏi luyện thi

## 1. Nguyên tắc chung

- Mỗi câu hỏi **bắt buộc** phải gắn với đúng một mã LO (vd. `AI-3.3.1`) và mức K của LO đó
  (K1/K2/K3/K4), lấy theo bảng ở [01-cau-truc-noi-dung-syllabus.md](01-cau-truc-noi-dung-syllabus.md).
- Câu hỏi có thể gắn thêm mã Business Outcome (BO1–BO8) để phục vụ thống kê tiến độ (FR-4.1).
- Với từ khóa (keywords) liệt kê đầu mỗi chương trong syllabus: tên và định nghĩa phải được nhớ
  ở mức K1 dù không có LO K1 tường minh (theo mục 0.5 của syllabus) → cần có nhóm câu hỏi
  "nhận biết định nghĩa" riêng cho các từ khóa này.
- Câu hỏi có thể yêu cầu kết hợp kiến thức nhiều mục/chương (theo mục 0.6 của syllabus), nên hệ
  thống câu hỏi nên hỗ trợ gắn **nhiều mã LO** cho một câu hỏi khi cần.

## 2. Loại câu hỏi theo mức K (bám sát Learning Objectives của syllabus)

| Mức K | Dạng câu hỏi phù hợp | Ví dụ LO |
|---|---|---|
| K1 (Remember) | Nhận diện định nghĩa đúng của thuật ngữ/từ khóa | Định nghĩa "narrow AI", "F1-score", "concept drift"... |
| K2 (Understand) | Giải thích/so sánh/phân biệt khái niệm, chọn ví dụ đúng | AI-1.1.2, AI-4.1.1, AI-6.1.7... (phần lớn LO của syllabus) |
| K3 (Apply) | Bài tập tính toán / áp dụng kỹ thuật vào tình huống cho trước | AI-3.3.1 (tính Accuracy/Precision/Recall/F1 từ confusion matrix cho trước), AI-4.2.2 (áp dụng red teaming), AI-5.1.5 (áp dụng dataset constraint testing), AI-6.1.5 (suy ra test case bằng metamorphic testing) |
| K4 (Analyze) | Phân tích tình huống phức tạp, không có LO K4 nào trong syllabus v2.0 hiện tại | — |

Lưu ý: cú pháp tính toán trong 6.1.3 (MoE, CL, cỡ mẫu) chỉ mang tính minh họa — syllabus ghi rõ
**thí sinh không cần tính toán công thức thống kê trong bài thi**, nên câu hỏi cho mục 6.1.3 nên
dừng ở mức khái niệm (K2: giải thích ý nghĩa MoE/CL, không yêu cầu tính số).

## 3. Phân bổ số lượng câu hỏi theo chương (đề xuất cho Mock Exam)

Syllabus không đính kèm tài liệu "Exam Structure and Rules" (được syllabus mục 0.6 dẫn chiếu là
tài liệu riêng). Do đó, đề xuất phân bổ số câu hỏi thi thử **tỷ lệ theo thời lượng đào tạo mỗi
chương** (tổng 1170 phút = 19.5 giờ) làm mặc định, và cần rà soát lại khi có tài liệu Exam
Structure chính thức của ISTQB cho CT-AI v2.0:

| Chương | Thời lượng | Tỷ trọng đề xuất |
|---|---:|---:|
| 1. Introduction to AI | 120 phút | ~10% |
| 2. Quality Characteristics for AI-Based Systems | 45 phút | ~4% |
| 3. Machine Learning | 375 phút | ~32% |
| 4. Testing AI-Based Systems | 195 phút | ~17% |
| 5. Input Data Testing for ML Systems | 180 phút | ~15% |
| 6. Model Testing for ML Systems | 225 phút | ~19% |
| 7. Machine Learning Development Testing | 30 phút | ~3% |

> Cấu hình tỷ trọng này phải là **tham số có thể chỉnh trong hệ thống** (không hard-code), để cập
> nhật ngay khi có số liệu chính thức từ tài liệu Exam Structure and Rules của ISTQB.

## 4. Yêu cầu giải thích đáp án (answer explanation)

Mỗi câu hỏi phải có:
- Đáp án đúng và giải thích ngắn gọn tại sao đúng.
- Với câu sai phổ biến (distractor), nên giải thích vì sao phương án đó sai (giúp ôn tập hiệu quả).
- Liên kết tới đúng mục lý thuyết nguồn (vd. câu hỏi về Neuron Coverage → liên kết mục 3.4.3).

## 5. Yêu cầu riêng cho câu hỏi dạng tính toán (K3 — 3.3.1)

- Phải cho sẵn bảng Confusion Matrix (TP, FP, FN, TN) trong đề bài.
- Yêu cầu người học tính đúng 1 trong 4 chỉ số: Accuracy, Precision, Recall, F1-score theo đúng
  công thức trong syllabus mục 3.3.1.
- Hệ thống chấm cần cho phép sai số làm tròn hợp lý (vd. ±0.5%) khi so khớp đáp số dạng số.

## 6. Nguồn dữ liệu glossary phục vụ câu hỏi K1

Ngân hàng câu hỏi định nghĩa thuật ngữ nên được sinh/rà soát dựa trên toàn bộ danh sách trong:
- Chapter 8 – List of Abbreviations (viết tắt).
- Chapter 9 – AI-Specific Terms (thuật ngữ và định nghĩa gốc).
