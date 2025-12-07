# 🐞 BUG REPORT MẪU

| Field | Thông tin Chi tiết |
| :--- | :--- |
| **Mã Lỗi** | BUG_LOGIN_001 |
| **Tóm tắt** | **[Login] Incorrect validation message when user enters 4-character password.** (Thông báo validation sai khi nhập mật khẩu 4 ký tự.) |
| **Mức độ Nghiêm trọng** | **Major** |
| **Mức độ Ưu tiên** | **High** |
| **Người được Giao** | Chờ phân công |

## CHI TIẾT LỖI

**1. Các Bước Tái hiện:**
1. Truy cập trang Đăng nhập Facebook.
2. Nhập email hợp lệ vào trường Email.
3. Nhập mật khẩu **4 ký tự** (ví dụ: `1234`) vào trường Mật khẩu.
4. Nhấn nút "Đăng nhập".

**2. Kết quả Thực tế:**
Hệ thống hiển thị thông báo lỗi chung: "Địa chỉ email hoặc số di động bạn nhập không được kết nối với tài khoản."

**3. Kết quả Mong đợi**
Hệ thống phải hiển thị thông báo lỗi cụ thể về validation: "Mật khẩu quá ngắn. Vui lòng sử dụng ít nhất 6 ký tự."

**4. Môi trường:**
* **Trình duyệt:** Chrome 126.0 (Latest)
* **Hệ điều hành:** Windows 11
* **Thiết bị:** Desktop