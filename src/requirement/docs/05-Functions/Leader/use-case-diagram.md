# Use Case Diagram - Leader

## Actor:
- **Leader**

---

## Use Cases:

### Team Management
- **UC-LEADER-01:** Xem danh sách thành viên nhóm
  - Actor: Leader
  - Description: Leader xem thông tin các thành viên trong nhóm mình phụ trách.
- **UC-LEADER-02:** Đánh giá hiệu suất thành viên
  - Actor: Leader
  - Description: Leader đánh giá KPIs và hiệu suất làm việc của thành viên.
- **UC-LEADER-03:** Tổ chức họp nhóm
  - Actor: Leader
  - Description: Leader lên lịch và quản lý các cuộc họp nhóm.

### Task Management
- **UC-LEADER-04:** Giao task cho member
  - Actor: Leader
  - Description: Leader giao task với tiêu đề, mô tả, deadline, độ ưu tiên.
- **UC-LEADER-05:** Theo dõi tiến độ task
  - Actor: Leader
  - Description: Leader theo dõi trạng thái, tiến độ các task của nhóm.
- **UC-LEADER-06:** Phê duyệt task hoàn thành
  - Actor: Leader
  - Description: Leader xem xét và phê duyệt các task đã hoàn thành.
- **UC-LEADER-07:** Quản lý workload
  - Actor: Leader
  - Description: Leader cân đối khối lượng công việc giữa các thành viên.

### Quality Control
- **UC-LEADER-08:** Code Review
  - Actor: Leader
  - Description: Leader review code của thành viên trong nhóm.
- **UC-LEADER-09:** Thiết lập tiêu chuẩn chất lượng
  - Actor: Leader
  - Description: Leader định nghĩa các tiêu chuẩn chất lượng cho nhóm.

### Reporting & Analytics
- **UC-LEADER-10:** Tạo báo cáo tiến độ
  - Actor: Leader
  - Description: Leader tạo báo cáo về tiến độ công việc của nhóm.
- **UC-LEADER-11:** Phân tích hiệu suất nhóm
  - Actor: Leader
  - Description: Leader xem các metrics về hiệu suất làm việc của nhóm.

### Communication
- **UC-LEADER-12:** Gửi thông báo nhóm
  - Actor: Leader
  - Description: Leader gửi thông báo đến các thành viên trong nhóm.
- **UC-LEADER-13:** Chat nhóm
  - Actor: Leader
  - Description: Leader tham gia và quản lý kênh chat của nhóm.

---

## Summary Table

| Use Case ID     | Name                              | Description                                         |
|-----------------|-----------------------------------|-----------------------------------------------------|
| UC-LEADER-01    | Xem thành viên nhóm               | Xem danh sách thành viên trong nhóm                 |
| UC-LEADER-02    | Đánh giá hiệu suất thành viên     | Đánh giá KPIs và hiệu suất làm việc của thành viên |
| UC-LEADER-03    | Tổ chức họp nhóm                  | Lên lịch và quản lý các cuộc họp nhóm              |
| UC-LEADER-04    | Giao task cho member              | Giao task với tiêu đề, mô tả, deadline, độ ưu tiên |
| UC-LEADER-05    | Theo dõi tiến độ task            | Theo dõi trạng thái, tiến độ các task của nhóm      |
| UC-LEADER-06    | Phê duyệt task hoàn thành        | Xem xét và phê duyệt các task đã hoàn thành        |
| UC-LEADER-07    | Quản lý workload                  | Cân đối khối lượng công việc giữa các thành viên   |
| UC-LEADER-08    | Code Review                       | Review code của thành viên trong nhóm               |
| UC-LEADER-09    | Thiết lập tiêu chuẩn chất lượng   | Định nghĩa các tiêu chuẩn chất lượng cho nhóm       |
| UC-LEADER-10    | Tạo báo cáo tiến độ              | Tạo báo cáo về tiến độ công việc của nhóm          |
| UC-LEADER-11    | Phân tích hiệu suất nhóm         | Xem các metrics về hiệu suất làm việc của nhóm     |
| UC-LEADER-12    | Gửi thông báo nhóm               | Gửi thông báo đến các thành viên trong nhóm        |
| UC-LEADER-13    | Chat nhóm                         | Tham gia và quản lý kênh chat của nhóm             |