# Lab 01 – Resetting a User Password in Active Directory

## Objective
Resolve a user login issue by resetting the user’s domain password in **Active Directory** and forcing a password change at next logon.

## Scenario (Ticket Style)
**User:** Ervin  
**Issue:** “I can’t log in. My password isn’t working.”  
**Role:** Tier 1 IT Help Desk

## Environment & Tools
- Windows Server (Active Directory Domain Services)
- Windows 11 domain-joined client
- Active Directory Users and Computers (ADUC)

## Steps Performed

1. Opened **Active Directory Users and Computers** on the domain controller.
2. Navigated to the correct OU and located the user account (**Ervin**).
3. Right-clicked the user and selected **Reset Password…**.
4. Entered a temporary password and checked **“User must change password at next logon.”**
5. Instructed the user to log in with the temporary password and set a new one.
6. Verified the user could sign in successfully with their new password.


## Screenshots

- Locating the user account in ADUC
  
<img width="598" height="582" alt="User" src="https://github.com/user-attachments/assets/fb829396-33a3-44c9-a1b9-4f2ba814a141" />

- Reset password dialog
<img width="448" height="326" alt="Reset_Dialog" src="https://github.com/user-attachments/assets/d006b22f-7974-4fca-afce-f9e484129c7c" />

- Successful logon after password reset  
<img width="441" height="480" alt="Change_password" src="https://github.com/user-attachments/assets/25712452-aa84-46fe-b394-cdd669bfe31b" />

<img width="669" height="711" alt="Successful_login" src="https://github.com/user-attachments/assets/7798691d-e0f0-44de-b01a-a4262680dbe4" />

## Result

- User’s password was reset successfully.
- User was forced to choose a new password at next logon.
- Issue would be marked **Resolved** in a ticketing system.

## What I Learned

- How to safely reset a user’s domain password in Active Directory.
- The importance of **“User must change password at next logon”** for security.

