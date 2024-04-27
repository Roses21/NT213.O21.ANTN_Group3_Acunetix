## ❤️ Acunetix là gì?
- Acunetix Web Vulnerbility Scanner là một công cụ kiểm tra bảo mật ứng dụng web tự động kiểm tra các ứng dụng web để tìm kiếm lỗ hổng bảo mật như SQL Injection, hay Cross-Site Scripting (XSS),...
- Mục tiêu là một trang web, ứng dụng web, máy chủ hoặc thiết bị mạng mà bạn muốn quét để tìm lỗ hổng bảo mật.
- Acunetix là một trình quét bảo mật trang Web tất cả trong một, Acunetix cung cấp một công cụ tự động quét các ứng dụng Web để xác định và giải quyết những vấn đề bảo mật.
- Acunetix có một bộ kỹ thuật phát hiện lỗ hổng Website hàng đầu hiện nay cùng với Acunetix AcuSensor giúp thực hiện các cuộc tấn công tự động và hiển thị các lỗ hổng được phát hiện. Đó cũng là một công nghệ bảo mật có thể tìm thấy lỗ hổng nhanh với số lượng cảnh báo giả thấp. Điều này cũng cho thấy, lỗ hổng trong mã nguồn và báo cáo thông tin gỡ lỗi hiệu quả, đồng thời xác định được các lỗ hổng Website như: File inclusion, CRLF, Code execution, Directory Traversal, lỗ hổng khi xác thực...
![image](https://github.com/Roses21/NT213.O21.ANTN_Group3_Acunetix/assets/147015288/bc92c149-373e-40ba-b814-5e6ec3c27917)

## ❤️ Các chức năng chính của Acunetix
- Phát hiện lỗ hổng bảo mật: Acunetix quét các ứng dụng web để phát hiện các lỗ hổng bảo mật phổ biến như SQL injection, cross-site scripting (XSS), cross-site request forgery (CSRF), và nhiều lỗ hổng khác theo OWASP Top 10 và các tiêu chuẩn bảo mật khác.
- Quét tự động: Acunetix cung cấp khả năng quét tự động để phát hiện lỗ hổng bảo mật trong các ứng dụng web, giúp tiết kiệm thời gian và công sức cho các nhà phát triển và nhà quản trị hệ thống.
- Phân tích kết quả quét: Acunetix cung cấp báo cáo chi tiết về các lỗ hổng bảo mật được phát hiện, bao gồm cấp độ nghiêm trọng, các bước để khắc phục, và các thông tin liên quan. Điều này giúp các nhà phát triển và nhà quản trị hệ thống hiểu rõ về các vấn đề bảo mật và áp dụng biện pháp sửa chữa.
- Kiểm tra tích hợp: Acunetix có thể tích hợp với các công cụ quản lý dự án và hệ thống theo dõi lỗi như Jira, GitHub, và các công cụ khác, giúp các nhóm làm việc cùng nhau quản lý và giải quyết các vấn đề bảo mật một cách hiệu quả.
- Quét bảo mật mạng: giúp người dùng phát hiện ra các cổng đang mở và những dịch vụ đang chạy, đồng thời kiểm tra hơn 50.000 lỗ hổng mạng và cấu hình sai đã biết. Acunetix cũng cho phép người dùng phân tích tính bảo mật của Router, Switch, bộ cân bằng tải và những thứ tương tự. Ngoài ra, thành phần quét bảo mật mạng được trang bị thêm một số khả năng như kiểm tra mật khẩu yếu: FTP, IMAP, Database Server, POP3, Socks, SSH, Telnet; Proxy server được cấu hình không hợp lệ; truy cập FTP ẩn danh và các thư mục có thể ghi qua FTP; mật mã TLS/SSL yếu.
## ❤️ Acunetix hoạt động như thế nào?
## ❤️ Ưu, nhược điểm của Acunetix
### 🌵 Ưu điểm
- Acunetix triển khai một loạt các biện pháp kiểm tra lỗ hổng web đối với từng thành phần trong ứng dụng web.
- Kết quả quét bao gồm chi tiết toàn diện về tất cả các lỗ hổng được tìm thấy trong trang web. Các lỗ hổng được trình bày theo yêu cầu hoặc theo mức độ nghiêm trọng.
- Dễ dàng xem lại kết quả quét của các lần quét đang diễn ra hoặc đã hoàn thành thông qua trang Scans. Có thể lập lịch hoặc quét ngay lập tức.
- Hỗ trợ quét hộp đen và hộp xám.
- Cung cấp nhiều mẫu báo cáo khác nhau.
### 🌵 Nhược điểm
- Chi phí đầu tư: Acunetix là một công cụ tính phí.
- Tồn tại dương tính giả, làm mất thời gian và công sức của nhà phát triển và nhà quản trị hệ thống trong việc kiểm tra và xác minh các kết quả quét.
- Trong quá trình quét rất tốn RAM và bộ nhớ.
- Không có chức năng tạm dừng quét, phải chờ đến khi quét xong.
## ❤️ Tích hợp AcuSensor và AcuMonitor vào Acunetix 
### 🌵 AcuSensor
- Mô tả: AcuSensor là một công nghệ độc đáo cho phép Acunetix phát hiện nhiều lỗ hổng bảo mật hơn so với phương pháp quét hộp đen truyền thống và giảm thiểu các kết quả dương tính giả.
- Chức năng: AcuSensor được thiết kế để chèn các cảm biến vào mã nguồn của ứng dụng web, thu thập thông tin chi tiết về hoạt động của ứng dụng và chỉ ra dòng mã mà lỗ hổng được tìm thấy.
- Tính năng: AcuSensor kết hợp các kỹ thuật quét hộp đen với phân tích mã tương tác trong khi mã nguồn đang được thực thi để tăng độ chính xác của việc phát hiện lỗ hổng bảo mật.
### 🌵 AcuMonitor
- Mô tả: AcuMonitor là một dịch vụ trung gian được tích hợp vào Acunetix để phát hiện các lỗ hổng bảo mật chỉ có thể được xác định thông qua một dịch vụ bên ngoài.
- Chức năng: AcuMonitor cho phép Acunetix phát hiện các lỗ hổng bảo mật mà không cần trực tiếp truy cập vào ứng dụng web đích. Nó có thể báo cáo các lỗ hổng ngay lập tức trong quá trình quét hoặc thông báo qua email sau khi quét kết thúc.
- Tính năng: AcuMonitor là một dịch vụ hoàn toàn tích hợp vào Acunetix và được kích hoạt cho tất cả các mục tiêu được cấu hình trong Acunetix, giúp cải thiện khả năng phát hiện lỗ hổng bảo mật của công cụ.
## ❤️ Nguồn tham khảo
- https://tapchinganhang.gov.vn/kiem-tra-va-phat-hien-lo-hong-bao-mat-website-voi-acunetix.htm
- https://www.acunetix.com/support/docs/wvs/overview/
- https://viblo.asia/p/gioi-thieu-cong-cu-do-quet-lo-hong-acunetix-ORNZqjDbl0n 
