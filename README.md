# Arunachalam K

Web application penetration tester in the making. I build things to understand how to break them.
Practicing on TryHackMe and HackTheBox. Studying through PortSwigger Web Security Academy.

## I code in
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![CSS](https://img.shields.io/badge/css-%23663399.svg?style=for-the-badge&logo=css&logoColor=white)

## Databases
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

## Pentesting Tools
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge)![Static Badge](https://img.shields.io/badge/Metasploit-%232596CD?style=for-the-badge&logo=metasploit&logoColor=white)![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
## Tools & Environment
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)![Parrot OS](https://img.shields.io/badge/Parrot_OS-15E0ED?style=for-the-badge&logo=parrotsecurity&logoColor=black)![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)![VirtualBox](https://img.shields.io/badge/virtualbox-%23183A61.svg?style=for-the-badge&logo=virtualbox&logoColor=white)![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)![tmux](https://img.shields.io/badge/tmux-%23000000?style=for-the-badge&logo=tmux&logoColor=%231BB91F)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)![Obsidian](https://img.shields.io/badge/Obsidian-%23483699.svg?style=for-the-badge&logo=obsidian&logoColor=white)![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Projects

### 🍯 HoneyTrap
A dual-protocol honeypot that emulates SSH and HTTP services to lure and log attacker activity.

- Fake SSH server built with **Paramiko** — emulates an Ubuntu shell, logs every credential attempt and command executed
- Fake HTTP login page built with **Flask** — captures IP addresses and submitted credentials
- Rotating file logs across three audit files: connection attempts, commands, and HTTP activity
- Fully **Dockerized** — runs both honeypots in parallel via a startup shell script, with log volume mounting for persistence

`Python` `Paramiko` `Flask` `Docker` `Threading` `Socket`

[→ View Repository](https://github.com/Arunachalam-1435/Honeytrap)

---

### 🔐 AuthLite
An intentionally vulnerable PHP authentication app — built to understand how auth systems work before attacking them.

- User registration and login with email and password
- Profile picture upload via JavaScript Fetch API
- Deliberately skips security best practices: no prepared statements, MD5 password hashing, no session regeneration, no server-side file validation
- Built to practice identifying SQLi, session fixation, and insecure file upload vulnerabilities in a controlled environment

`PHP` `PostgreSQL` `PDO` `JavaScript` `HTML`

[→ View Repository](https://github.com/Arunachalam-1435/AuthLite)

---

### 🔌 REST API
A RESTful API built from scratch in plain PHP to understand backend fundamentals before using frameworks.

- Full CRUD operations on a products resource across 5 endpoints
- MVC architecture with manual routing, controller, and model layers
- Used **MySQLi** instead of the tutorial's PDO — understanding the difference between abstraction layers mattered more than following instructions
- Tested entirely with **cURL**

`PHP` `MySQL` `MySQLi` `MVC` `REST` `cURL`

[→ View Repository](https://github.com/Arunachalam-1435/REST-API)

---

## Contact
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arunachalam1435/)
[![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/r0m3o_101)
