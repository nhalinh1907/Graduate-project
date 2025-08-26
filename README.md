# Graduate-project
Đồ án đã trình bày được các khái niệm, tính chất của bài toán chuỗi thời gian và
cũng như xây dựng được mô hình dự báo chuỗi thời gian cho giá cổ phiếu trong thị
trường chứng khoán và đưa ra những nhận định quan trọng

Cụ thể:

1. Đồ án đã hệ thống hóa các kiến thức nền tảng về chuỗi thời gian và bài toán dự
báo chuỗi thời gian. Quá trình nghiên cứu làm quen các mô hình học sâu, đặc
biệt tập trung vào các mô hình có cấu trúc "mixing-based" mới được công bố
những năm gần đây.

2. Nghiên cứu lý thuyết các mô hình học sâu trong dự báo chuỗi thời gian, tập
trung đặc biệt vào mô hình TimeXer mới được công bố có khả năng khai thác
hiệu quả thông tin từ các biến ngoại sinh. Việc này bao gồm phân tích kiến trúc
của TimeXer, so sánh với mô hình mạng nơ-ron như LSTM và mô hình cùng
cấu trúc "mixing-based" nhưng chưa tích hợp biến ngoại sinh như TimeMixer
và TSMixer.

3. Tìm hiểu và áp dụng các công cụ được tích hợp trong nền tảng SaaS Microsoft
Fabric, nhằm thu thập, lưu trữ, xử lý và phân tích dữ liệu. Xây dựng thành công
data pipeline cập nhật dữ liệu tự động hàng ngày

4. Xây dựng nhiều kịch bản thử nghiệm nhằm phân tích hiệu suất của mô hình từ
các góc độ khác nhau, bao gồm cấu hình mô hình, và việc tích hợp các biến
ngoại sinh. Các thử nghiệm này giải quyết bài toán dự báo chỉ số thị trường
VNindex ngắn hạn và trung hạn, được thiết kế để kiểm tra khả năng tổng quát
hóa và độ nhạy của mô hình trước các thay đổi trong dữ liệu hoặc cấu hình.
5. Đưa ra 5 nhận định ý nghĩa từ các kết quả thực nghiệm. Những nhận định này
có ý nghĩa thực tiễn cao, góp phần định hướng cho việc áp dụng các mô hình
vào dự báo thị trường chứng khoán. Đồng thời, đây cũng là nền tảng quan trọng
để phát triển các nghiên cứu tiếp theo trong cùng lĩnh vực.