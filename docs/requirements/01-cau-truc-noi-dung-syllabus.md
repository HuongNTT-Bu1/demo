# Cấu trúc nội dung Syllabus CT-AI v2.0 (dùng làm cấu trúc content của website)

Đây là yêu cầu về cấu trúc dữ liệu nội dung: mỗi **chương (chapter)** là 1 đơn vị ôn tập lý thuyết,
mỗi **mục (section)** là 1 đơn vị bài học nhỏ, gắn với **từ khóa (keywords)** và **Learning
Objectives (LO)** dùng để sinh câu hỏi luyện thi.

Tổng thời lượng đào tạo tối thiểu: **19.5 giờ**, chia theo 7 chương thi.

Mức độ nhận thức (Cognitive Level): **K1** Remember, **K2** Understand, **K3** Apply, **K4** Analyze.
Mức độ Hands-on (không thi nhưng nên có bài tập thực hành minh họa trong phần ôn tập): **H0/H1/H2**.

---

## Chapter 1 – Introduction to Artificial Intelligence (120 phút)

**Từ khóa AI-specific**: AI-based system, artificial intelligence, general AI, machine learning,
ML development framework, narrow AI, super AI

| Mục | Tên | LO |
|---|---|---|
| 1.1.1 | AI-Based and Conventional Systems | AI-1.1.1 (K2) Phân biệt hệ thống AI-based và hệ thống truyền thống |
| 1.1.2 | Narrow AI, General AI, and Super AI | AI-1.1.2 (K2) Phân biệt narrow AI, general AI, super AI |
| 1.1.3 | Different Types of AI Technologies | AI-1.1.3 (K2) Giải thích các loại công nghệ AI |
| 1.1.4 | Generative AI | AI-1.1.4 (K2) Giải thích Generative AI |
| 1.1.5 | Hardware for Machine Learning Systems | AI-1.1.5 (K2) So sánh các lựa chọn phần cứng cho MLS |
| 1.1.6 | Development and Hosting of AI Models | AI-1.1.6 (K2) So sánh các phương án phát triển/hosting mô hình AI |
| 1.1.7 | Machine Learning Development Frameworks | AI-1.1.7 (K2) Tóm tắt chức năng của ML development framework |
| 1.1.8 | Regulations and Standards for AI | AI-1.1.8 (K2) Giải thích ảnh hưởng của quy định/tiêu chuẩn đến phát triển và kiểm thử AI |

---

## Chapter 2 – Quality Characteristics for AI-Based Systems (45 phút)

**Từ khóa**: Functional adaptability, AI functional correctness, intervenability, AI robustness,
safety, societal and ethical risk mitigation, transparency, user controllability

| Mục | Tên | LO |
|---|---|---|
| 2.1.1 | AI-Specific Quality Characteristics | AI-2.1.1 (K2) Phân loại hành vi hệ thống AI theo đặc tính chất lượng ISO/IEC 25059 |
| 2.1.2 | AI and Safety | AI-2.1.2 (K2) Giải thích các cân nhắc đặc biệt khi AI dùng trong hệ thống an toàn |
| 2.2.1 | Acceptance Criteria for AI-Based Systems | AI-2.2.1 (K2) Cho ví dụ về tiêu chí chấp nhận cho hệ thống AI |

---

## Chapter 3 – Machine Learning (375 phút) — chương nặng nhất

**Từ khóa**: K-multisection neuron coverage, ML functional performance criteria/metric, ML model,
neuron boundary coverage, neuron coverage, perceptron; Association, classification, clustering,
data preparation, ML algorithm, ML development framework, ML workflow, pretrained model,
ML regression, reinforcement learning, supervised/unsupervised learning

