# **Tài liệu ChatBot**
##### Tạo một chatbot 
SE-Lab-Day7

GOALS:

Phần mềm quản lí khách sạn
Phần mềm dạng ứng dụng cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng, quản lí khách sạn được sử dụng
Quản lí thông tin phòng và khách sạn
Tạo và xem các loại báo cáo
Đặt chỗ/ Hủy đặt chỗ phòng
Checkin/Checkout và thanh toán cho khách hàng
BUSINESS OBJECTIVES

Quản lí thông tin phòng và khách sạn
Tìm phòng trống và đặt phòng theo yêu cầu của khách
Thêm/sửa/xóa thông tin phòng
Thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả (bao gồm mô tả bằng text và bằng hình ảnh).
Trong khách sạn có nhiều phòng, mỗi phòng được mô tả bằng các thông tin: tên phòng (duy nhất, để phân biệt các phòng), loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.
Tạo và xem các loại báo cáo
Xem các báo cáo doanh thu theo thời gian/theo phòng/theo loại phòng
Xem báo cáo tỉ lệ phòng trống theo thời gian/theo phòng/theo loại phòng
Xem báo cáo khách hàng đặt nhiều theo thời gian/theo nguồn gốc khách hàng
Đặt chỗ/ Hủy đặt chỗ phòng
Mỗi khách hàng, khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND (số passport nếu là người nước ngoài), loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...
Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.
Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.
Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo
Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.
Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.
Checkin/Checkout và thanh toán cho khách hàng
Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm (mỗi dịch vụ bao gồm tên dịch vụ, đơn vị tính, đơn giá, tổng tiền), số tiền thanh toán.
Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.
