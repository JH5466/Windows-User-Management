# Windows User Management

Hands-on Windows lab focused on creating, managing, and configuring local user accounts.

## 🧑‍💻 About This Lab
In this lab, I created and managed local user accounts in Windows to demonstrate how permissions and security groups control what each user can do on a system. I created three users—Sylvia, Scott, and Jed—and assigned each one the appropriate group membership based on their required privileges. Sylvia was added to the Administrators group for full system control, Scott was placed in the Backup Operators group to allow backup and restore operations, and Jed remained a standard user with only the default Users group membership. This lab highlights how proper group assignment helps maintain security and ensures users have only the access they need.

## 🛠️ Tools Used
- Windows 10 / Windows 11  
- Local Users and Groups (lusrmgr.msc)  
- Computer Management Console  

## 📝 Steps Performed
- Created three local user accounts: Sylvia, Scott, and Jed  
- Assigned Sylvia to the Administrators group  
- Assigned Scott to the Backup Operators group  
- Left Jed as a standard user in the Users group  
- Verified group membership for each account  

## ⭐ Skills Demonstrated
- Windows user account creation  
- Group membership management  
- Understanding of least privilege principles  
- Navigating Local Users and Groups  
- Basic Windows administration  

## 📸 Screenshots

- **sylvia-user-creation.png** — Creating the *Sylvia* user account in the Computer Management console using the “New User” window.  
- **scott-user-creation.png** — Creating the *Scott* user account using the same “New User” interface in Computer Management.  
- **jed-user-creation.png** — Creating the *Jed* user account through the “New User” window in Computer Management.  
- **sylvia-added-to-administrators.png** — Opening the *Administrators* group properties, selecting “Add,” and choosing the *Sylvia* account in the “Select Users” window to assign her administrative privileges.  
- **scott-added-to-backup-operators.png** — Opening the *Backup Operators* group properties and adding the *Scott* account through the “Select Users” window to grant backup and restore permissions.  

## 📂 Repository Structure
Windows-User-Management/
- Screenshots/
  - sylvia-user-creation.png
  - scott-user-creation.png
  - jed-user-creation.png
  - sylvia-added-to-administrators.png
  - scott-added-to-backup-operators.png
- README.md



