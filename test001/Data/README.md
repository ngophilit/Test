## Thông Tin Tập Dữ Liệu

+ Cách thu thập dữ liệu: Dữ liệu được ghi lại trong trong quá trình đi vay của khách hàng và được gán nhãn là đạt chuẩn và không đạt chuẩn cho vay.
+ Muc đích: Tự động hóa phân loại các trường hợp đủ điều kiện cho vay (thời gian thực) dựa trên chi tiết khách hàng được cung cấp trong khi điền vào mẫu đơn đăng ký trực tuyến.
+ Data source [https://www.kaggle.com/datasets/vikasukani/loan-eligible-dataset](https://www.kaggle.com/datasets/vikasukani/loan-eligible-dataset) 
+ Tập dữ liệu phân tích có **12 thuộc tính** gồm 2 file csv (tập train và test)
  + Train gồm **615 quan sát**
  + Test gồm **369 quan sát**
+ Thông tin thuộc tính:

|Thuộc Tính|Mô Tả|Biến|
|:-|:-:|:-:|
|Loan_ID|ID khoản vay |Phân loại|
|Gender|Giới tính (male/female) |Phân loại|
|Married|Tình trạng kết hôn (Y/N) |Phân loại|
|Dependents|Số người là thân nhân/bảo hộ |Rời rạc|
|Education|Trình độ giáo dục (Graduate/ Under Graduate) |Rời rạc|
|Self_Employed|Tự làm chủ (Y/N) |Phân loại|
|ApplicantIncome|Thu nhập ứng viên |Liên tục|
|CoapplicantIncome|Coapplicant income thu nhập đồng ứng viên |Liên tục|
|LoanAmount|Số tiền vay (đơn vị nghìn)|Liên tục|
|Loan_Amount_Term|Thời hạn của 1 khoản vay trong tháng|Liên tục|
|Credit_History|Lịch sử tín dụng đáp ứng các nguyên tắc |Phân loại|
|Property_Area|Khu vực (Urban/ Semi-Urban/ Rural) |Phân loại|
|Loan_Status|Khoản vay được chấp thuật (Y/N) |Phân loại|
