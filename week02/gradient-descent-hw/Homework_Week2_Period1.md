# Homework Week 2 - Period 1

## Chủ đề

Bài tập thực hành Gradient Descent cho hai bài toán cơ bản:

1. **Linear Regression** với bộ dữ liệu một biến `x` và nhãn `y` nằm rải rác quanh một đường thẳng.
2. **Logistic Regression** với bộ dữ liệu một biến `x` và nhãn nhị phân `y`, trong đó hai lớp hơi phân tách nhau.

Hạn chót nộp bài: **23:59 ngày 3/7/2026** (Thứ 6).


## Mục tiêu bài tập

Sau khi hoàn thành bài này, sinh viên cần làm được các việc sau:
- Viết hàm dự đoán cho Linear Regression.
- Tính hàm mất mát MSE cho Linear Regression.
- Tính gradient theo `w` và `b`.
- Cập nhật `w` và `b` bằng Gradient Descent.
- Viết hàm sigmoid cho Logistic Regression.
- Tính Binary Cross Entropy loss.
- Huấn luyện Logistic Regression bằng Gradient Descent.
- Viết hàm vẽ biểu đồ để quan sát loss và kết quả dự đoán.

## Hình thức nộp bài

Sinh viên chỉnh sửa trực tiếp file notebook `gradient_descent_hw.ipynb` và push lên fork repository của mình. Thêm tên và mã số sinh viên vào đầu file notebook.

Yêu cầu khi nộp:

- Tất cả các cell code phải chạy được từ đầu đến cuối theo thứ tự.
- Không để lại lỗi runtime trong notebook.
- Không xóa dữ liệu, biến khởi tạo, hoặc đề bài đã cho.
- Có in ra kết quả huấn luyện cuối cùng cho cả hai bài.
- Có biểu đồ visualize cho cả Linear Regression và Logistic Regression.
- Chỉ dùng `numpy` cho phần tính toán và `matplotlib` cho phần vẽ biểu đồ.

## Thang điểm

Tổng điểm: **10 điểm**

| Hạng mục | Điểm |
|---|---:|
| Hoàn thiện đúng hàm dự đoán, loss và gradient cho Linear Regression | 2.0 |
| Huấn luyện Linear Regression đúng bằng Gradient Descent, loss giảm hợp lý | 1.5 |
| Vẽ được biểu đồ kết quả Linear Regression | 1.0 |
| Hoàn thiện đúng sigmoid, Binary Cross Entropy và gradient cho Logistic Regression | 2.0 |
| Huấn luyện Logistic Regression đúng bằng Gradient Descent, loss giảm hợp lý | 1.5 |
| Vẽ được biểu đồ kết quả Logistic Regression | 1.0 |
| Notebook sạch, chạy tuần tự không lỗi, trình bày dễ đọc | 1.0 |

## Gợi ý kiểm tra trước khi nộp

Trước khi nộp, hãy chọn **Restart Kernel** rồi chạy lại toàn bộ notebook từ trên xuống dưới.

Nếu notebook chạy hết, có loss giảm, có kết quả cuối cùng và có biểu đồ cho cả hai bài, bài nộp đã đạt yêu cầu cơ bản.
