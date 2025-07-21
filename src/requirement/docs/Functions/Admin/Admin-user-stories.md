<<<<<<< HEAD

=======
<<<<<<<< HEAD:src/requirement/docs/05-user-stories.md
========

## Admin - User Stories

### US-ADMIN-01: Manage User Accounts

**User Story:**  
As an Admin, I want to create and delete user accounts, so that I can control who has access to the system.

**Acceptance Criteria:**  
- Admin can create a new user by entering Full Name, Email, Password, and Role  
- Admin can delete a user account  
- System validates that email is unique  
- Admin receives confirmation after successful creation or deletion  

**Priority:** High  
**Story Points:** 5  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-02: Assign User Roles

**User Story:**  
As an Admin, I want to assign roles (Admin, PM, Member) to users, so that each user has appropriate permissions.

**Acceptance Criteria:**  
- Admin can select a user and assign a role  
- System ensures users can only access features allowed by their role  
- Role updates are reflected immediately  

**Priority:** High  
**Story Points:** 3  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-03: Lock/Unlock Accounts

**User Story:**  
As an Admin, I want to lock or unlock user accounts, so that I can restrict access when needed.

**Acceptance Criteria:**  
- Admin can lock or unlock a user account  
- Locked users cannot log in  
- Admin is notified when an account is locked/unlocked  

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-04: Reset User Passwords

**User Story:**  
As an Admin, I want to reset user passwords, so that I can help users regain access to their accounts.

**Acceptance Criteria:**  
- Admin can trigger a password reset for any user  
- System sends a password reset email  
- User can update their password via a secure link  

**Priority:** Medium  
**Story Points:** 2  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-05: View All Projects

**User Story:**  
As an Admin, I want to view a list of all projects in the system, so that I can monitor their progress.

**Acceptance Criteria:**  
- Admin sees a dashboard of all projects  
- Each project displays key info (name, status, PM)  
- Admin can filter/sort projects  

**Priority:** High  
**Story Points:** 3  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-06: Remove Projects or Reassign PM

**User Story:**  
As an Admin, I want to delete projects or reassign their PM, so that I can maintain proper ownership and clean up the system.

**Acceptance Criteria:**  
- Admin can remove a project (with confirmation prompt)  
- Admin can select a new PM for any project  
- Changes are reflected in real-time  

**Priority:** High  
**Story Points:** 5  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-07: Manage Access Permissions

**User Story:**  
As an Admin, I want to configure access levels for users or roles, so that data and features are properly secured.

**Acceptance Criteria:**  
- Admin can create/update access rules per role  
- System prevents unauthorized access  
- Audit logs record changes  

**Priority:** High  
**Story Points:** 5  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-08: Configure SMTP / Email Settings

**User Story:**  
As an Admin, I want to set up SMTP/email configurations, so that the system can send notifications and alerts.

**Acceptance Criteria:**  
- Admin can input SMTP server details (host, port, user, password)  
- Test email function verifies settings  
- Errors are clearly reported  

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-09: Advanced Role Configuration

**User Story:**  
As an Admin, I want to configure detailed role-based access rules, so that I have fine-grained control over user permissions.

**Acceptance Criteria:**  
- Admin can assign module-level and action-level permissions  
- Role matrix UI shows which role can access which function  
- Changes are saved and applied immediately  

**Priority:** Medium  
**Story Points:** 5  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-10: Backup and Restore System

**User Story:**  
As an Admin, I want to back up and restore system data, so that I can prevent data loss and recover from incidents.

**Acceptance Criteria:**  
- Admin can trigger full system backup  
- Backups can be downloaded or stored securely  
- Restore process can be initiated from a backup file  

**Priority:** High  
**Story Points:** 8  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-11: View System Reports

**User Story:**  
As an Admin, I want to view overall reports of projects, users, and tasks, so that I can analyze system usage.

**Acceptance Criteria:**  
- Dashboard shows project/user/task counts  
- Reports can be filtered by date or status  
- Export function is available (PDF/CSV)  

**Priority:** Medium  
**Story Points:** 3  
**UI Design:** Figma link / Attached screenshot  

---

### US-ADMIN-12: Monitor Audit Logs

**User Story:**  
As an Admin, I want to view audit logs of user activity, so that I can trace important actions and maintain transparency.

**Acceptance Criteria:**  
- Logs include login/logout, create/edit/delete actions  
- Logs can be filtered by user or date  
- Secure access to log viewer  

**Priority:** High  
**Story Points:** 4  
**UI Design:** Figma link / Attached screenshot  
>>>>>>>> origin/namle:src/requirement/docs/Functions/Admin/Admin-user-stories.md
>>>>>>> origin/namle
