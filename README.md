# 🐧 Linux & Git Learning Journey

> **Status:** 🟢 Active Learning (Phase 2)
> 
> **Goal:** Building the foundation for Site Reliability Engineering (SRE).

This repository serves as my personal laboratory and documentation hub. Here, I document every Linux command, Git workflow, and Networking concept I master on my journey to becoming a Cloud Engineer.

---

## 🛠️ Tech Stack & Tools
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📚 Linux Command Cheat Sheet
*A log of essential commands I use daily in Ubuntu (WSL2).*

| Category | Command | Description |
| :--- | :--- | :--- |
| **Navigation** | `cd ~` | Go to Home directory |
| | `ls -la` | List all files (including hidden) |
| | `pwd` | Print Working Directory |
| **File Mgmt** | `touch file.txt` | Create an empty file |
| | `mkdir folder` | Create a new directory |
| | `rm -rf folder` | Remove directory (Force) |
| **System** | `top` | View active processes |
| | `df -h` | Check disk space usage |
| **Navigation** | `cd .. ` | Go back one folder level (up) |
| **Privilage**| `sudo <cmd>`|"SuperUser DO" - Run command as Root/Admin. |
| **File Mgmt**| `cp <file> <new>` | Copy a file to the new location/name. |
| **File Mgmt**| `rm <file>` | Removes(deletes) a specific file |
| **File Mgmt**| `cat <file>`| Read or Display the contents of the file |
| **File Mgmt**| 'less <file>` | Read the content of file in document form and read it page by page using arrow keys |
| **System**| `whoami` | Shows which user you are currently logged at |
| **System**| `which` <cmd> |Shows the path where program is installed |
| **System**| `clear` | Clears the terminal screen |
| **System**| `history` | Shows the list of commands that we have written , linux almost remembers past 1000 commands |
---

## 🐙 Git Workflow
*The SRE standard workflow for version control.*

```bash
# 1. Start a new feature
git checkout -b feature-name

# 2. Save work
git add .
git commit -m "Added new feature"

# 3. Upload to Cloud
git push origin feature-name
```
## 🗺️ The Roadmap

### 🟢 Phase 1: The Foundation (Current)
- [x] **Week 1:** Setup & Configuration (WSL2 + Git)
- [X] **Week 2:** 🐧 **Linux Deep Dive** (Permissions & File Systems)
- [X] **Week 3:** 🌐 **Computer Networking** (The language of the cloud)
- [X] **Week 4:** 🤖 **Basic Automation** (Bash Scripting)

### 🟡 Phase 2: The Logic (Upcoming - Jan 2026)
- [X] 🐍 **Python for DevOps**
- [ ] 🧠 **SRE-Focused DSA** (Logs, Parsing, Automation logic)

### 🔵 Phase 3: The Cloud (Upcoming)
- [ ] ☁️ **AWS Essentials**
- [ ] 🐳 **Docker & Containers**

## So far:
* Linux: Strengthening command line proficiency and kernel understanding(permissions , file systems).
* python: Initialized the `python-practice` repository to document automation scripts and logic.[repository][https://github.com/KarthikShetty23/python-practice]
* Networking: Building foundational knowledge in OSI model and TCP/IP.
