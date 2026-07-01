# Homework Week 2 - Period 2

## Chủ đề

NumPy, Pandas và Exploratory Data Analysis với bộ dữ liệu Automobile.

Hạn nộp bài: **theo thông báo của khóa học**.

## Mục tiêu

Sau khi hoàn thành, sinh viên cần:

- hiện thực stable softmax cho một batch logits bằng NumPy;
- chuẩn hóa train/validation mà không làm rò rỉ thông tin từ validation;
- dùng boolean mask để xác định các prediction cần kiểm tra;
- xử lý và augment một batch ảnh, đồng thời kiểm soát view/copy;
- phát hiện missing marker và chuyển dtype phù hợp bằng Pandas;
- chuyển dữ liệu từ DataFrame sang NumPy để tính toán;
- thực hiện EDA bằng Matplotlib và Seaborn;
- viết nhận xét có dẫn chứng từ bảng thống kê hoặc biểu đồ.

## File bài tập

```text
week02/numpy-pandas-eda-hw/
|-- README.md
|-- numpy_pandas_eda_hw.ipynb
`-- data/
    |-- automobile_raw.csv
    `-- data_dictionary.md
```

Sinh viên chỉ chỉnh sửa:

```text
week02/numpy-pandas-eda-hw/numpy_pandas_eda_hw.ipynb
```

Không đổi tên hoặc di chuyển notebook. Không chỉnh sửa hai file trong `data/`.

## Hình thức nộp bài

1. Điền `STUDENT_NAME` và `STUDENT_ID` ở đầu notebook.
2. Hoàn thành các cell `TODO` và giữ nguyên tên biến đầu ra được yêu cầu.
3. Chọn **Restart Kernel** và chạy lại toàn bộ notebook.
4. Commit trực tiếp file notebook vào fork:

   ```bash
   git add week02/numpy-pandas-eda-hw/numpy_pandas_eda_hw.ipynb
   git commit -m "week02: complete numpy pandas eda homework"
   git push origin main
   ```

5. Gửi link fork theo hướng dẫn của khóa học. Không cần đổi tên file, tạo zip
   hoặc gửi notebook riêng.

## Dữ liệu

`automobile_raw.csv` đã được thêm header và chuẩn hóa tên cột. Dấu `?` vẫn được
giữ để sinh viên thực hành missing values và dtype conversion.

Đọc [`data/data_dictionary.md`](data/data_dictionary.md) trước khi bắt đầu.

## Yêu cầu

- Notebook phải chạy từ trên xuống không có runtime error sau khi hoàn thành.
- Giữ nguyên tên các biến đầu ra được yêu cầu trong notebook.
- Biểu đồ phải có title, axis labels và đơn vị khi phù hợp.
- Mỗi biểu đồ cần ít nhất một nhận xét ngắn.
- Không train machine learning model trong bài này.

## Kiểm tra trước khi nộp

- [ ] Đã điền họ tên và MSSV.
- [ ] Không còn cell `TODO` chưa hoàn thành.
- [ ] Restart Kernel và Run All không lỗi.
- [ ] Không đổi tên notebook.
- [ ] Không chỉnh sửa dataset.
- [ ] Đã commit và push notebook lên fork.
