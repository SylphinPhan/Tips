# Tips
# 💵 Phân Tích Tiền Tip Tại Nhà Hàng

## 📌 Giới thiệu

Dự án này sử dụng bộ dữ liệu `tips.csv` để khám phá hành vi chi trả tiền **tip** tại một nhà hàng ở Mỹ. Phân tích tập trung vào việc tìm hiểu các yếu tố ảnh hưởng đến số tiền tip mà khách hàng để lại như: giới tính, thời gian, ngày trong tuần, số người đi cùng, v.v.

Phân tích được thực hiện bằng Python trong môi trường Jupyter/Colab.

---

## 📁 Dữ liệu sử dụng

- **Nguồn**: [https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv](https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv)
- **Mô tả**:
  | Cột        | Ý nghĩa                         |
  |------------|----------------------------------|
  | `total_bill` | Tổng hóa đơn (USD)             |
  | `tip`         | Tiền tip (USD)                 |
  | `sex`         | Giới tính của người trả tiền   |
  | `smoker`      | Có hút thuốc hay không         |
  | `day`         | Ngày trong tuần                |
  | `time`        | Bữa ăn (Lunch/Dinner)          |
  | `size`        | Số người trong nhóm            |

---

## 🎯 Mục tiêu dự án

- Khám phá mối liên hệ giữa tổng hóa đơn và tiền tip
- So sánh mức độ tip giữa nam và nữ, người hút thuốc và không hút
- Phân tích xu hướng tip theo ngày trong tuần và thời gian trong ngày
- Trực quan hóa các mối tương quan quan trọng bằng biểu đồ

---

## 📈 Kết quả nổi bật

- Có xu hướng tăng tiền tip khi tổng hóa đơn cao
- Khách hàng đi theo nhóm đông thường tip nhiều hơn
- Sự khác biệt rõ rệt về tip giữa các ngày trong tuần và buổi ăn

---

## 🚀 Cách sử dụng

1. Tải repo về:
   ```bash
   git clone https://github.com/yourusername/tips-data-analysis.git
