# Lab 01 – Resetting a User Password in Active Directory

## Objective
Resolve a user login issue by resetting the user’s domain password in **Active Directory** and forcing a password change at next logon.

## Scenario (Ticket Style)
**User:** User1 Test  
**Issue:** “I can’t log in. My password isn’t working.”  
**Role:** Tier 1 IT Help Desk

## Environment & Tools
- Windows Server (Active Directory Domain Services)
- Windows 10/11 domain-joined client
- Active Directory Users and Computers (ADUC)

## Steps Performed

1. Opened **Active Directory Users and Computers** on the domain controller.
2. Navigated to the correct OU and located the user account (**User1 Test**).
3. Right-clicked the user and selected **Reset Password…**.
4. Entered a temporary password and checked **“User must change password at next logon.”**
5. Instructed the user to log in with the temporary password and set a new one.
6. Verified the user could sign in successfully with their new password.

*(Screenshots will be added below once uploaded.)*

## Screenshots

- Locating the user account in ADUC  
- Reset password dialog  
- Successful logon after password reset  

(Markdown image links will go here.)

## Result

- User’s password was reset successfully.
- User was forced to choose a new password at next logon.
- Issue would be marked **Resolved** in a ticketing system.

## What I Learned

- How to safely reset a user’s domain password in Active Directory.
- The importance of **“User must change password at next logon”** for security.
- How this task fits into common Tier 1 IT Help Desk workflows.
