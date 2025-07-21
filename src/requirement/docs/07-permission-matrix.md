## 👥 Roles
- **Admin** – Quản trị toàn hệ thống  
- **PM** – Quản lý dự án cụ thể  
- **Member** – Thành viên tham gia thực hiện công việc trong dự án

---

### 1. User Management

| Action            | Admin | PM   | Member |
|-------------------|:-----:|:----:|:------:|
| Create user       | ✅    | ❌   | ❌     |
| Edit user info    | ✅    | ❌   | ❌     |
| Delete user       | ✅    | ❌   | ❌     |
| Assign roles      | ✅    | ❌   | ❌     |
| Lock/unlock user  | ✅    | ❌   | ❌     |
| Reset password    | ✅    | ❌   | ❌     |
| View all users    | ✅    | ❌   | ❌     |

---

### 2. Project Management (All Projects)

| Action                  | Admin | PM   | Member |
|-------------------------|:-----:|:----:|:------:|
| View all projects       | ✅    | ❌   | ❌     |
| Delete project          | ✅    | ❌   | ❌     |
| Transfer ownership      | ✅    | ❌   | ❌     |
| Manage project access   | ✅    | ❌   | ❌     |

---

### 3. Project Management (Own Projects)

| Action               | Admin | PM   | Member |
|----------------------|:-----:|:----:|:------:|
| Create project        | ✅    | ✅   | ❌     |
| Edit project info     | ✅    | ✅   | ❌     |
| Delete own project    | ✅    | ✅   | ❌     |
| Assign members        | ✅    | ✅   | ❌     |
| Remove members        | ✅    | ✅   | ❌     |
| View all tasks        | ❌    | ✅   | ❌     |


---

### 4. Task Management

| Action             | Admin | PM   | Member |
|--------------------|:-----:|:----:|:------:|
| Create task         | ✅    | ✅   | ❌     |
| Assign task         | ✅    | ✅   | ❌     |
| Edit task           | ✅    | ✅   | ❌     |
| Delete task         | ✅    | ✅   | ❌     |
| Comment on task     | ✅    | ✅   | ✅     |
| Change task status  | ✅    | ✅   | ✅     |

---

### 5. System Configuration

| Action                      | Admin | PM   | Member |
|-----------------------------|:-----:|:----:|:------:|
| Configure email (SMTP)      | ✅    | ❌   | ❌     |
| Configure advanced roles    | ✅    | ❌   | ❌     |
| Backup system               | ✅    | ❌   | ❌     |
| Restore system              | ✅    | ❌   | ❌     |

---

### 6. Reporting & Logs

| Action                    | Admin | PM   | Member |
|---------------------------|:-----:|:----:|:------:|
| View system stats         | ✅    | ❌   | ❌     |
| View project stats        | ✅    | ✅   | ❌     |
| View overdue task report  | ✅    | ✅   | ❌     |
| View audit logs           | ✅    | ❌   | ❌     |
