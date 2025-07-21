## Actor:
- **Owner** (Chủ tổ chức / workspace)

---

## Use Cases:

### Organization Management
- **UC-OWNER-01:** Tạo tổ chức mới  
  - Actor: Owner  
  - Description: Tạo mới một tổ chức để quản lý người dùng và dự án.

- **UC-OWNER-02:** Chỉnh sửa thông tin tổ chức  
  - Actor: Owner  
  - Description: Cập nhật tên, mô tả, logo của tổ chức.

- **UC-OWNER-03:** Xem danh sách thành viên tổ chức  
  - Actor: Owner  
  - Description: Xem toàn bộ người dùng đang thuộc tổ chức của mình.

- **UC-OWNER-04:** Mời người dùng vào tổ chức  
  - Actor: Owner  
  - Description: Gửi lời mời người dùng tham gia tổ chức qua email hoặc chọn người đã có tài khoản.

- **UC-OWNER-05:** Gỡ người dùng khỏi tổ chức  
  - Actor: Owner  
  - Description: Xóa người dùng khỏi tổ chức khi không còn hoạt động.

### Project Management (Tổ chức cấp)
- **UC-OWNER-06:** Tạo dự án mới trong tổ chức  
  - Actor: Owner  
  - Description: Tạo mới một dự án và gán cho Project Manager phụ trách.

- **UC-OWNER-07:** Xem danh sách dự án trong tổ chức  
  - Actor: Owner  
  - Description: Xem toàn bộ dự án do tổ chức tạo ra, kể cả khi không phải PM trực tiếp.

- **UC-OWNER-08:** Gán hoặc chuyển PM cho dự án  
  - Actor: Owner  
  - Description: Chỉ định hoặc thay đổi Project Manager của một dự án.

- **UC-OWNER-09:** Lưu trữ hoặc xoá dự án  
  - Actor: Owner  
  - Description: Ẩn dự án không còn hoạt động hoặc xoá vĩnh viễn nếu cần.

### Member Role Management
- **UC-OWNER-10:** Phân quyền cho thành viên  
  - Actor: Owner  
  - Description: Gán vai trò PM, Leader hoặc Member cho người dùng trong tổ chức.

- **UC-OWNER-11:** Chuyển thành viên giữa các dự án  
  - Actor: Owner  
  - Description: Di chuyển hoặc gán lại người dùng từ dự án này sang dự án khác.

### Analytics & Reporting
- **UC-OWNER-12:** Xem tổng quan tiến độ tổ chức  
  - Actor: Owner  
  - Description: Xem báo cáo tiến độ, hiệu suất tổng hợp của các dự án trong tổ chức.

- **UC-OWNER-13:** Thống kê theo từng PM / dự án  
  - Actor: Owner  
  - Description: Xem chi tiết hiệu suất từng dự án hoặc Project Manager cụ thể.

---

## Summary Table

| Use Case ID     | Name                              | Description                                                       |
|-----------------|-----------------------------------|-------------------------------------------------------------------|
| UC-OWNER-01     | Tạo tổ chức mới                   | Tạo mới một tổ chức để quản lý người dùng và dự án               |
| UC-OWNER-02     | Chỉnh sửa thông tin tổ chức       | Cập nhật tên, mô tả, logo của tổ chức                             |
| UC-OWNER-03     | Xem thành viên tổ chức            | Xem toàn bộ người dùng trong tổ chức                              |
| UC-OWNER-04     | Mời người dùng vào tổ chức        | Gửi lời mời người dùng tham gia tổ chức                           |
| UC-OWNER-05     | Gỡ người dùng khỏi tổ chức        | Xóa người dùng khỏi tổ chức                                       |
| UC-OWNER-06     | Tạo dự án mới                     | Tạo mới dự án thuộc tổ chức và gán PM                             |
| UC-OWNER-07     | Xem danh sách dự án               | Xem toàn bộ dự án thuộc tổ chức                                   |
| UC-OWNER-08     | Gán / chuyển PM cho dự án         | Chỉ định hoặc thay đổi PM của một dự án                           |
| UC-OWNER-09     | Lưu trữ hoặc xoá dự án            | Ẩn hoặc xoá dự án khỏi tổ chức                                    |
| UC-OWNER-10     | Phân quyền cho thành viên         | Gán vai trò PM, Leader, Member cho người dùng trong tổ chức      |
| UC-OWNER-11     | Chuyển thành viên giữa dự án      | Di chuyển hoặc gán lại người dùng giữa các dự án                  |
| UC-OWNER-12     | Xem tiến độ tổng quan tổ chức     | Xem báo cáo tổng quan hiệu suất của toàn tổ chức                  |
| UC-OWNER-13     | Thống kê theo PM / dự án          | Xem chi tiết hiệu suất từng PM hoặc từng dự án                   |