| Mục | Tên | LO |
|---|---|---|
| 3.1.1 | Different Forms of Machine Learning | AI-3.1.1 (K2) Phân biệt các hình thức ML (supervised/unsupervised/reinforcement) |
| 3.1.2 | Machine Learning Workflow | AI-3.1.2 (K2) Tóm tắt quy trình (workflow) tạo hệ thống ML |
| 3.1.4 | Pretrained Models, Fine-Tuning, RAG | AI-3.1.4 (K2) Tóm tắt việc dùng pretrained model, fine-tuning, RAG |
| 3.2.1 | Activities in Data Preparation | AI-3.2.1 (K2) Giải thích các hoạt động chuẩn bị dữ liệu |
| 3.2.3 | Training, Validation, Test Datasets | AI-3.2.3 (K2) So sánh việc dùng tập train/validation/test |
| 3.3.1 | ML Functional Performance Metrics | AI-3.3.1 (K3) Tính các chỉ số hiệu năng ML từ confusion matrix (Accuracy, Precision, Recall, F1) |
| 3.4.1 | Structure and Working of a Deep Neural Network | AI-3.4.1 (K2) Giải thích cấu trúc & hoạt động của DNN |
| 3.4.3 | Coverage Measures for Neural Networks | AI-3.4.3 (K2) Mô tả các độ đo coverage cho neural network (Neuron Coverage, kMNC, NBC) |

Bài tập thực hành (không thi, nhưng nên minh họa trong phần ôn tập):
3.1.3 Create an ML Model, 3.2.2 Data Preparation, 3.3.2/3.3.3 Evaluate Model & Metrics,
3.4.2 Implement a Perceptron.

---

## Chapter 4 – Testing AI-Based Systems (195 phút)

**Từ khóa**: Attack, exploratory testing, risk-based testing, test oracle; Adaptive/locked
AI-based system, generative AI, large language model

| Mục | Tên | LO |
|---|---|---|
| 4.1.1 | Locked and Adaptive AI-Based Systems | AI-4.1.1 (K2) So sánh khả năng kiểm thử của hệ thống locked và adaptive |
| 4.1.2 | Rationale for a Statistical Approach | AI-4.1.2 (K2) Giải thích lý do cần cách tiếp cận thống kê khi test AI |
| 4.1.3 | Test Oracles for AI-Based Systems | AI-4.1.3 (K2) Giải thích thách thức & giải pháp cho test oracle với hệ thống AI |
| 4.2.1 | Testing Generative AI | AI-4.2.1 (K2) Giải thích cách kiểm thử Generative AI |
| 4.2.2 | Red Teaming | AI-4.2.2 (K3) Áp dụng red teaming cho hệ thống GenAI |
| 4.3.1 | Test Levels for Machine Learning Systems | AI-4.3.1 (K2) Tóm tắt các test level dùng cho MLS |
| 4.3.2 | Risk-Based Testing of ML Systems | AI-4.3.2 (K2) Giải thích cách áp dụng risk-based testing cho MLS |

---

## Chapter 5 – Input Data Testing for Machine Learning Systems (180 phút)

**Từ khóa**: Data pipeline testing, data representativeness testing, dataset constraint testing,
input data testing, label correctness testing, review, testing for bias; Disparate impact
analysis, multiple annotation

| Mục | Tên | LO |
|---|---|---|
| 5.1.1 | Input Data Risks and Mitigations | AI-5.1.1 (K2) Cho ví dụ các cách kiểm thử giảm thiểu rủi ro dữ liệu đầu vào |
| 5.1.2 | Testing for Bias | AI-5.1.2 (K2) Giải thích cách test bias (data bias, algorithmic bias, disparate impact analysis) |
| 5.1.3 | Data Pipeline Testing | AI-5.1.3 (K2) Tóm tắt các hình thức test data pipeline |
| 5.1.4 | Testing for Data Representativeness | AI-5.1.4 (K2) Giải thích cách test tính đại diện của dữ liệu |
| 5.1.5 | Dataset Constraint Testing | AI-5.1.5 (K3) Áp dụng dataset constraint testing (single-value, multi-value, comparison constraint) |
| 5.1.6 | Label Correctness Testing | AI-5.1.6 (K2) Giải thích label correctness testing |

---

## Chapter 6 – Model Testing for Machine Learning Systems (225 phút)

