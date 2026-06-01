# Users and Permissions (Linux)

---

## 🎯 Objective
Learn basic user management in Ubuntu.

---

## 🧪 What I did

- Checked current user  
- Created a new user  
- Added user to sudo group  
- Verified permissions  

---

## 💻 Commands used

```bash id="cmdfinal2"
whoami
sudo adduser testuser
sudo usermod -aG sudo testuser
groups testuser
