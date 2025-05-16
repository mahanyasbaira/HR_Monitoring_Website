HR Management System
&lt;p align="center">
&lt;img src="[suspicious link removed]" alt="HR Management System Banner">
&lt;/p>

A comprehensive web-based Human Resources (HR) management system built using PHP (likely Laravel).

This system provides a comprehensive suite of tools for HR administrators to manage employees, track attendance, handle leave requests, and oversee various organizational activities. It also includes API endpoints, suggesting the possibility of mobile or other external application integrations.

⚙️ Key Features and Functionalities
(deduced from the code)

👤 Employee Management
Handles employee data with functionalities for creating, retrieving, updating, and potentially archiving records.
Relevant files: app/Http/Controllers/Web/UserController.php, app/Http/Controllers/Api/UserProfileApiController.php, app/Models/User.php
⏱️ Attendance Tracking
Features for tracking employee attendance, including clock-in/clock-out, reports, and potential corrections.
Relevant files: app/Http/Controllers/Web/AttendanceController.php, app/Http/Controllers/Api/AttendanceApiController.php, app/Models/Attendance.php
🗓️ Leave Management
Supports leave requests and management, allowing employees to apply and administrators to review/approve/reject.
Relevant files: app/Http/Controllers/Web/LeaveController.php, app/Http/Controllers/Api/LeaveApiController.php, app/Models/LeaveRequestMaster.php, app/Models/LeaveType.php
📂 Project Management
Modules for project creation, employee assignment, task management, and progress tracking.
Relevant files: app/Http/Controllers/Web/ProjectController.php, app/Http/Controllers/Api/ProjectApiController.php, app/Models/Project.php, app/Models/Task.php
✅ Task Management
Allows for the creation and management of tasks with checklists, comments, and attachments.
Relevant files: app/Http/Controllers/Web/TaskController.php, app/Http/Controllers/Api/TaskApiController.php, app/Models/TaskChecklist.php, app/Models/TaskComment.php, app/Models/Attachment.php
🛡️ Role and Permission Management
Includes a role-based permission system for defining roles and assigning specific permissions to users.
Relevant files: app/Http/Controllers/Web/RoleController.php, app/Helpers/RolePermissionHelper.php, app/Models/Role.php, app/Models/Permission.php
📢 Notice and Notification System
Features for creating and managing internal communications through notices and notifications.
Relevant files: app/Http/Controllers/Web/NoticeController.php, app/Http/Controllers/Web/NotificationController.php, app/Models/Notice.php, app/Models/Notification.php
📊 Reporting and Data Export
Functionalities to generate and export reports for attendance, employee data, etc.
Relevant files: app/Http/Controllers/Web/DataExportController.php, app/Exports/
🌐 API Functionality
Provides API endpoints for various functionalities, enabling mobile app or other system integrations.
Relevant directory: app/Http/Controllers/Api/
⚙️ General Settings
Administrators can configure various system settings.
Relevant files: app/Http/Controllers/Web/GeneralSettingController.php, app/Models/GeneralSetting.php
📞 Support/Ticket System
Features for employees to submit support requests and administrators to manage them.
Relevant files: app/Http/Controllers/Web/SupportController.php, app/Models/Support.php
✈️ TADA Management
Functionality to manage Travel Allowance and Daily Allowance.
Relevant files: app/Http/Controllers/Web/TadaController.php, app/Models/Tada.php
🤝 Team Meetings
Supports scheduling and managing team meetings.
Relevant files: app/Http/Controllers/Web/TeamMeetingController.php, app/Models/TeamMeeting.php
🏢 Asset Management
Functionality to manage company assets.
Relevant files: app/Http/Controllers/Web/AssetController.php, app/Models/Asset.php
In essence, this project delivers a robust digital platform designed to streamline and manage a wide array of HR-related operations and organizational workflows.
