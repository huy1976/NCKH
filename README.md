# Thuật toán train mô hình AI 1D-CNN + Autoencoder

Kho lưu trữ này chứa mã nguồn triển khai mô hình học sâu kết hợp giữa **1D-CNN Autoencoder** và **Classifier** để phân loại và xử lý tín hiệu.

## 📂 Dữ liệu (Dataset)
Bộ dữ liệu Dataset về dòng điện stato được sử dụng làm nguồn dữ liệu đầu vào chính cho bài toán chẩn đoán lỗi vòng bi của động cơ không đồng bộ ba pha.
👉 **[(https://data.mendeley.com/datasets/j8d8pfkvj2/4)]**

## 📊 Kết quả huấn luyện (Training Results)
EDA - Exploratory Data Analysis
<p align="center">
  <br>
  <b>1. Ma trận tương quan Pearson giữa ba pha dòng điện trên toàn bộ tập dữ liệu:</b><br>
  <img src="https://github.com/user-attachments/assets/fcf5c3da-620f-4349-875f-fd1eac9553a7" alt="Kết quả train 1" width="600" />
  
  <br><br>
  <b>2. So sánh ma trận tương quan giữa ba pha dòng điện theo từng trạng thái dữ liệu:</b><br>
  <img src="https://github.com/user-attachments/assets/31d596ca-f26c-458f-84dc-313dd4806ab7" alt="Kết quả train 2" width="500" />
  
  <br><br>
  <b>3. Không gian quỹ đạo 3D của dòng điện 3 pha (5.000 mẫu cho mỗi trạng thái):</b><br>
  <img src="https://github.com/user-attachments/assets/608b9633-eb70-4408-9759-f395522c541b" alt="Kết quả train 3" width="400" />
</p>

Kết quả Test:
Class
Precision 1D-CNN
Recall
1D-CNN
F1
1D-CNN
Precision
Hybrid
Recall
Hybrid
F1
Hybird
Ball
0.6646
0.7472
0.7035
0.7218
0.7788
0.7492
Inner
0.9966
0.9996
0.9981
1.0000
0.9991
0.9996
Normal
0.6681
0.6513
0.6596
0.7234
0.7401
0.7316
Outer
0.8146
0.7314
0.7708
0.9012
0.8100
0.8532
Accuracy
0.7824
—
—
0.8320
—
—
Marco F1
0.7830
—
—
0.8334
—
—


