# Bài tập — Khóa hè Python & Machine Learning + Embedded C 2026

Repo **gốc (upstream)** chứa đề bài và khung nộp bài của khóa học — Machine Learning & IoT Lab, HCMUT.

> 📅 20/6 – 30/8/2026 · Thứ Bảy & Chủ Nhật (Python & ML) · Chủ nhật (Embedded C)

---

## 🚀 Hướng dẫn cho học viên (luồng Fork)

### Bước 1 — Fork repo gốc
Vào repo này trên GitHub, bấm nút **Fork** (góc trên bên phải) → GitHub tạo một **repo cá nhân** của bạn (đây là remote `origin`).

### Bước 2 — Clone fork của bạn về máy
```bash
git clone https://github.com/<ten-cua-ban>/mliot-pyml-2026-hw.git
cd mliot-pyml-2026-hw
```

### Bước 3 — Thêm remote `upstream` trỏ về repo gốc
```bash
git remote add upstream https://github.com/mliotlab/mliot-pyml-2026-hw.git
git remote -v          # kiem tra: co origin (fork cua ban) va upstream (repo goc)
```

> **Hai remote:** `origin` = fork cá nhân của bạn · `upstream` = repo gốc của Lab.

---

## 🔄 Mỗi buổi học

### Lấy đề mới (cập nhật từ repo gốc)
Đề bài của các buổi được thêm dần vào repo gốc. Trước mỗi buổi, đồng bộ:
```bash
git pull upstream main
```

### Làm bài & nộp
Làm bài trong thư mục tuần tương ứng (`weekXX/`), rồi đẩy lên fork cá nhân:
```bash
git add week01/
git commit -m "week01: hoan thanh bai tap buoi 1"
git push origin main
```

### Nộp bài cho mentor
- Cách 1 (mặc định): gửi **link repo cá nhân (fork)** của bạn trên Discord để mentor vào check.
- Cách 2 (nếu mentor yêu cầu): tạo **Pull Request** từ fork của bạn về repo gốc để mentor review.

---

## 📁 Cấu trúc thư mục

| Thư mục | Tuần | Nội dung |
|---|---|---|
| `week01` | Tuần 1 | Buổi 1 — Đại số tuyến tính · Buổi 2 — Xác suất thống kê |
| `week02` | Tuần 2 | Buổi 3 — Gradient Descent · Buổi 4 — NumPy, Pandas & Visualization |
| `week03` | Tuần 3 | Buổi 5 — ML & Tiền xử lý · Buổi 6 — Linear Regression |
| `week04` | Tuần 4 | Buổi 7 — Logistic & KNN · Buổi 8 — Tree & Random Forest |
| `week05` | Tuần 5 | Buổi 9 — Clustering · Buổi 10 — SVD |
| `week06` | Tuần 6 | Buổi 11 — SVM · Buổi 12 — Ensemble + **Kiểm tra giữa kỳ** |
| `week07` | Tuần 7 | Buổi 13 — Deep Learning & MLP · Buổi 14 — CNN |
| `week08` | Tuần 8 | Buổi 15 — Attention & Transformer · Buổi 16 — Object Detection |
| `week09` | Tuần 9 | Buổi 17 — LLM & Agent · Buổi 18 — Multimodal |
| `week10` | Tuần 10 | Buổi 19–20 — Final Project |
| `week11` | Tuần 11 | Buổi 21–22 — Final Project |

---

## 📝 Quy ước nộp bài

- Đặt bài làm vào **đúng thư mục tuần** (`weekXX/`).
- Định dạng: notebook `.ipynb` hoặc file `.py`; đặt tên rõ ràng, ví dụ `buoi01_nguyenvana.ipynb`.
- Nếu đề đã cung cấp notebook khung, chỉnh sửa trực tiếp file đó và **không đổi tên hoặc di chuyển file**.
- Commit message rõ ràng: `week01: hoan thanh bai tap buoi 1`.
- **Không commit** dữ liệu lớn / file nặng (đã cấu hình trong `.gitignore`).

## ⚙️ Cài đặt môi trường

```bash
pip install -r requirements.txt
```

---

## ℹ️ Ghi chú

- Nếu `git pull upstream main` báo xung đột (conflict): thường do bạn sửa cùng file với repo gốc — giữ phần bài làm của bạn trong `weekXX/` và giải quyết conflict theo hướng dẫn của mentor.
- Repo gốc nên để **Public** để học viên fork được.

---

*Machine Learning & IoT Lab — Khoa Điện–Điện tử,Trường Đại học Bách khoa - ĐHQG TP.HCM*
