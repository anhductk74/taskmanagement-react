# 03 – Functional Requirements (Chức năng hệ thống)

## Public Web (Người dùng chưa đăng nhập)

### 1. Trang chủ
- Giới thiệu tổng quan về nền tảng quản lý công việc và dự án.
- Hiển thị các tính năng nổi bật, lợi ích khi sử dụng.
- CTA (Call to Action): Đăng ký / Đăng nhập.

### 2. Đăng ký tài khoản
- Nhập họ tên, email, mật khẩu.
- Sau đăng ký, tài khoản được gán role mặc định (Tài khoản có thể mua gói tạo workspace).

### 3. Đăng nhập / Quên mật khẩu
- Đăng nhập bằng email và mật khẩu.
- Quên mật khẩu: Gửi OTP đến email để đặt lại.

---

## Private Web (Người dùng đã đăng nhập)

###  1. Admin (Quản trị hệ thống)
#### Quản lý toàn bộ hệ thống:
- Danh sách người dùng (xem, tìm kiếm, chỉnh sửa, khóa).
- Gán role: Owner / PM / Leader / Member.
- Quản lý tổ chức: phê duyệt, xóa, vô hiệu hóa tổ chức.

#### Theo dõi hệ thống:
- Nhật ký hoạt động (audit logs), thống kê hệ thống.
- Theo dõi sử dụng tài nguyên, báo cáo tổng quan.

#### Cấu hình hệ thống:
- SMTP, backup dữ liệu, cấu hình chung.

#### Quản lý gói cước (nếu có):
- Tạo, chỉnh sửa gói, cấp gói cho từng tổ chức.

---

###  2. Owner (Chủ tổ chức / workspace)
#### Quản lý tổ chức:
- Cập nhật tên, logo, thông tin tổ chức.
- Mời / xoá / phân quyền người dùng trong tổ chức.


#### Quản lý dự án:
- Tạo, chỉnh sửa, xóa dự án thuộc tổ chức.
- Gán Project Manager cho từng dự án.

#### Giám sát:
- Theo dõi tổng quan tiến độ các dự án.
- Xem hiệu suất làm việc theo user / team.

#### Quản lý tài khoản trong tổ chức:
- Phân quyền PM, Leader, Member.
- Cung cấp tài khoản theo từng role PM, Leader, Member theo đuôi gmail của công ty

---

###  3. Project Manager (Quản lý dự án)
#### Quản lý dự án được giao:
- Tạo task, phân công công việc, đặt deadline.
- Chỉnh sửa thông tin dự án, milestone, calendar.

#### Quản lý thành viên dự án:
- Mời thành viên đã có trong tổ chức vào dự án.
- Phân quyền Leader / Member.

#### Giám sát tiến độ:
- Theo dõi trạng thái công việc (To do – Doing – Done).
- Gửi báo cáo tiến độ cho Owner theo thời gian.

#### Quản lý dữ liệu:
- Upload tài liệu, bình luận, nhắc việc.

---

###  4. Leader (Trưởng nhóm)
#### Quản lý nhóm phụ trách (ví dụ: frontend, backend...):
- Tạo và giao task cho các thành viên trong nhóm của mình.
- Cập nhật trạng thái, theo dõi tiến độ nhóm phụ trách.

#### Tương tác nhóm:
- Bình luận, thảo luận trong task.
- Đính kèm tài liệu, tham gia lịch họp.

#### Không được:
- Mời thành viên mới vào dự án.
- Sửa milestone hoặc cấu trúc dự án.

---

###  5. Member (Thành viên)
#### Công việc cá nhân:
- Xem và cập nhật task được giao.
- Cập nhật trạng thái task: To do, Doing, Done.

#### Tương tác nhóm:
- Bình luận trong task, đính kèm file, tag đồng nghiệp.


#### Tham gia lịch trình:
- Xem và tham gia lịch họp, sự kiện milestone.

---

## Tính năng nâng cao (Dùng chung)

### Thông báo thời gian thực:
- Nhắc việc, cập nhật task, lịch họp qua toast / email / thông báo trên app.

### Tích hợp lịch ngoài:
- Google Calendar, Outlook để đồng bộ lịch họp / milestone.

###  Dashboard trực quan:
- Hiển thị tiến độ, năng suất, số lượng task theo ngày / tuần / tháng tùy theo vai trò.
