# TEST SCENARIO SUMMARY 

| ID Scenario | Tính năng | Tên Kịch bản | Mô tả |
| :--- | :--- | :--- | :--- |
| **TSC_LOGIN_001** | Đăng nhập | Xác minh Đăng nhập thành công. | Đảm bảo người dùng có thể truy cập News Feed bằng thông tin hợp lệ. |
| **TSC_LOGIN_002** | Đăng nhập | Xác minh Đăng nhập thất bại với dữ liệu không hợp lệ. | Kiểm tra các trường hợp nhập sai Email, Mật khẩu hoặc để trống. |
| **TSC_LOGIN_003** | Đăng nhập | Xác minh chức năng "Quên mật khẩu". | Đảm bảo luồng khôi phục tài khoản hoạt động. |
| **TSC_SIGNUP_001** | Đăng ký | Xác minh Đăng ký tài khoản mới thành công. | Đảm bảo người dùng hoàn tất quá trình đăng ký. |
| **TSC_SIGNUP_002** | Đăng ký | Xác minh Đăng ký thất bại với dữ liệu ngoài phạm vi. | Kiểm tra các quy tắc validation cho độ dài Mật khẩu, định dạng Email, v.v. |
| **TSC_POST_001** | Đăng bài viết | Xác minh Đăng bài viết (text) thành công. | Kiểm tra khả năng đăng nội dung văn bản thuần túy. |
| **TSC_POST_002** | Đăng bài viết | Xác minh Đăng bài viết kèm Media (Ảnh/Video). | Kiểm tra việc upload và hiển thị đa phương tiện. |
| **TSC_POST_003** | Đăng bài viết | Xác minh Giới hạn quyền riêng tư. | Đảm bảo bài viết hiển thị đúng theo thiết lập: Public/Friends/Only Me. |