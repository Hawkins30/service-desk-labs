# PowerShell Lab – Service Desk Automation

## Purpose
The purpose of this lab is to demonstrate practical use of PowerShell to automate common first-line IT service desk tasks in an Active Directory environment. The lab focuses on safe, repeatable automation for user account management, which is a core responsibility in junior IT support roles.

This lab reflects real-world service desk usage of PowerShell to improve efficiency, consistency, and accuracy when handling user issues.

---

## Tools Used
- Windows Server (Active Directory Domain Controller)
- Windows PowerShell
- Active Directory PowerShell module

---

## Lab Environment
- Domain: LAB.local
- Role: Domain Administrator
- Test User: john.smith

---

## Tasks Performed

### PowerShell Environment Setup
- Opened Windows PowerShell with administrative privileges.
- Verified PowerShell version to confirm modern PowerShell functionality.
- Imported the Active Directory module to enable AD-related cmdlets.

Screenshots:
- PowerShell opened as Administrator
- PowerShell version information
- Active Directory module imported successfully

---

### User Account Query and Status Checks
- Queried Active Directory to confirm the existence of a specific user account.
- Checked account lockout status using PowerShell.
- Verified user properties using read-only commands before making changes.

Screenshots:
- AD user query output
- LockedOut property check

---

### Service Desk Account Management Tasks
- Unlocked a user account using PowerShell.
- Reset the user’s password with a temporary password.
- Forced the user to change their password at next logon.
- Added the user to a security group to simulate access provisioning.
- Verified group membership after changes were applied.

Screenshots:
- Account unlock command
- Password reset command
- Change password at next logon command
- Group membership modification
- Group membership verification output

---

### PowerShell Automation Script
- Created a PowerShell script to automate multiple service desk actions.
- Script performs the following tasks:
  - Unlocks a user account
  - Resets the user’s password
  - Forces password change at next logon
  - Outputs confirmation of completed actions
- Executed the script successfully and verified results.

Screenshots:
- Script file created
- Script contents
- Script execution output
- Verification of account status after script execution

---

## What I Learned
- How PowerShell is used in real service desk environments
- How to safely query Active Directory using PowerShell
- How to unlock accounts and reset passwords via command line
- How to manage group membership using PowerShell
- How to combine multiple commands into a simple automation script
- The importance of verification after making account changes

---

## Why This Lab Matters
PowerShell is widely used in IT support roles to automate repetitive tasks and reduce manual errors. This lab demonstrates the ability to use PowerShell responsibly to perform common service desk actions efficiently while maintaining control and visibility over changes.

The skills demonstrated in this lab are directly applicable to first-line and junior IT support positions.

