# Seminar Report - PIXIU: A Comprehensive Benchmark for Financial LLMs

## Giới thiệu
Đây là repository chứa toàn bộ nội dung nghiên cứu và thực nghiệm của sinh viên đối với đề tài seminar:

> **Chủ đề**: Nghiên cứu và trình bày theo chủ đề seminar: [PIXIU - A Comprehensive Benchmark for Financial LLMs](https://github.com/The-FinAI/PIXIU)

- Dịch và tìm hiểu chi tiết bài báo gốc.
- Trình bày slide và báo cáo cá nhân.
- Triển khai các thực nghiệm phụ trợ như: **Credit Scoring**, **Knowledge Extraction**, **Sentiment Analysis**, và **Text Summarization**.

---

##  Cấu trúc thư mục

| Tên File / Thư mục               | Mô tả                                                                 |
|----------------------------------|----------------------------------------------------------------------|
| `155_PIXIU_A_Comprehensive_Benc.pdf` | Bài báo gốc của đề tài seminar (tiếng Anh)                         |
| `topic-translate.pdf`            | Bản dịch tiếng Việt của bài báo                                      |
| `slide.pdf`                      | Slide trình bày bài thuyết trình                                     |
| `report_seminar.pdf`            | Báo cáo nghiên cứu của cá nhân theo yêu cầu seminar                  |
| `dataset/`                       | Thư mục chứa các tập dữ liệu phục vụ cho phần thực nghiệm            |
| `credit_scoring.ipynb`           | Thử nghiệm về mô hình dự đoán điểm tín dụng tài chính               |
| `knowledge_extraction.ipynb`     | Thực nghiệm trích xuất tri thức (NER & FiNER-Ord) trên FLARE         |
| `test_finma_sentiment.ipynb`     | Đánh giá cảm xúc văn bản tài chính với mô hình FinMA                 |
| `text_summarization.ipynb`       | Tóm tắt văn bản tài chính bằng mô hình LLM                           |
| `README.md`                      | (Chính là file này)                                                  |

---

##  Các phần thực nghiệm

1. **Knowledge Extraction (NER)**
   - Áp dụng mô hình BERT để trích xuất thực thể trên hai tập dữ liệu: `flare_ner.csv` và `flare_finer_ord.csv`.
   - Đánh giá kết quả bằng `seqeval.metrics` (precision, recall, F1).

2. **Credit Scoring**
   - Dự đoán rủi ro tín dụng bằng mô hình học máy cơ bản.
   - Thực hiện xử lý dữ liệu, huấn luyện và đánh giá.

3. **FinMA Sentiment Analysis**
   - Kiểm thử mô hình `FinMA` trong việc phân tích cảm xúc từ các câu trích xuất từ văn bản tài chính.

4. **Text Summarization**
   - Tóm tắt các văn bản tài chính bằng LLM (`BART`, `T5`, v.v.)

---

##  Thông tin thêm

- Chủ đề seminar thuộc lĩnh vực **Ngôn ngữ tự nhiên trong tài chính**.
- Bài báo PIXIU cung cấp chuẩn benchmark quan trọng cho đánh giá LLM tài chính.
- Dữ liệu thực nghiệm chủ yếu đến từ bộ **FLARE benchmark** và mô hình open-source.

---

##  Thực hiện bởi

- **Sinh viên**: *Hoàng Mạnh Hùng*  
- **Môn học**: Seminar khoa học  
- **Giảng viên hướng dẫn**: *[TS. Trần Hồng Việt]*  
- **Thời gian thực hiện**: 2025

---

##  Tham khảo

-  [Bài báo PIXIU trên arXiv](https://arxiv.org/abs/2403.08195)  
-  [PIXIU GitHub Repository](https://github.com/The-FinAI/PIXIU)  
-  [FLARE Benchmark](https://huggingface.co/datasets/ynie/FLARE)

---

