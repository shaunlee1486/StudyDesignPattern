﻿## Tóm tắt
- Observer Pattern xác định mối quan hệ một-nhiều giữa các đối tượng.
- Subjects, hoặc tên gọi khác như chúng ta cũng biết, Observable, cập nhật những Observer bằng interface chung.
- Observer Pattern đạt được “khớp nối lỏng lẽo” trong đó Observable không biết gì về người quan sát (observer) , ngoài việc biết chúng implement interface Observer.
- Bạn có thể push (đẩy) hoặc kéo (pull) dữ liệu từ Observable được khi sử dụng mẫu Observer Pattern (kéo(pull) được coi là chính xác hơn).
- Không phụ thuộc vào một thứ tự thông báo cụ thể cho những Observer của bạn.
- Java có một số triển khai Observer Pattern, chứa bên trong java.util.Observable.
- Xem qua các vấn đề khi triển khai java.util.Observable.
- Đừng sợ tạo ra Observable của riêng bạn nếu cần.
- Swing sử dụng rất nhiều Observer Pattern, cũng như nhiều GUI framework.
- Bạn cũng tìm thấy mẫu này ở nhiều nơi khác, bao gồm JavaBeans và RMI.