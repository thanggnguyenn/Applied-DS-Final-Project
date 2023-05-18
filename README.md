# Đồ án cuối kỳ môn Khoa học dữ liệu ứng dụng

## 1. Thông tin thành viên

|MSSV|Họ tên|
|---|---|
|19120207|Hồ Hoàng Duy|
|19120364|Nguyễn Đắc Thắng|
|19120651|Nguyễn Phạm Hoàng Thái|

## 2. Thông tin về đồ án

Trong đồ án này nhóm thực hiện đề tài dự đoán liệu rằng một khách hàng có ngưng sử dụng dịch vụ thẻ tín dụng hay không dựa vào các thông tin cá nhân của khách hàng cũng như thông tin về hoạt động của khách hàng với thẻ tín dụng. Từ đó, nhóm phân tích dữ liệu, tìm ra các đặc trưng quan trọng để đưa vào mô hình phân lớp khách hàng nào sẽ không sử dụng thẻ.

## 3. Hướng dẫn cách chạy code trong giai đoạn 3

Nhóm thực hiện theo từng file như sau:

- Preprocess_data_Feature_selection.ipynb: trong file này nhóm sẽ tiền xử lý cơ bản để có thể đưa vào mô hình dự đoán các giá trị quan trọng góp phần vào độ chính xác của dự đoán.
- Feature_Extraction.ipynb: dựa vào thuật toán SHAP để chọn ra các đặc trưng cho mô hình sau này.
- DataMining.ipynb: sau khi đã chọn ra các thuộc tính đặc trưng, nhóm chọn ra các mô hình là RandomForest, XGBoost, CatBoost, LightGBM để huấn luyện dữ liệu.
- Experiment.ipynb: nhóm đã tạo ra một tập dữ liệu giả (synthetic data) trên 1 triệu dòng để chạy các mô hình trên và kiểm tra kết quả. Để chạy được file này, truy cập vào [đây](https://drive.google.com/file/d/1Mh9KMNf-f4a3WsP48rcFv_OS2ZX-FPVc/view?fbclid=IwAR1WfRfPt6RtBKr7Z_T5vu6eAe43TXwkPXwneSJp14xNYcjPINpWZyju9tM) và tải về máy, sau đó sử dụng dữ liệu này để làm đầu vào cho phần thực nghiệm.
