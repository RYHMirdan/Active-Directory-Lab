**AD:**

 - Created and organized OU's for Admins and Users
 - Applied GPO's to enforce password and login restrictions
 - Added 1k+ test users through powershell automation

**ADMINS OU created:**

<img width="592" height="418" alt="Screenshot 2025-08-09 030921" src="https://github.com/user-attachments/assets/e09a252d-292a-47a6-908b-87e4a6afcee4" />

Created the Admins OU, set up a username style: first letter of first name+ last name

**Powershell script used to automate the bulk 1000 users creation.** 

<img width="598" height="407" alt="Screenshot 2025-08-08 034711" src="https://github.com/user-attachments/assets/a99c690f-bbee-43a1-8eae-d1c09d086c3d" />

"_USERS" OU created in Active Directory, Script sets the same password for all users, Loop made for all users being evaliated, the loop will split the user's name between first and last, then in the first initial + full last name format, a username will be created. "password never expires" box will be checked on, then the information is to directed in the _USERS folder in the AD, the account then gets enabled.

**Bulk 1000 users made using powershell scripting:**

<img width="598" height="410" alt="Screenshot 2025-08-08 035721" src="https://github.com/user-attachments/assets/70579926-3f35-40e3-b45c-79713e517196" />

**Ensuring that the Windows Client was registered on the Active Directory:**
<img width="748" height="524" alt="Screenshot 2025-08-08 233253" src="https://github.com/user-attachments/assets/1d96905b-af90-4d9e-8981-798f7be5b7c9" />
