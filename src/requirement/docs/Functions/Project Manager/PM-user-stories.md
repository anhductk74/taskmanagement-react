## 🗂️ User Stories – Quản lý Dự án (Project Manager)

---

### User Story #1: Tạo dự án mới

**User Story:**  
As a Project Manager, I want to create a new project,  
So that I can start managing tasks and team members under it.

**Acceptance Criteria:**

- Có form tạo dự án gồm: tên dự án, mô tả, ngày bắt đầu (tùy chọn), deadline (tùy chọn)
- Tên dự án không được để trống
- Nếu thiếu thông tin bắt buộc → hiện lỗi rõ ràng
- Sau khi tạo thành công, dự án xuất hiện trong danh sách quản lý
- Gán mặc định người tạo là Project Manager của dự án đó

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #2: Chỉnh sửa thông tin dự án

**User Story:**  
As a Project Manager, I want to edit project details,  
So that I can update information if anything changes.

**Acceptance Criteria:**

- Có thể chỉnh sửa: tên dự án, mô tả, ngày bắt đầu, deadline
- Không cho phép để trống tên dự án khi cập nhật
- Lưu thay đổi và cập nhật giao diện ngay
- Ghi log hoạt động chỉnh sửa (nếu có chức năng activity log)

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #3: Xóa hoặc lưu trữ dự án

**User Story:**  
As a Project Manager, I want to delete or archive a project,  
So that I can clean up old or completed projects from my dashboard.

**Acceptance Criteria:**

- Có nút lựa chọn “Xóa” và “Lưu trữ” dự án
- Khi nhấn xóa → hiện hộp thoại xác nhận
- Lưu trữ dự án: ẩn khỏi danh sách chính, có thể xem lại ở trang “Dự án đã lưu trữ”
- Không thể xóa dự án nếu không có quyền (chỉ PM hoặc Admin được phép)
- Gửi thông báo xác nhận khi thao tác thành công

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #4: Xem danh sách các dự án đang quản lý

**User Story:**  
As a Project Manager, I want to view all projects I am managing,  
So that I can quickly switch between them and track their progress.

**Acceptance Criteria:**

- Hiển thị danh sách các dự án mà người dùng là PM
- Mỗi dự án hiển thị: tên, mô tả ngắn, tiến độ tổng thể (% task hoàn thành), số thành viên
- Có ô tìm kiếm và bộ lọc (theo trạng thái, ngày tạo, tên)
- Click vào từng dự án để xem chi tiết

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

## 👥 User Stories – Quản lý Thành viên trong Dự án

---

### User Story #5: Mời thành viên tham gia dự án

**User Story:**  
As a Project Manager, I want to invite members to my project,  
So that they can collaborate on tasks and contribute to the project.

**Acceptance Criteria:**

- Nhập email hoặc chọn từ danh sách người dùng hệ thống
- Không cho phép mời người đã tham gia dự án
- Gửi email / thông báo mời tham gia dự án
- Thành viên được thêm vào danh sách thành viên dự án sau khi chấp nhận

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #6: Gán vai trò cho thành viên

**User Story:**  
As a Project Manager, I want to assign roles to project members,  
So that they have the correct permissions for their responsibilities.

**Acceptance Criteria:**

- Các vai trò có thể gồm: Member, Reviewer,...
- Có thể gán vai trò khi mời hoặc chỉnh sửa sau
- Không cho phép tự gán vai trò cao hơn cho bản thân
- UI hiển thị rõ vai trò của từng thành viên trong danh sách

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #7: Xóa thành viên khỏi dự án

**User Story:**  
As a Project Manager, I want to remove members from the project,  
So that I can manage the team when someone leaves or is no longer needed.

**Acceptance Criteria:**

- Chỉ PM hoặc Admin mới được phép xóa
- Hiện hộp thoại xác nhận trước khi xóa
- Sau khi xóa, thành viên không còn truy cập được vào dự án
- Ghi log hoặc thông báo cho người bị xóa (tuỳ chọn)

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

## 📋 User Stories – Quản lý Công việc (Task)

---

### User Story #8: Tạo task mới

**User Story:**  
As a Project Manager, I want to create new tasks,  
So that I can assign work to team members.

**Acceptance Criteria:**

- Có form tạo task gồm: tên, mô tả, người thực hiện, deadline, ưu tiên
- Tên task là bắt buộc
- Task hiển thị trong danh sách task của dự án và lịch
- Có thể tạo task chưa gán người thực hiện (backlog)

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #9: Gán task cho thành viên

**User Story:**  
As a Project Manager, I want to assign tasks to members,  
So that everyone knows what they are responsible for.

**Acceptance Criteria:**

