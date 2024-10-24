AbleSpace IEP Goal Tracking - Test Plan
This repository contains the test plans and procedures for testing the IEP Goal Tracking screen in AbleSpace. The test plan covers various UI, functional, performance, security, and integration aspects of the application.

Features to Test
UI/UX Testing

Goal list display, expand/collapse functionality, and "Add Goal" button functionality.
Functional Testing

Capturing trial data, Undo functionality, Graph and Capture views, etc.
Data Validation Testing

Ensure input validation for goal progress data.
Graph/Chart Testing

Real-time data updates and view switching for visualizing progress.
Role-Based Testing

Check permissions for different user roles (teacher, admin, view-only).
Bugs

  Security Bugs
Authentication: Weak password policies allowing insecure passwords (e.g., "123456").
Authorization: Unauthorized users can access restricted data, bypassing permissions.
Session Management: Sessions do not expire after inactivity, which can lead to security risks.
Cross-Site Scripting (XSS): Input fields, such as "Add Goal" and "Notes," are vulnerable to XSS attacks. Ensure proper input validation and sanitization.
Data Privacy: Lack of encryption for sensitive data (e.g., student names, progress), especially during transit (HTTP instead of HTTPS).
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/iep-goal-tracking-test-plan.git
Open the test plan documentation, located in the /docs folder.

Test Cases
The test cases are organized in a spreadsheet and markdown format for ease of use.
Each test case includes detailed steps, expected results, and status tracking.
Tools Used
Manual Testing for UI, functional, and data validation tests.
Used Jira software for test planning 

