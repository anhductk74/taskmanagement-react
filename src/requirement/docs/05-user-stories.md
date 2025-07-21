# ✅ 3. Member

## 🧩 User Story #1: View Assigned Tasks

**User Story:**  
As a **project member**,  
I want to **view the list of tasks assigned to me within each project**,  
So that **I know what I need to do and by when**.

**Acceptance Criteria:**

- [ ] Display task list grouped by project  
- [ ] Show only tasks assigned to the logged-in user  
- [ ] Include deadline, status, and brief description for each task  
- [ ] Provide filter options by task status (All, Not Started, In Progress, Completed)

**Priority:** High  
**Story Points:** 5  
**UI Design:** `TaskListByProject.png`

---

## 🧩 User Story #2: Update Task Status

**User Story:**  
As a **project member**,  
I want to **update the status of my tasks**,  
So that **my manager can track progress in real time**.

**Acceptance Criteria:**

- [ ] Allow selecting status: Not Started, In Progress, Completed  
- [ ] Status is updated and reflected instantly in the UI  
- [ ] Record timestamp and user who updated the status  
- [ ] Send a notification to the manager upon status update

**Priority:** High  
**Story Points:** 3  
**UI Design:** `TaskStatusDropdown.png`

---

## 🧩 User Story #3: Comment & Collaborate on Tasks

**User Story:**  
As a **project member**,  
I want to **comment and collaborate on tasks**,  
So that **I can clarify requirements and coordinate with teammates**.

**Acceptance Criteria:**

- [ ] Comment input field and submit button are available  
- [ ] Display comments in chronological order  
- [ ] Show commenter’s name and timestamp  
- [ ] Notify relevant users when a new comment is posted

**Priority:** Medium  
**Story Points:** 5  
**UI Design:** `TaskCommentsSection.png`

---

## 🧩 User Story #4: Join Team Meetings

**User Story:**  
As a **project member**,  
I want to **view upcoming meeting schedules and receive meeting invitations**,  
So that **I can join team meetings on time**.

**Acceptance Criteria:**

- [ ] Display upcoming meetings  
- [ ] Show invitation with RSVP option  
- [ ] Optionally sync with Google Calendar  
- [ ] Reminder before meeting time (via app or email)

**Priority:** Medium  
**Story Points:** 8  
**UI Design:** `MeetingScheduleCard.png`

---

# ✅ 4. Common

## 🧩 User Story #5: Sign Up & Log In

**User Story:**  
As a **new user**,  
I want to **sign up and log in using my email and password**,  
So that **I can access the system with a personalized role**.

**Acceptance Criteria:**

- [ ] Signup form requires Email, Password, Confirm Password  
- [ ] Password must be at least 8 characters  
- [ ] Show error for incorrect login info  
- [ ] Optional: Email verification after signup

**Priority:** High  
**Story Points:** 5  
**UI Design:** `LoginSignupPage.png`

---

## 🧩 User Story #6: Manage Personal Profile

**User Story:**  
As a **logged-in user**,  
I want to **update my personal information**,  
So that **my profile remains accurate and secure**.

**Acceptance Criteria:**

- [ ] Allow editing name, avatar, and password  
- [ ] Avatar supports upload and preview  
- [ ] Require old password when changing password  
- [ ] Show success message after saving changes

**Priority:** Medium  
**Story Points:** 5  
**UI Design:** `ProfileEditModal.png`

---

## 🧩 User Story #7: Receive Notifications

**User Story:**  
As a **system user**,  
I want to **receive notifications about tasks, comments, or changes**,  
So that **I stay informed without missing updates**.

**Acceptance Criteria:**

- [ ] Notification icon in the header  
- [ ] List of notifications sorted by time  
- [ ] Each notification includes an icon (task, meeting, comment)  
- [ ] Allow marking notifications as read and toggling notification types

**Priority:** Medium  
**Story Points:** 8  
**UI Design:** `NotificationDropdown.png`
