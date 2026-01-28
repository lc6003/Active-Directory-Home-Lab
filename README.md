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

2. **Logon Hours Violation**
   - User tried logging in outside permitted hours
   - Diagnosed logon hours restriction
   - Adjusted user logon hours settings

3. **Expired Account**
   - User account expiration prevented login
   - Extended account expiration date
   - Verified successful authentication

**Group Policy Implementation:**

Created and configured Default Domain Policy for:

- **Password Policy:**
  - Minimum password length
  - Password complexity requirements
  - Password history
  - Maximum password age

- **Account Lockout Policy:**
  - Account lockout threshold
  - Account lockout duration
  - Reset lockout counter timer

### File Sharing & Permissions (1/25/2026)

**Shared Folder Configuration:**
- Created shared folders via Server Manager
- Configured NTFS permissions (Read, Modify, Full Control)
- Mapped network drives for users

**Security Group Management:**
- Created security groups for folder access
- Added users to security groups
- Assigned permissions at group level instead of individual users
- Reduced manual permission management overhead

**Example:** Configured "Jason" with Modify permissions (not Full Control) on shared folder

**Patch Management:**
- Installed Action1 patch management tool
- Generated system reports through Action1
- Created audit documentation

## Screenshots

**Screenshot 1 & 2:** User account creation and management (password reset, account disable, logon hours)

**Screenshot 3:** Account disabled error message

**Screenshot 4:** Logon hours restriction error

**Screenshot 5:** Expired account error

**Screenshot 6 & 7:** Group Policy configuration (password policy and account lockout policy)

**Screenshot 8:** NTFS folder permissions (Modify access for Jason)

**Screenshot 9:** Network drive mapping

**Screenshot 10:** Security group creation and user assignment
