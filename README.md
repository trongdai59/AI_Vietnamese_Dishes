# AI_Vietnamese_Dishes
Dự án này sử dụng mạng nơ-ron tích chập (CNN) được xây dựng từ đầu (scratch) để phân loại các món ăn khác nhau thông qua hình ảnh. Mô hình được tối ưu hóa để nhận diện chính xác các đặc trưng về thành phần, hình dáng bên ngoài của các món ăn.
# Tải Xuống Mô Hình Pre-trained
Do giới hạn dung lượng file trên GitHub, file trọng số mô hình .h5 được lưu trữ tại Google Drive. Bạn có thể tải về để sử dụng ngay mà không cần huấn luyện lại:
👉 https://drive.google.com/file/d/1zWwj3Co4kCQkkRAxk4nhAsPlmwxvpFjv/view?usp=sharing
# 📂 Cấu Trúc Thư Mục Dự Án
* AI_Vietnamese_Dishes.ipynb: File Google Colab chứa toàn bộ mã nguồn từ xử lý dữ liệu đến huấn luyện.
* test: Thư mục chứa các hình ảnh món ăn thực tế dùng để kiểm thử (Test).
* README.md: Hướng dẫn và thông tin dự án.
#  🛠️ Cách Chạy Mô Hình
Bạn có thể nạp lại mô hình trong môi trường Python/Colab bằng lệnh sau:
```python
from tensorflow.keras.models import load_model
# Load model từ file đã tải về
model = load_model('flowers_recognition.h5')
# Dự đoán ảnh mới
# predictions = model.predict(img_prepared)
print("Mô hình nhận diện hoa đã sẵn sàng!")
