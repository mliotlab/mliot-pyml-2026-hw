# HOMEWORK

## Bài 1: Titanic Dataset

Sử dụng lại bộ dữ liệu **Titanic** trong bài tập về nhà trước.

### Yêu cầu

1. Sử dụng **Logistic Regression** để dự đoán hành khách sống sót hay không.
2. Sử dụng cùng cách chia dữ liệu train/test như bài tập trước nếu có thể.
3. Đánh giá kết quả của mô hình Logistic Regression.
4. So sánh kết quả của **Logistic Regression** với kết quả của **Linear Regression** trong bài tập trước.

### Nội dung so sánh

Có thể so sánh dựa trên các chỉ số:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Đưa ra nhận xét về mô hình phù hợp hơn đối với bài toán phân loại hành khách sống sót.

---

## Bài 2: Dry Bean Dataset

Xây dựng mô hình phân loại các loại hạt trong bộ dữ liệu **Dry Bean Dataset** bằng hai thuật toán:

1. **Logistic Regression**
2. **K-Nearest Neighbors – KNN**

### Dữ liệu

Dữ liệu đã được preprocessing (file processing_seeds.ipynb) và chia thành hai tập:

```text
Dry_Bean_Dataset/
├── dry_bean_train.csv
└── dry_bean_test.csv

Các bạn có thể tự tạo file processing để có thể processing theo ý mình