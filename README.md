[![Latest-Version](https://img.shields.io/badge/Latest_Version-1-green)](https://github.com/PezzaD84/JAMF-LAPS-Menubar-app/releases) ![macOS-Versions](https://img.shields.io/badge/macOS-11+-blue) ![Script-Language](https://img.shields.io/badge/Coding_Language-Bash-blue) [![Powered-by](https://img.shields.io/badge/Powered_by-SupportApp-red)](https://github.com/root3nl/SupportApp) 

# JAMF LAPS MenuBar App

---
A menubar app for displaying the JAMF LAPS account and password
<img width="454" alt="Screenshot 2024-09-05 at 11 38 47" src="https://github.com/user-attachments/assets/5626ecfc-3ae3-4fa1-87b9-bc3612402f96">

---

**Setup**

- To install the menu bar app download the pkg and config profile
- Upload the pkg to JAMF
- Create a policy to install the pkg
- Upload the Config Profile to JAMF
- Edit the com.jamf.laps.menubar plist in the Config Profile
- Fill in the JAMFURL string with your JAMF tenant
- Fill in the ENCODEDAPI string with your encoded API account
- Scope the config profile and policy to install

