## 🏢 User Stories – Vai trò: Owner (Chủ tổ chức)

---

### User Story #1: Tạo tổ chức mới

**User Story:**  
As a user, I want to create a new organization,  
So that I can manage members and projects under one workspace.

**Acceptance Criteria:**

- Có form tạo tổ chức: tên, mô tả, logo (tuỳ chọn)
- Không cho phép trùng tên tổ chức trong cùng hệ thống
- Sau khi tạo thành công, người tạo được gán vai trò Owner
- Tổ chức hiển thị trong dashboard cá nhân của Owner

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #2: Mời người dùng vào tổ chức

**User Story:**  
As an Owner, I want to invite users to my organization,  
So that they can join and collaborate on projects.

**Acceptance Criteria:**

- Gửi lời mời qua email hoặc chọn người dùng có sẵn trong hệ thống
- Người được mời phải xác nhận để gia nhập tổ chức
- Không được mời trùng người đã có trong tổ chức
- Có thể gán vai trò mặc định khi mời (PM, Member,...)

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #3: Gán Project Manager cho người dùng

**User Story:**  
As an Owner, I want to assign the PM role to a user in my organization,  
So that they can manage specific projects.

**Acceptance Criteria:**

- Chỉ hiện danh sách người thuộc tổ chức
- Cho phép gán PM cho dự án bất kỳ
- Nếu người đó đang là PM ở dự án khác thì không bị ảnh hưởng
- Có thể thu hồi vai trò PM và chuyển cho người khác

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #4: Tạo dự án mới trong tổ chức

**User Story:**  
As an Owner, I want to create new projects under my organization,  
So that I can assign them to Project Managers.

**Acceptance Criteria:**

- Form tạo dự án: tên, mô tả, deadline, gán PM
- Không cho phép trùng tên trong cùng tổ chức
- Dự án sau khi tạo thuộc quyền quản lý của tổ chức
- Dự án được thêm vào danh sách trong dashboard của Owner

**Priority:** High  
**Story Points:** 3  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #5: Xem danh sách dự án trong tổ chức

**User Story:**  
As an Owner, I want to see all projects in my organization,  
So that I can track what is being worked on.

**Acceptance Criteria:**

- Hiển thị tất cả dự án thuộc tổ chức (kể cả không phải mình là PM)
- Có thể lọc theo PM, trạng thái, ngày tạo
- Hiển thị thông tin cơ bản: tên dự án, tiến độ, số lượng task, PM phụ trách

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #6: Xem báo cáo tổng quan tổ chức

**User Story:**  
As an Owner, I want to view overall performance and progress of my organization,  
So that I can evaluate productivity and project status.

**Acceptance Criteria:**

- Dashboard tổng hợp: số dự án, tiến độ, task đã hoàn thành, task quá hạn
- Biểu đồ thống kê theo PM, theo dự án
- Có thể chọn khoảng thời gian xem báo cáo (tuần / tháng)

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** [Figma link / ảnh đính kèm]

---

### User Story #7: Gỡ thành viên khỏi tổ chức

**User Story:**  
As an Owner, I want to remove users from my organization,  
So that I can manage active members.

**Acceptance Criteria:**

- Chỉ cho phép gỡ người dùng không phải là Owner
- Hiển thị cảnh báo xác nhận trước khi xóa
- Sau khi gỡ, người dùng không còn truy cập dự án nào thuộc tổ chức

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** [Figma link / ảnh đính kèm]
