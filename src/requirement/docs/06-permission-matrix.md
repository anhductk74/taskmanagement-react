# 👥 Roles

| Role          | Mô tả                                                                 |
|---------------|----------------------------------------------------------------------|
| **Admin**     | Quản trị toàn hệ thống (nhiều công ty, nhiều người dùng)             |
| **Owner**     | Chủ sở hữu công ty, tạo và quản lý các dự án trong công ty mình      |
| **PM**        | Quản lý một dự án cụ thể (được giao bởi Owner)                        |
| **Leader**    | Trưởng nhóm, phân chia và theo dõi công việc trong nhóm nhỏ          |
| **Member**    | Thành viên thực hiện công việc được giao trong dự án                 |

---
## 1. 👤 User Management
| Action              | Admin | Owner | PM  | Leader | Member |
|---------------------|:-----:|:-----:|:--:|:------:|:------:|
| Create user         | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Edit user info      | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Delete user         | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Assign roles        | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Lock/unlock user    | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Reset password      | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| View all users      | ✅    | ✅    | ❌ |   ❌   |   ❌   |

## 2. 🧩 Company Management
| Action                 | Admin | Owner | PM  | Leader | Member |
|------------------------|:-----:|:-----:|:--:|:------:|:------:|
| Create company         | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| Edit company info      | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Delete company         | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| Manage company users   | ✅    | ✅    | ❌ |   ❌   |   ❌   |

## 3. 📁 Project Management
| Action             | Admin | Owner | PM  | Leader | Member |
|--------------------|:-----:|:-----:|:--:|:------:|:------:|
| Create project     | ✅    | ✅    | ✅ |   ❌   |   ❌   |
| Edit project info  | ✅    | ✅    | ✅ |   ❌   |   ❌   |
| Delete project     | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Assign PM          | ✅    | ✅    | ❌ |   ❌   |   ❌   |
| Assign members     | ✅    | ✅    | ✅ |   ❌   |   ❌   |
| Remove members     | ✅    | ✅    | ✅ |   ❌   |   ❌   |
| View all projects  | ✅    | ✅    | ✅ |   ✅   |   ✅   |

## 4. ✅ Task Management
| Action              | Admin | Owner | PM  | Leader | Member |
|---------------------|:-----:|:-----:|:--:|:------:|:------:|
| Create task         | ✅    | ✅    | ✅ |   ✅   |   ❌   |
| Assign task         | ✅    | ✅    | ✅ |   ✅   |   ❌   |
| Edit task           | ✅    | ✅    | ✅ |   ✅   |   ❌   |
| Delete task         | ✅    | ✅    | ✅ |   ✅   |   ❌   |
| Comment on task     | ✅    | ✅    | ✅ |   ✅   |   ✅   |
| Change task status  | ✅    | ✅    | ✅ |   ✅   |   ✅   |
| View task details   | ✅    | ✅    | ✅ |   ✅   |   ✅   |

## 5. ⚙️ System Configuration
| Action                   | Admin | Owner | PM  | Leader | Member |
|--------------------------|:-----:|:-----:|:--:|:------:|:------:|
| Configure email (SMTP)   | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| Configure roles & access | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| System backup            | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| Restore from backup      | ✅    | ❌    | ❌ |   ❌   |   ❌   |

## 6. 📊 Reporting & Logs
| Action                    | Admin | Owner | PM  | Leader | Member |
|---------------------------|:-----:|:-----:|:--:|:------:|:------:|
| View system stats         | ✅    | ❌    | ❌ |   ❌   |   ❌   |
| View company/project stats| ✅    | ✅    | ✅ |   ✅   |   ❌   |
| View overdue task reports | ✅    | ✅    | ✅ |   ✅   |   ❌   |
| View audit logs           | ✅    | ✅    | ❌ |   ❌   |   ❌   |