**Từ khóa**: A/B testing, adversarial testing, back-to-back testing, concept drift, data drift,
drift testing, metamorphic testing, ML functional performance, ML model testing, review;
Overfitting, underfitting

| Mục | Tên | LO |
|---|---|---|
| 6.1.1 | ML Model Risks and Mitigations | AI-6.1.1 (K2) Cho ví dụ về cách giảm thiểu rủi ro mô hình ML |
| 6.1.2 | ML Model Documentation and Review | AI-6.1.2 (K2) Giải thích mục đích & trọng tâm review tài liệu mô hình (Model Cards, Datasheets) |
| 6.1.3 | ML Functional Performance Testing (probabilistic MLS) | AI-6.1.3 (K2) Giải thích cách test hiệu năng chức năng cho hệ thống ML xác suất (MoE, CL) |
| 6.1.4 | Adversarial Testing | AI-6.1.4 (K2) Tóm tắt adversarial testing (black-box/white-box) |
| 6.1.5 | Metamorphic Testing | AI-6.1.5 (K3) Dùng metamorphic testing để suy ra test case (metamorphic relation) |
| 6.1.7 | Drift Testing | AI-6.1.7 (K2) Giải thích drift testing (data drift, concept drift; static/dynamic) |
| 6.1.8 | Overfitting and Underfitting | AI-6.1.8 (K2) Giải thích cách phát hiện overfitting/underfitting |
| 6.1.9 | A/B Testing | AI-6.1.9 (K2) Giải thích cách dùng A/B testing với MLS |
| 6.1.10 | Back-to-Back Testing | AI-6.1.10 (K2) Giải thích cách dùng back-to-back testing với MLS |

---

## Chapter 7 – Machine Learning Development Testing (30 phút)

**Từ khóa**: ML development testing, ML functional performance, shadow testing

| Mục | Tên | LO |
|---|---|---|
| 7.1.1 | ML Development Risks and Mitigations | AI-7.1.1 (K2) Cho ví dụ cách giảm thiểu rủi ro trong phát triển ML |
| 7.1.2 | ML System Deployment Testing | AI-7.1.2 (K2) Giải thích các hình thức test triển khai MLS (installability, rollback, canary, shadow, model conversion, cross-device, API testing) |

---

## Nội dung tham khảo bổ sung (không thi trực tiếp nhưng hỗ trợ ôn tập)

- **Chapter 8 – List of Abbreviations**: dùng cho tính năng tra cứu viết tắt (AI, AIaaS, API, CL, CNN,
  CPU, DL, DNN, EDA, FN, FP, GAN, GenAI, GPU, HO, IAA, kMNC, LIME, LLM, LO, ML, MLS, MoE, NBC,
  NLP, RAG, RNN, RT, SVM, TN, TP...).
- **Chapter 9 – AI-Specific Terms**: nguồn dữ liệu cho module **Glossary** (định nghĩa thuật ngữ AI).
- **Appendix A – Learning Objectives/Cognitive Level**: cơ sở để gắn nhãn K-level cho từng câu hỏi.
- **Appendix B – Business Outcomes Traceability Matrix**: dùng để map câu hỏi/chủ đề về đúng BO,
  phục vụ tính năng thống kê tiến độ theo BO.

## Yêu cầu đối với dữ liệu nội dung trên website

1. Mỗi **mục lý thuyết** hiển thị: tiêu đề, số hiệu mục (vd. 3.3.1), nội dung tóm tắt, từ khóa liên
   quan, mã LO + mức K, liên kết chương cha, và (nếu có) bảng/công thức/hình minh họa gốc từ
   syllabus (vd. công thức Accuracy/Precision/Recall/F1 ở 3.3.1, Confusion Matrix ở Figure 2, ML
   Workflow ở Figure 1).
2. Cấu trúc dữ liệu phải cho phép lọc/duyệt theo: Chương → Mục → LO → Mức K → Từ khóa.
3. Phải giữ đúng số liệu, công thức, ví dụ nêu trong syllabus (không được diễn giải sai định nghĩa,
   vì đây là nội dung thi).
