# JMeter
# Kiểm tra hiệu năng trang web
# Mục tiêu:
- Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://canvas.phenikaa-uni.edu.vn/
- Chạy kịch bản kiểm tra và ghi lại kết quả.
- Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.
- Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.
# Kịch bản kiểm tra:
- Thread Group:
  - Số lượng thread: 1000
  - Thời gian chạy: 30 giây
  - Ramp-up period: 10 giây
- HTTP Request:
  - URL: https://canvas.phenikaa-uni.edu.vn/
  - Method: GET
  - Content encoding: UTF-8
- Listeners:
  - View Results Tree
  - Aggregate Report
# Kết quả kiểm tra: 
![image](https://github.com/KTThanh167/JMeter/assets/144884139/db3cbc80-6109-46f1-9a60-3e3f02d489fd)
![image](https://github.com/KTThanh167/JMeter/assets/144884139/fdc61870-7c21-4956-b6c8-2b1a18ccfd1f)
# Phân tích kết quả kiểm tra
- Số lượng yêu cầu thành công: 999/1000 = 99,9%
- Số lượng yêu cầu thất bại: 1/1000 = 0,1%
# Kết luận: Trang web https://canvas.phenikaa-uni.edu.vn/ có hiệu năng tốt. Số lượng yêu cầu thành công rất cao (99,9%), số lượng yêu cầu thất bại rất thấp (0,1%).
