# Phân tích cảm xúc bình luận tiếng Việt trên nền tảng thương mại điện tử

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 1. Giới thiệu đề tài
Dự án này tập trung vào việc xây dựng và đánh giá các mô hình xử lý ngôn ngữ tự nhiên (NLP) nhằm phân loại cảm xúc (Tích cực, Tiêu cực, Trung tính) từ dữ liệu đánh giá sản phẩm của người dùng Việt Nam.

## 2. Mục tiêu
* Xây dựng bộ dữ liệu sạch đã được gán nhãn chuẩn hóa cho bài toán phân tích cảm xúc tiếng Việt.
* So sánh hiệu năng giữa các phương pháp học máy truyền thống (TF-IDF + SVM) và học sâu (PhoBERT).
* Cung cấp mã nguồn mở phục vụ mục đích học tập và nghiên cứu tiếp nối.

## 3. Phương pháp thực hiện
* **Tiền xử lý dữ liệu:** Chuẩn hóa từ viết tắt, loại bỏ nhiễu, tách từ tiếng Việt bằng thư viện `underthesea`.
* **Huấn luyện mô hình:** Tinh chỉnh (fine-tuning) mô hình ngôn ngữ tiền huấn luyện PhoBERT-base.
* **Đánh giá:** Sử dụng độ đo Accuracy và Macro F1-Score trên tập kiểm thử độc lập.

## 4. Kết quả bước đầu
* Mô hình PhoBERT đạt độ chính xác **89.4%** và F1-Score **0.88**, vượt trội hơn 6.2% so với mô hình cơ sở SVM.

## 5. Giấy phép (License)
Dự án này được phát hành dưới giấy phép **MIT License**. Xem chi tiết tại tệp [LICENSE](./LICENSE).# BanQuyenNoiDungSo
Bản quyền nội dung số
