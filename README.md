# From LinearSVM to Real‑life Implementation

Dự án này chứa toàn bộ tài liệu cho buổi chia sẻ **“From LinearSVM to Real‑life Implementation”** – một hướng dẫn toàn diện về Máy Vector Hỗ Trợ (SVM), từ trực quan hình học, nền tảng toán học cho đến triển khai thực tế trên Python.

Kho lưu trữ bao gồm:
- Slide thuyết trình LaTeX (Beamer) với đầy đủ hình vẽ TikZ và công thức.
- Notebook Jupyter thực hành phân loại chữ số viết tay (MNIST 0 vs 1).
- Các tệp hỗ trợ (hình ảnh, font, v.v.).

---

## Cấu trúc dự án
```txt
tree
.
├── nminst.ipynb     # Bài thực hành
├── README.md
└── slides
    ├── appendix
    │   └── dual_form.tex # Bài chứng minh
    ├── img
    └── src
```

## Làm sao để bắt đầu?
### Yêu cầu 
- Python 3.8+
- Các thư viện: `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`, `statsmodels`, `jupyter`.
> Cài đặt nhanh: `pip install numpy matplotlib seaborn scikit-learn scipy statsmodels notebook`

### Hướng dẫn thực hành
Chạy từng cell theo thứ tự. Notebook đã bao gồm các bước:
1. EDA cơ bản (thống kê, trực quan hóa).
2. Tiền xử lý (StandardScaler).
3. Huấn luyện LinearSVC và SVC với kernel RBF.
4. Đo thời gian huấn luyện.
5. Tối ưu siêu tham số bằng GridSearchCV.
6. Kiểm định thống kê (paired t‑test).


## Credit
- Long Nguyen Hoang – University of Information Technology, VNU‑HCM.

> *Nếu bạn có bất kỳ câu hỏi hoặc góp ý nào, vui lòng mở Issue hoặc liên hệ qua email longnguyenhoang.personal@gmail.com.*