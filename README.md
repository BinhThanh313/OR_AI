# Dự báo nhu cầu bán lẻ & tối ưu tồn kho (Instacart)

Dự án này thực hiện **dự báo nhu cầu bán lẻ** và **tối ưu hóa tồn kho** cho sản phẩm trong dữ liệu Instacart Online Grocery 2017.

- **Dataset tham khảo:** Instacart Online Grocery 2017 (~3 triệu đơn hàng)  
  [Tải về tại Kaggle](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)

- **Bài toán OR:** Mô hình đa mặt hàng nhiều kỳ (ILP/LP) nhằm **tối thiểu chi phí đặt hàng, lưu kho và thiếu hụt**, đồng thời đảm bảo **ràng buộc mức dịch vụ (Service Level, SL)**.

- **AI/ML:** Dự báo nhu cầu theo sản phẩm × tuần bằng các mô hình **Random Forest / LightGBM**.

- **Kết quả dự kiến:**  
  - Đường cong **chi phí – mức dịch vụ**  
  - So sánh **baseline tồn kho định mức** vs. **forecast-driven**.

---

## Cấu trúc dự án

| Tên file | Mô tả |
|-----------|-------|
| `1_EDA.ipynb` | Phân tích khám phá dữ liệu (Exploratory Data Analysis) |
| `2_Feature_Engineering.ipynb` | Xử lý dữ liệu và tạo đặc trưng |
| `3_Forecasting_Model.ipynb` | Xây dựng mô hình dự báo nhu cầu |
| `4_Optimization_Model.ipynb` | Xây dựng mô hình tối ưu hóa tồn kho (OR-Tools) |

---

## Yêu cầu

- **Python 3.8+**
- **Các thư viện chính:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `lightgbm`
  - `ortools` hoặc `pyscipopt` (tùy solver bạn chọn)

---

## Cài đặt

1. **Clone repository:**
```bash
git clone https://github.com/BinhThanh313/OR_AI.git
cd OR_AI
