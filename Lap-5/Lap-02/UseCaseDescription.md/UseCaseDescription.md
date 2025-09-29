# Use Case Description – Hệ thống Quản lý Video Online

## Use Case 1: Đăng nhập

- **Mục tiêu**:  
  Người dùng có thể truy cập vào hệ thống bằng tài khoản hợp lệ.

- **Actor**:  
  Người dùng.

- **Điều kiện trước (Pre-condition)**:  
  - Người dùng đã có tài khoản trong hệ thống.  

- **Điều kiện sau (Post-condition)**:  
  - Người dùng đăng nhập thành công và truy cập được các chức năng của hệ thống.  

- **Luồng sự kiện chính (Main flow)**:  
  1. Người dùng mở màn hình đăng nhập.  
  2. Người dùng nhập tên đăng nhập và mật khẩu.  
  3. Hệ thống kiểm tra thông tin đăng nhập.  
  4. Nếu hợp lệ, hệ thống cho phép truy cập.  

- **Luồng phụ/ngoại lệ (Alternative flow)**:  
  - Nếu thông tin đăng nhập sai, hệ thống báo lỗi và yêu cầu nhập lại.  
  - Nếu nhập sai nhiều lần, hệ thống có thể khóa tạm thời tài khoản.  

---

## Use Case 2: Xem video

- **Mục tiêu**:  
  Người dùng có thể xem video trực tuyến từ hệ thống.

- **Actor**:  
  Người dùng.

- **Điều kiện trước (Pre-condition)**:  
  - Người dùng đã đăng nhập.  
  - Video tồn tại trong hệ thống.  

- **Điều kiện sau (Post-condition)**:  
  - Video được phát thành công cho người dùng.  

- **Luồng sự kiện chính (Main flow)**:  
  1. Người dùng chọn video từ danh sách.  
  2. Hệ thống tải thông tin video.  
  3. Hệ thống phát video cho người dùng.  

- **Luồng phụ/ngoại lệ (Alternative flow)**:  
  - Nếu video không tồn tại, hệ thống báo lỗi “Video không khả dụng”.  
  - Nếu mạng yếu, hệ thống cho phép người dùng chọn chất lượng phát thấp hơn.  
