# Pandas Exercises Solutions

Folder này chứa các bài tập Pandas đã được hoàn thiện dưới dạng Jupyter Notebook.
Mỗi notebook giữ nguyên cấu trúc đề bài và điền lời giải trực tiếp vào các ô code.

## Cách chạy

```powershell
cd "C:\Users\duong\Documents\New project\pandas_exercises_solutions"
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter lab
```

Sau đó mở notebook trong từng thư mục bài tập.

## Ghi chú dữ liệu

- Hầu hết notebook đọc dataset local trong cùng thư mục để dễ chạy offline.
- File `01_Getting_&_Knowing_Your_Data/World Food Facts/products.tsv` rất lớn, khoảng 1GB, nên đã được đưa vào `.gitignore` để tránh lỗi khi upload GitHub. File vẫn đang nằm local để bạn chạy notebook nếu cần.
- Dataset `US_Crime_Rates_1960_2014.csv` đã được thêm vào thư mục bài `05_Apply/US_Crime_Rates`.

## Kiểm tra đã thực hiện

- Đã xác nhận 21 notebook đều có code, không còn ô code trống.
- Đã kiểm tra cú pháp toàn bộ code cells.
- Đã chạy thử 15 notebook không phụ thuộc `matplotlib/seaborn`; tất cả chạy thành công.
- Các notebook visualization cần cài thư viện trong `requirements.txt` để chạy biểu đồ.
