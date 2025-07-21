#  Use Case Diagram - Admin

##  Actor:
- **Admin**

---

##  Use Cases:

###  User Management
- **UC-ADMIN-01:** Create user
  - Actor: Admin
  - Description: Admin adds a new user with name, email, password and role.
- **UC-ADMIN-02:** Delete user
  - Actor: Admin
  - Description: Admin deletes a user permanently from the system.
- **UC-ADMIN-03:** Assign role
  - Actor: Admin
  - Description: Admin assigns roles such as Admin, PM, or Member to a user.
- **UC-ADMIN-04:** Lock/Unlock user
  - Actor: Admin
  - Description: Admin locks or unlocks user accounts.
- **UC-ADMIN-05:** Reset user password
  - Actor: Admin
  - Description: Admin resets passwords for users upon request.

---

###  System-wide Project Management
- **UC-ADMIN-06:** View all projects
  - Actor: Admin
  - Description: Admin views a list of all existing projects in the system.
- **UC-ADMIN-07:** Delete project
  - Actor: Admin
  - Description: Admin deletes a specific project.
- **UC-ADMIN-08:** Transfer project ownership
  - Actor: Admin
  - Description: Admin reassigns a Project Manager to a project.
- **UC-ADMIN-09:** Manage project access
  - Actor: Admin
  - Description: Admin configures access permissions per project.

---

###  System Configuration
- **UC-ADMIN-10:** Configure SMTP/Email
  - Actor: Admin
  - Description: Admin updates the SMTP settings to support email notifications.
- **UC-ADMIN-11:** Advanced permission configuration
  - Actor: Admin
  - Description: Admin manages advanced permission settings.
- **UC-ADMIN-12:** Backup system
  - Actor: Admin
  - Description: Admin performs a system backup.
- **UC-ADMIN-13:** Restore system
  - Actor: Admin
  - Description: Admin restores system data from a backup.

---

###  System Reports & Audit
- **UC-ADMIN-14:** View system summary reports
  - Actor: Admin
  - Description: Admin views stats like number of users, projects, overdue tasks, etc.
- **UC-ADMIN-15:** View login statistics
  - Actor: Admin
  - Description: Admin checks how many times users logged in.
- **UC-ADMIN-16:** View audit logs
  - Actor: Admin
  - Description: Admin views detailed logs of system activities like login, delete, edit actions.

---

###  Authentication & Session
- **UC-ADMIN-17:** Login
  - Actor: Admin
  - Description: Admin logs in to the system.
- **UC-ADMIN-18:** Logout
  - Actor: Admin
  - Description: Admin logs out of the system.
- **UC-ADMIN-19:** Change password
  - Actor: Admin
  - Description: Admin changes their own password.

---

##  Summary Table

| Use Case ID     | Name                          | Description                                         |
|-----------------|-------------------------------|-----------------------------------------------------|
| UC-ADMIN-01     | Create user                   | Add a new user                                      |
| UC-ADMIN-02     | Delete user                   | Remove a user account                               |
| UC-ADMIN-03     | Assign role                   | Set user role to Admin/PM/Member                    |
| UC-ADMIN-04     | Lock/Unlock user              | Temporarily deactivate/reactivate user              |
| UC-ADMIN-05     | Reset password                | Reset user’s password                               |
| UC-ADMIN-06     | View all projects             | Access full list of projects                        |
| UC-ADMIN-07     | Delete project                | Remove a project from the system                    |
| UC-ADMIN-08     | Transfer project ownership    | Reassign Project Manager                            |
| UC-ADMIN-09     | Manage project access         | Manage project-level access control                 |
| UC-ADMIN-10     | Configure SMTP/Email          | Set up mail server settings                         |
| UC-ADMIN-11     | Configure permissions         | Advanced role & permission settings                 |
| UC-ADMIN-12     | Backup system                 | Export full backup of the system                    |
| UC-ADMIN-13     | Restore system                | Restore backup data into the system                 |
| UC-ADMIN-14     | View reports                  | See summary statistics                              |
| UC-ADMIN-15     | View login stats              | Analyze user login data                             |
| UC-ADMIN-16     | View audit logs               | Track system-level actions                          |
| UC-ADMIN-17     | Login                         | Log into the system                                 |
| UC-ADMIN-18     | Logout                        | Log out of the system                               |
| UC-ADMIN-19     | Change password               | Update admin’s own password                         |


