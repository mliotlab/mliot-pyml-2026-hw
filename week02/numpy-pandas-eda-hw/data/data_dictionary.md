# Automobile Data Dictionary

Mỗi dòng đại diện cho một mẫu xe trong bộ 1985 Auto Imports.
Giá trị thiếu trong `automobile_raw.csv` được giữ dưới dạng ký hiệu `?`.

| Column | Expected type | Meaning | Unit / values | Missing |
|---|---|---|---|---:|
| `symboling` | integer | Mức đánh giá rủi ro bảo hiểm | -3 đến 3 | 0 |
| `normalized_losses` | numeric | Mức tổn thất bảo hiểm trung bình đã chuẩn hóa | relative score | 41 |
| `make` | categorical | Hãng sản xuất | - | 0 |
| `fuel_type` | categorical | Loại nhiên liệu | gas/diesel | 0 |
| `aspiration` | categorical | Cơ chế nạp khí của động cơ | std/turbo | 0 |
| `num_doors` | categorical | Số cửa | two/four | 2 |
| `body_style` | categorical | Kiểu thân xe | - | 0 |
| `drive_wheels` | categorical | Hệ dẫn động | fwd/rwd/4wd | 0 |
| `engine_location` | categorical | Vị trí động cơ | front/rear | 0 |
| `wheel_base` | numeric | Khoảng cách giữa tâm hai trục bánh xe | inches | 0 |
| `length` | numeric | Chiều dài xe | inches | 0 |
| `width` | numeric | Chiều rộng xe | inches | 0 |
| `height` | numeric | Chiều cao xe | inches | 0 |
| `curb_weight` | numeric | Khối lượng xe với trang bị tiêu chuẩn | pounds | 0 |
| `engine_type` | categorical | Kiến trúc động cơ | - | 0 |
| `num_cylinders` | categorical | Số xi-lanh | - | 0 |
| `engine_size` | numeric | Dung tích động cơ | cubic inches | 0 |
| `fuel_system` | categorical | Loại hệ thống nhiên liệu | - | 0 |
| `bore` | numeric | Đường kính xi-lanh | inches | 4 |
| `stroke` | numeric | Hành trình piston | inches | 4 |
| `compression_ratio` | numeric | Tỷ số nén | ratio | 0 |
| `horsepower` | numeric | Công suất động cơ | hp | 2 |
| `peak_rpm` | numeric | Tốc độ động cơ tại công suất cực đại | rpm | 2 |
| `city_mpg` | numeric | Mức tiết kiệm nhiên liệu trong đô thị | miles per gallon | 0 |
| `highway_mpg` | numeric | Mức tiết kiệm nhiên liệu trên cao tốc | miles per gallon | 0 |
| `price` | numeric | Giá xe | USD | 4 |

## Core analysis columns

Các bài NumPy định lượng sử dụng 6 cột sau:

`curb_weight`, `engine_size`, `horsepower`, `city_mpg`, `highway_mpg`, `price`

## Source

- UCI Machine Learning Repository: Automobile dataset.
- Original data file: `imports-85.data`.
- Dataset DOI: <https://doi.org/10.24432/C5B01C>.
- UCI lists the dataset under the CC BY 4.0 license.
