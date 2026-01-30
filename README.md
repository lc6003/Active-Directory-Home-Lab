# Active-Directory-Home-Lab

### Active Directory Configuration (1/20/2026)

**User Account Management:**
- Created domain user accounts
- Configured user profile paths
- Reset user passwords
- Disabled/enabled user accounts
- Set account expiration dates
- Configured logon hours restrictions
- Locked and unlocked user accounts

**Example:** Created test user "Jason" to practice account management procedures

<img width="407" height="536" alt="Screenshot#1" src="https://github.com/user-attachments/assets/05a91681-2139-4fb0-a7d3-dfd08c9f8e2d" />

<img width="943" height="539" alt="Screenshot#2" src="https://github.com/user-attachments/assets/0ad9038e-943d-4986-b661-744f0c68eff8" />


### Domain Integration (1/23/2026)

**Client Setup:**
- Joined Windows 11 machine to Server 2022 domain
- Tested user authentication from domain-joined client
- Configured Remote Desktop access to domain controller

**Help Desk Troubleshooting Scenarios:**

Simulated and resolved three common login issues:

1. **Disabled Account Error**
   - User attempted login with disabled account
   - Identified issue via error message
   - Re-enabled account through ADUC

<img width="1016" height="756" alt="Screenshot#3" src="https://github.com/user-attachments/assets/74bc51bb-74ed-4448-aafe-61352eacafc3" />

2. **Logon Hours Violation**
   - User tried logging in outside permitted hours
   - Diagnosed logon hours restriction
   - Adjusted user logon hours settings

<img width="1017" height="762" alt="Screenshot#4" src="https://github.com/user-attachments/assets/5066b0e1-4aed-48a7-b974-7503ff856a80" />

3. **Expired Account**
   - User account expiration prevented login
   - Extended account expiration date
   - Verified successful authentication

<img width="1018" height="757" alt="Screenshot#5" src="https://github.com/user-attachments/assets/a407d199-d24d-4f71-9919-b8dd262267cc" />

**Group Policy Implementation:**

Created and configured Default Domain Policy for:

- **Password Policy:**
  - Minimum password length
  - Password complexity requirements
  - Password history
  - Maximum password age

<img width="545" height="204" alt="Screenshot#6" src="https://github.com/user-attachments/assets/83dbeee9-d2a8-478f-b056-9b5dc69bd80c" />

- **Account Lockout Policy:**
  - Account lockout threshold
  - Account lockout duration
  - Reset lockout counter timer

<img width="546" height="86" alt="Screenshot#7" src="https://github.com/user-attachments/assets/4503f116-a5aa-4845-99b9-77c639e4bd4c" />

### File Sharing & Permissions (1/25/2026)

**Shared Folder Configuration:**
- Created shared folders via Server Manager
- Configured NTFS permissions (Read, Modify, Full Control)
- Mapped network drives for users

<img width="502" height="82" alt="Screenshot#8" src="https://github.com/user-attachments/assets/d912084b-7d24-4ffe-85fa-4940220db670" />

<img width="360" height="445" alt="Screenshot#9" src="https://github.com/user-attachments/assets/71ce528b-b48b-4196-89cf-f5eaed752f9e" />

**Security Group Management:**
- Created security groups for folder access
- Added users to security groups
- Assigned permissions at group level instead of individual users
- Reduced manual permission management overhead

<img width="394" height="446" alt="Screenshot#10" src="https://github.com/user-attachments/assets/73cbf9ef-2c49-412e-93b3-ea833f7ef12b" />

**Example:** Configured "Jason" with Modify permissions (not Full Control) on shared folder

**Patch Management:**
- Installed Action1 patch management tool
- Generated system reports through Action1
- Created audit documentation

### Advanced Group Policy Configuration (1/27/2026)

- **Shutdown/Restart Restrictions**
  - Blocked shutdown and restart buttons from Start menu
  - Prevents users from powering down workstations during business hours

- **Password Management Control**
  - Removed "Change Password" option from Ctrl+Alt+Del menu
  - Enforces centralized password change procedures through help desk

- **Lock Computer Restriction**
  - Disabled ability to lock computer via Ctrl+Alt+Del
  - Controls workstation security through policy

- **Task Manager Access Control**
  - Removed access to Task Manager
  - Prevents users from terminating critical processes or viewing system information

<img width="605" height="138" alt="Screenshot#11" src="https://github.com/user-attachments/assets/33249144-4890-4498-b893-3255b6d76d63" />

<img width="684" height="634" alt="Screenshot#12" src="https://github.com/user-attachments/assets/e11b0c56-86c4-4a1b-aba7-1971140219df" />

## Screenshots

**Screenshot 1 & 2:** User account creation and management (password reset, account disable, logon hours)

**Screenshot 3:** Account disabled error message

**Screenshot 4:** Logon hours restriction error

**Screenshot 5:** Expired account error

**Screenshot 6 & 7:** Group Policy configuration (password policy and account lockout policy)

**Screenshot 8 & 9:** NTFS folder permissions (Modify access for Jason)

**Screenshot 10:** Security group creation and user assignment

**Screenshot 11 & 12:** Advanced Group Policy settings (desktop restrictions: shutdown/restart block, password change removal, lock computer removal, Task Manager access control)

**Screenshot 13** Joining Domain
