# Microsoft-Entra-ID-Lab

# Lab: Create and Manage Microsoft Entra ID Users in the Azure Portal

This lab demonstrates the process of creating, modifying, revoking, and deleting users in **Microsoft Entra ID** using the **Azure Portal**. It provides hands-on experience with identity lifecycle management and simulates real-world administrative and incident response scenarios.

---

## 🧠 Objective
The purpose of this lab is to practice managing user accounts in Microsoft Entra ID through the Azure Portal.  
This includes:
- Creating new users  
- Modifying user properties  
- Resetting passwords  
- Revoking active sessions  
- Deleting and recovering user accounts  

---

## 🧰 Tools Used
- **Microsoft Azure Portal**
- **Microsoft Entra ID**
- **Web Browser (Google Chrome)**

---

## ⚙️ Steps Taken

### 1. Log in to the Azure Portal
1. Navigated to [https://portal.azure.com](https://portal.azure.com)  
2. Signed in using provided lab credentials  
3. Dismissed any setup or prompt screens  

---

### 2. Create Microsoft Entra ID User Accounts
1. Opened the **hamburger menu → Microsoft Entra ID → Users**  
2. Selected **New user → Create new user**  
3. Entered the following details:  
   - **Display name:** User One  
   - **User principal name:** user.one  
4. Clicked **Next → Properties → Review + Create → Create**  
5. Repeated the process for **User Two** and **User Three**  
6. Verified all users appeared under **All users** after refreshing the page  

---

### 3. Modify a User Account
1. Selected **User One** from *All users*  
2. Viewed the available options in the user profile sidebar  
3. Clicked **Edit properties**, updated **Job title** and **Display name**, and saved changes  
4. Selected **Reset password**, and clicked **Reset password** to generate a temporary password  

---

### 4. Revoke User Access
1. With **User One** selected, clicked **Revoke sessions → Yes**  
2. Confirmed that the user's sessions were terminated immediately  

---

### 5. Delete a User Account
1. In *All users*, selected **User Three** and clicked **Delete → OK**  
2. Refreshed the list to confirm removal  
3. Opened **Deleted users** to verify the account appeared there  
4. Noted that deleted users remain recoverable for **30 days** before permanent deletion  

---

## 🔍 Findings
- Microsoft Entra ID allows centralized control over user lifecycle management  
- User creation and deletion updates may require a manual refresh  
- Password resets generate temporary credentials automatically  
- Revoking sessions is an effective immediate response during incidents  
- Deleted accounts remain recoverable for 30 days as a safety measure  

---

## 🧾 Lessons Learned
- Learned how to **create, modify, and delete users** in Microsoft Entra ID  
- Practiced **revoking access** and **resetting passwords**, simulating real security scenarios  
- Understood the importance of **identity lifecycle management** in cloud environments  
- Gained confidence navigating the **Azure Portal** and managing user identities  

---

## 📸 Screenshots

| # | Description | Screenshot |
|:-:|--------------|-------------|
| 1 | Entra ID Overview | ![Entra ID Overview](./screenshots/1-entra-id-overview.png) |
| 2 | Entra ID User Creation Page | [![Create User] [(img](https://github.com/Mikala-Troupe/Microsoft-Entra-ID-Lab/blob/main/Pasted%20image%2020251024171941.png?raw=true) |
| 3 | Created Users List | ![Created Users](./screenshots/3-created-users.png) |
| 4 | Updating User Properties | ![User Properties](./screenshots/4-update-properties.png) |
| 5 | Reset Password | ![Reset Password](./screenshots/5-reset-password.png) |
| 6 | Revoke Sessions | ![Revoke Sessions](./screenshots/6-revoke-sessions.png) |
| 7 | Deleted User | ![Deleted User](./screenshots/7-deleted-user.png) |
| 8 | Deleted Users List | ![Deleted Users List](./screenshots/8-deleted-users-list.png) |
---

## 👩🏽‍💻 Author
**Mikala Troupe**  
*Cybersecurity & Information Assurance Graduate | Aspiring Cloud Security Professional*

---

## 📜 License
This project is for **educational and lab practice purposes only**.  
Feel free to fork and adapt it for your own learning.
