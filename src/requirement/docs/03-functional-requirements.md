# 03 - Functional Requirements

## Public Web (Người dùng chưa đăng nhập)

### 1. Trang chủ
- Giới thiệu tổng quan hệ thống
- Hiển thị lợi ích, tính năng nổi bật
- CTA: Đăng ký / Đăng nhập

### 2. Đăng ký tài khoản
- Nhập: Họ tên, email, mật khẩu
- Xác thực email qua mã OTP

### 3. Đăng nhập / Quên mật khẩu
- Đăng nhập bằng email + mật khẩu
- Lấy lại mật khẩu bằng OTP gửi qua email

---

##  Private Web (Người dùng đã đăng nhập)

### A. Admin
- Quản lý người dùng (xem, phân quyền, khoá)
- Cấu hình hệ thống, SMTP, sao lưu dữ liệu
- Xem thống kê và nhật ký hoạt động

### B. Project Manager
- Quản lý dự án (tạo, sửa, xoá, mời thành viên)
- Giao task, phân quyền, đặt deadline
- Theo dõi tiến độ: To do – Doing – Done
- Quản lý tài nguyên: tệp, bình luận, nhắc việc
- Báo cáo tiến độ theo thời gian

### C. Member
- Xem và cập nhật task được giao
- Bình luận, trao đổi trong từng task
- Quản lý file đính kèm
- Chấm công, check-in/out

---

##  Tính năng mở rộng
- Thông báo theo thời gian thực
- Tích hợp lịch: Google Calendar / Outlook
- Giao diện Dashboard trực quan
