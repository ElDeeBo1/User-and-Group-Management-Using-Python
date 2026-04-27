#  Linux User Management Tool (Python)

A simple command-line Python tool to automate Linux user and group management using system administration commands.

---

##  Features

- Create new Linux users with passwords
- Modify existing users (username, groups)
- Delete users with home directory removal
- List all system users
- Create and delete groups
- Lock and unlock user accounts
- Change user passwords
- Interactive menu-driven CLI

---

##  Technologies Used

- Python 3
- Linux Shell Commands
- subprocess module

---

##  How It Works

The project executes Linux system commands such as:
- `useradd`
- `usermod`
- `userdel`
- `groupadd`
- `groupdel`
- `passwd`
- `chpasswd`

All commands are executed securely using Python’s `subprocess` module.

---

##  How to Run

```bash
python3 main.py
