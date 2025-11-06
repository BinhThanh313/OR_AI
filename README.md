# Dự báo nhu cầu bán lẻ & tối ưu tồn kho (Instacart)

• Dataset tham khảo: Instacart Online Grocery 2017 (3M đơn hàng).
 Tải: https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset
• Bài toán OR: Mô hình đa mặt hàng nhiều kỳ (ILP/LP) tối thiểu chi phí đặt,
 lưu kho, thiếu hụt; ràng buộc mức dịch vụ.
• AI/ML: Dự báo nhu cầu (hàng × tuần) bằng RF/LightGBM.
• Kết quả dự kiến: Đường cong chi phí–mức dịch vụ; so sánh baseline tồn kho
 định mức vs. forecast-driven.

## Cấu trúc dự án

1. `1_EDA.ipynb`: Phân tích khám phá dữ liệu
2. `2_Feature_Engineering.ipynb`: Xử lý và tạo đặc trưng
3. `3_Forecasting_Model.ipynb`: Mô hình dự báo
4. `4_Optimization_Model.ipynb`: Mô hình tối ưu tồn kho

## Yêu cầu

- Python 3.8+
- Các thư viện chính:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
  - pyscipopt

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/BinhThanh313/OR_AI.git
```

2. Cài đặt các thư viện cần thiết:
```bash
pip install -r requirements.txt
```

## Sử dụng

1. Chạy các notebook theo thứ tự:
   - `1_EDA.ipynb`: Hiểu về dữ liệu
   - `2_Feature_Engineering.ipynb`: Chuẩn bị dữ liệu
   - `3_Forecasting_Model.ipynb`: Dự báo nhu cầu
   - `4_Optimization_Model.ipynb`: Tối ưu kế hoạch tồn kho


