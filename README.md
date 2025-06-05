# Dự án Nhận diện Ký hiệu Tay ASL (ASL Handsign Recognition)

## Mô tả dự án
Dự án này tập trung vào việc phát triển một hệ thống nhận diện ký hiệu tay dựa trên bộ dữ liệu **ASL Handsign Dataset (Grayscaled & Thresholded)**, được tải từ Kaggle. Mục tiêu là áp dụng các thuật toán học máy như K Nearest Neighbor, KMeans, Logistic Regression, Naive Bayes, DBScan, và giảm chiều PCA để phân loại các ký hiệu tay theo ngôn ngữ ký hiệu Mỹ (ASL). Đây là bài tập lớn cho môn học Machine Learning tại trường đại học.

## Thông tin thành viên nhóm
| STT | Họ và Tên         | Mã sinh viên | Công việc phụ trách                                      |
|-----|-------------------|--------------|---------------------------------------------------------|
| 1   | Đỗ Hữu Đạt        | [22000080]      | Nghiên cứu và tổng hợp kiến thức về thuật toán K Nearest Neighbor, KMeans, giảm chiều PCA. |
| 2   | Đỗ Tiến Dũng      | [22000075]      | Nghiên cứu và tổng hợp kiến thức về thuật toán Logistic Regression, chuẩn hóa dữ liệu. |
| 3   | Nguyễn Vĩ Chí Cường | [22000073]      | Nghiên cứu và tổng hợp kiến thức về thuật toán Naive Bayes, DBScan, tiền xử lý và trực quan hóa dữ liệu. |

## Cấu trúc thư mục
- **data/**:
  - **raw/**: Chứa dữ liệu thô từ Kaggle (ASL Handsign Dataset).
  - **processed/**: Chứa dữ liệu đã được xử lý (ví dụ: sau khi giảm chiều, chuẩn hóa).
- **documents/**: Chứa báo cáo chi tiết và slide thuyết trình.
- **src/**: Chứa mã nguồn chính (ví dụ: script tiền xử lý, huấn luyện mô hình).

## Nguồn dữ liệu
Dữ liệu được lấy từ:  
[ASL Handsign Dataset (Grayscaled & Thresholded)](https://www.kaggle.com/datasets/furkanakdeniz/asl-handsign-dataset-grayscaled-thresholded/data).

## Cách tổ chức chương trình
- Ngôn ngữ lập trình: Python.
- Thư viện sử dụng: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`.
- Chương trình được tổ chức thành các script riêng biệt trong thư mục `src/`.
## Lưu ý
- Thư mục `data/processed/` sẽ được cập nhật sau khi chạy các bước tiền xử lý dữ liệu.
- Đảm bảo có quyền truy cập vào bộ dữ liệu trên Kaggle.

## Góp ý và đóng góp
- Mọi đóng góp đều được chào đón! Vui lòng tạo pull request hoặc issue trên repository này.
- Báo cáo lỗi hoặc đề xuất cải tiến qua phần Issues.

---
