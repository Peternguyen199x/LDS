Bank Additional
Posted Yesterday
Cho dữ liệu bank marketing data (tập tin bank-additional-full.csv) (UCI's Bank Marketing Data Set: link: https://archive.ics.uci.edu/ml/datasets/bank+marketing)
Dữ liệu có liên quan đến các chiến dịch tiếp thị trực tiếp (các cuộc gọi điện thoại) của một tổchức ngân hàng Bồ Đào Nha. Mục tiêu phân loại là để dự đoán liệu khách hàng sẽ đăng kýmột khoản tiền gửi có kỳ hạn hay không (y).

Yêu cầu:

Phần 1: Thực hiện các công việc sau:
Xác định các thuộc tính
Phân tích đơn biến
Để dự đoán một khách hàng sẽ đăng ký (subscribe =yes/no) cho một khoản tiền gửi cókỳ hạn (term deposit - variable y) hay không chúng ta cần các thông tin trong dữ liệu, hãychọn một số thuộc tính và phân tích.
Phân tích hai biến
Xử lý dữ liệu thiếu
Phát hiện và xử lý ngoại lệ

Phần 2: Tính toán và trực quan hóa KPI, chủ yếu tập trung vào phântích conversion rates
1. Tạo cột conversion: dựa trên cột y với giá trị 'yes' => 1 và 'no' => 0
2. Tính toán tổng conversion và conversion rate
3. Tính toán conversion rate theo từng age. Trực quan hóa kết quả.
4. Tính toán conversion rate theo từng nhóm age (nhóm 18-30, nhóm 30-40, nhóm 40 - 50,nhóm 50-60, nhóm 60-70, nhóm >70. Trực quan hóa kết quả.
5. So sánh giữa conversion và non-conversion cho từng nhóm marital status. Trực quan hóa kếtquả.
6. So sánh giữa conversion và non-conversion cho từng nhóm Age Groups & Marital Status.Trực quan hóa kết quả.