- Danh sách thành viên chọn từ trong dự án
- Cho phép gán lại task cho người khác
- Gửi thông báo khi được gán task
- Hiển thị avatar hoặc tên người thực hiện

**Priority:** High  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #10: Thiết lập deadline và độ ưu tiên cho task

**User Story:**  
As a Project Manager, I want to set deadlines and priority levels for tasks,  
So that the team knows which tasks are most urgent.

**Acceptance Criteria:**

- Cho phép chọn ngày deadline từ date picker
- Ưu tiên gồm các mức: Low, Medium, High
- Hiển thị màu sắc khác nhau theo độ ưu tiên
- Cảnh báo khi task sắp đến hạn hoặc quá hạn

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #11: Cập nhật trạng thái task

**User Story:**  
As a Project Manager, I want to update task statuses,  
So that the team and I can track progress easily.

**Acceptance Criteria:**

- Các trạng thái cơ bản: To Do, In Progress, Done
- Có thể kéo thả giữa các cột nếu dùng giao diện Kanban
- Ghi lại thời gian cập nhật trạng thái (timestamp)
- Có filter theo trạng thái

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #12: Bình luận trong task

**User Story:**  
As a Project Manager, I want to comment on tasks,  
So that I can communicate instructions or feedback.

**Acceptance Criteria:**

- Có khung nhập bình luận + nút gửi
- Hiển thị tên và thời gian người bình luận
- Cho phép tag người dùng trong bình luận (@username)
- Gửi thông báo khi có bình luận mới

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #13: Chỉnh sửa hoặc thay đổi lịch task

**User Story:**  
As a Project Manager, I want to edit or reschedule tasks,  
So that I can adapt to project changes.

**Acceptance Criteria:**

- Có thể thay đổi tên, mô tả, người thực hiện, deadline
- Gửi thông báo khi có thay đổi quan trọng
- Lưu lịch sử thay đổi nếu có audit log

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

## 📈 User Stories – Theo dõi Tiến độ

---

### User Story #14: Xem dashboard tiến độ

**User Story:**  
As a Project Manager, I want to see a project dashboard,  
So that I can monitor task completion and team performance.

**Acceptance Criteria:**

- Hiển thị phần trăm task đã hoàn thành
- Thống kê số lượng task theo trạng thái
- Biểu đồ dạng cột hoặc tròn thể hiện tiến độ
- Giao diện responsive trên cả desktop và mobile

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #15: Nhận thông báo về tiến độ

**User Story:**  
As a Project Manager, I want to get notifications for overdue or completed tasks,  
So that I can act quickly when needed.

**Acceptance Criteria:**

- Thông báo có thể gửi qua hệ thống (in-app), email, hoặc push notification
- Thông báo khi task gần tới hạn, quá hạn, hoặc được đánh dấu là Done
- Có thể bật/tắt từng loại thông báo

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]

---

## 📅📆 User Stories – Quản lý Lịch trình & Họp

---

### User Story #16: Xem lịch tổng hợp

**User Story:**  
As a Project Manager, I want to view a calendar with tasks, meetings, and milestones,  
So that I can keep track of important deadlines and schedules.

**Acceptance Criteria:**

- Hiển thị task (📋), milestone (🔴), và lịch họp (📆) trên cùng một giao diện
- Cho phép filter theo loại sự kiện
- Chế độ xem ngày / tuần / tháng
- Có thể click vào từng sự kiện để xem chi tiết

**Priority:** High  
**Story Points:** 5  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #17: Tạo lịch họp

**User Story:**  
As a Project Manager, I want to schedule meetings,  
So that team members are aligned on time and agenda.

**Acceptance Criteria:**

- Form tạo gồm: tiêu đề, nội dung, thời gian, người tham gia
- Không cho lưu khi thiếu tiêu đề hoặc thời gian
- Gửi thông báo hoặc email mời họp
- Hiển thị trên lịch sau khi tạo

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #18: Thiết lập milestone

**User Story:**  
As a Project Manager, I want to create project milestones,  
So that I can track key deliverables and phases.

**Acceptance Criteria:**

- Nhập tên, mô tả, ngày milestone
- Gắn milestone với dự án
- Hiển thị milestone trên lịch
- Có thể liên kết với task liên quan

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** [Figma link / Ảnh đính kèm]

---

### User Story #19: Chỉnh sửa / hủy cuộc họp

**User Story:**  
As a Project Manager, I want to update or cancel meetings,  
So that the schedule reflects the current situation.

**Acceptance Criteria:**

- Cho chỉnh sửa thời gian, người tham gia, nội dung
- Có xác nhận khi hủy
- Gửi thông báo cập nhật hoặc hủy họp
- Cập nhật lịch ngay sau khi thay đổi

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / Ảnh đính kèm]
