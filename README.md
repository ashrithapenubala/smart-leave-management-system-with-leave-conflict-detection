# 🚀 Smart Leave Management System with Leave Conflict Detection

> A ServiceNow application designed to streamline leave management, automate approvals, manage leave balances, and proactively detect leave conflicts to support better workforce planning.

---

## 📖 Project Overview

Organizations often manage leave requests through emails, spreadsheets, or manual processes, which can result in delays, poor visibility, and scheduling conflicts.

The **Smart Leave Management System with Leave Conflict Detection** addresses these challenges by providing a centralized platform where employees can submit leave requests and managers can efficiently review, approve, or reject them.

The system automatically calculates leave duration, updates leave balances upon approval, detects overlapping leave requests, and provides reports and dashboards for monitoring and decision-making.

---

## 🎯 Project Objectives

* Automate leave request submission and approval.
* Improve transparency in leave management.
* Reduce manual administrative effort.
* Detect leave conflicts before approval.
* Track employee leave balances.
* Provide reporting and dashboard insights.

---

## ✨ Key Features

### 👨‍💼 Employee Module

* Submit Leave Requests
* View Leave Status
* Track Leave History

### 👩‍💼 Manager Module

* Review Leave Requests
* Approve or Reject Requests
* Add Approval Comments

### ⚙️ System Features

* Automatic Leave Day Calculation
* Leave Conflict Detection
* Leave Balance Management
* Status Tracking
* Approval Workflow
* Reports and Dashboards

---

## 🔄 Workflow

Employee Applies for Leave

⬇

System Creates Request

⬇

Total Days Calculated Automatically

⬇

Conflict Detection Check

⬇

Manager Review

⬇

Approve / Reject

⬇

Leave Balance Updated (If Approved)

⬇

Employee Notification

---

## 🛠 Technology Stack

| Technology           | Purpose                  |
| -------------------- | ------------------------ |
| ServiceNow           | Application Development  |
| Custom Tables        | Data Management          |
| Business Rules       | Automation & Validation  |
| Flow Designer        | Process Automation       |
| Reports & Dashboards | Analytics and Monitoring |

---

## 🏗 Technical Components

### Custom Tables

#### Leave Request

* Employee
* Leave Type
* Start Date
* End Date
* Total Days
* Reason
* Status
* Manager
* Conflict Flag
* Comments

#### Leave Balance

* Employee
* Leave Type
* Allocated Days
* Used Days
* Remaining Days
* Year

#### Leave Conflict

* Request 1
* Request 2
* Conflict Date
* Department
* Resolved

---

### Business Rules

#### 1. Total Days Calculation

Automatically calculates leave duration between start date and end date.

#### 2. Leave Conflict Detection

Identifies overlapping leave requests and creates conflict records.

#### 3. Leave Balance Deduction

Updates used days and remaining leave balance after leave approval.

---

### Flow Designer

The workflow automates:

1. Leave Request Submission
2. Manager Approval/Rejection
3. Status Update
4. Employee Notification

---

## 📊 Reports Created

1. Leave Requests by Status
2. Leave Balance by Employee
3. Leave Conflicts Detected

---

## 📈 Dashboard

### Smart Leave Management Dashboard

Includes:

* Leave Requests by Status
* Leave Balance by Employee
* Leave Conflicts Detected

---

## 🧪 Testing Summary

| Test Case | Description                               | Result |
| --------- | ----------------------------------------- | ------ |
| TC01      | Leave Submission & Total Days Calculation | ✅ PASS |
| TC02      | Leave Conflict Detection                  | ✅ PASS |
| TC03      | Approved Leave Balance Update             | ✅ PASS |
| TC04      | Rejected Leave Balance Validation         | ✅ PASS |

### Testing Results

#### TC01 – Total Days Calculation

Input:

* Start Date: July 1
* End Date: July 3

Output:

* Total Days: 3

Result: PASS

#### TC02 – Conflict Detection

Multiple leave requests with overlapping dates were detected successfully.

Result: PASS

#### TC03 – Approval Workflow

Before Approval:

* Allocated Days: 12
* Used Days: 3
* Remaining Days: 9

After Approval:

* Allocated Days: 12
* Used Days: 6
* Remaining Days: 6

Result: PASS

#### TC04 – Rejected Leave Request

Before Rejection:

* Used Days: 2
* Remaining Days: 8

After Rejection:

* Used Days: 2
* Remaining Days: 8

Result: PASS

---

## ⚠️ Challenges Faced

### Challenge 1

Leave balance was not updating correctly after approval.

### Solution

Verified Business Rule logic, checked status values, and corrected field value comparisons.

---

### Challenge 2

Understanding the interaction between Business Rules and Flow Designer.

### Solution

Performed extensive testing and debugging to ensure workflow automation worked correctly.

---

## 📊 Business Value

* Reduces manual leave management efforts.
* Improves approval efficiency.
* Prevents scheduling conflicts.
* Improves workforce planning.
* Enhances employee and manager experience.
* Provides accurate leave tracking and reporting.

---

## 🔮 Future Enhancements

* Team Leave Calendar
* Multi-Level Approval Workflow
* Mobile-Friendly Interface
* Advanced Leave Analytics
* Department-Based Leave Planning

---

## 📷 Screenshots

Repository contains screenshots of:

* Leave Request Form
* Leave Balance Form
* Leave Conflict Form
* Business Rules
* Flow Designer Workflow
* Reports
* Dashboard
* Testing Results

---

## 🎓 Learning Outcomes

Through this project, I learned:

* ServiceNow Application Development
* Creating Custom Tables
* Implementing Business Rules
* Workflow Automation using Flow Designer
* Report and Dashboard Creation
* Testing and Debugging
* Real-World Process Automation

---

## 🚀 Project Status

✅ Completed

The Smart Leave Management System has been successfully implemented, tested, and validated in ServiceNow. All major functionalities including leave requests, approval workflows, conflict detection, leave balance management, reports, and dashboards are working as expected.

---

## 👩‍💻 Author

### P. Ashritha

B.Tech Computer Science and Engineering
Mohan Babu University

### Certifications

* ServiceNow Certified System Administrator (CSA)
* ServiceNow Certified Application Developer (CAD)

---

⭐ If you found this project interesting, feel free to explore the repository and provide feedback.
