# Lab 1 – Linux SSH, Users, Groups, and Secure Directory Access

This lab demonstrates the setup of a basic Linux server with SSH, user/group management, and directory access control.

## 🧾 Overview

- Updated system packages
- Installed and verified SSH server
- Created new users and groups
- Assigned permissions and verified secure access

## 🛠 Tools Used

- Debian 12 (VirtualBox VM)
- Terminal
- SSH
- Built-in Linux user/group utilities

## 📸 Screenshots

| Step | Description                                 | Screenshot |
|------|---------------------------------------------|------------|
| 1    | Update & Upgrade packages                   | ![01](screenshots/01_apt-update-upgrade.png) |
| 2    | Install OpenSSH Server                      | ![02](screenshots/02_install-ssh-server.png) |
| 3    | Verify SSH service status (clean output)    | ![03](screenshots/03_ssh-status-clean.png) |
| 4    | Add new user: `adminuser`                   | ![04](screenshots/04_add-adminuser.png) |
| 5    | Add new user: `testuser`                    | ![05](screenshots/05_add-testuser.png) |
| 6    | Add `adminuser` to `admins` group           | ![06](screenshots/06_group-admins-added.png) |
| 7    | Confirm access rights for `/secure-data`    | ![08](screenshots/08_secure-data-rights-confirmed.png) |
| 8    | Final check: SSH service is running         | ![09](screenshots/09_ssh-service-active.png) |

---

📁 All screenshots are located in the `screenshots/` folder.
