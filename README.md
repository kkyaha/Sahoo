# SAHOO: Safeguarded Alignment for High-Order Optimization Objectives in Recursive Self-Improvement

Codebase này nghiên cứu các cơ chế đảm bảo alignment an toàn cho các hệ thống tự cải thiện đệ quy.

## 📁 Cấu trúc Thư mục

```
.
├── docs/                       # Tài liệu và báo cáo
│   ├── README.md              # File này
│   ├── report.md              # Báo cáo chính
│   ├── theoretical_analysis.md # Phân tích lý thuyết
│   └── LICENSE                # Giấy phép
│
├── data/                       # Dữ liệu và kết quả
│   ├── results/               # Kết quả thực nghiệm
│   │   ├── results_code_generation.json
│   │   ├── results_mathematical_reasoning.json
│   │   ├── results_truthfulness.json
│   │   └── full_results.json
│   ├── analyses/              # Phân tích dữ liệu
│   │   ├── statistical_analysis.json
│   │   ├── stability_analyses.json
│   │   ├── theoretical_bounds.json
│   │   ├── intervention_recommendations.json
│   │   └── summary_statistics.json
│   └── raw/                   # Dữ liệu thô
│       ├── cycles_data.csv
│       └── stability_data.csv
│
├── visualizations/            # Biểu đồ và hình ảnh
│   ├── capability_alignment_tradeoff.png
│   ├── constraint_violations.png
│   ├── drift_trajectories.png
│   ├── stability_analysis.png
│   └── summary_dashboard.png
│
├── notebooks/                 # Jupyter notebooks
│   └── Recursive_Self_Improvement_ICLR_26.ipynb
│
├── logs/                      # Nhật ký thực nghiệm
│   ├── experiment.log
│   └── metrics.jsonl
│
└── config/                    # Cấu hình
    └── config.json
```

## 📊 Mô Tả Từng Thư mục

### `docs/`
Chứa tất cả tài liệu kỹ thuật, báo cáo và giấy phép.

### `data/`
**results/** - Kết quả thực nghiệm cho các khía cạnh khác nhau:
- Code generation
- Mathematical reasoning
- Truthfulness
- Full results (toàn bộ kết quả)

**analyses/** - Phân tích thống kê và lý thuyết của dữ liệu

**raw/** - Dữ liệu thô dùng cho các biểu đồ

### `visualizations/`
Tất cả các biểu đồ, hình ảnh kết quả để dễ dàng tham khảo.

### `notebooks/`
Jupyter notebooks chứa code thực nghiệm và phân tích.

### `logs/`
Nhật ký chi tiết từ các lần chạy thực nghiệm.

### `config/`
Các file cấu hình cho thực nghiệm.

## 🚀 Bắt Đầu

1. Đọc `docs/report.md` để hiểu tổng quan
2. Xem `docs/theoretical_analysis.md` cho chi tiết lý thuyết
3. Khám phá `notebooks/Recursive_Self_Improvement_ICLR_26.ipynb` cho code
4. Kiểm tra các biểu đồ trong `visualizations/` để visualize kết quả
5. Xem dữ liệu chi tiết trong `data/results/` và `data/analyses/`

## 📝 Ghi Chú

- Cấu trúc này được tối ưu hóa để dễ đọc, dễ tìm kiếm và tổ chức tài liệu
- Sử dụng thư mục con rõ ràng để phân tách các loại dữ liệu khác nhau
- Logs được lưu riêng để dễ theo dõi quá trình thực nghiệm
