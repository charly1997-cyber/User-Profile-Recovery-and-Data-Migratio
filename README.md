# User-Profile-Recovery-and-Data-Migratio
Recover a corrupted Windows user profile while preserving user data.
# Environment
	•	Windows Server 2019 Domain Controller
	•	Active Directory Domain Services
	•	Windows 10 Client
	•	VMware Workstation

# Problem

A domain user reported profile-related issues. Upon investigation, the account was loading an incorrect profile path and applications were not functioning properly.

# Commands used
whoami
echo %userprofile%

# Troubleshooting Steps
	1.	Verified current logged-in user.
	2.	Checked active profile path.
	3.	Logged into an administrative account.
	4.	Created a replacement user profile.
	5.	Logged into the new account to generate a fresh Windows profile.
	6.	Preserved existing user data by keeping the old profile folder.
	7.	Migrated user files from the old profile to the new profile.
	8.	Verified application functionality and profile integrity.

 # Data Preserved
	•	Desktop
	•	Documents
	•	Downloads
	•	Pictures
	•	Favorites

Excluded:
	•	AppData
	•	NTUSER.DAT

  Skills Demonstrated
	•	Windows User Profile Troubleshooting
	•	Active Directory User Management
	•	Data Migration
	•	Help Desk Troubleshooting
	•	Desktop Support
	•	Windows Administrative



