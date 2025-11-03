# ⚙️ Ansible Playbooks Collection

Welcome to my **Ansible Playbooks Repository** 👋  
This repo contains a collection of **real-world automation playbooks** that I’ve created while learning and practicing **DevOps and Cloud Automation**.

Each playbook focuses on a different concept — from installing packages to configuring services and using handlers, variables, and roles.

---

## 📚 Contents

| No. | Playbook Name | Description |
|-----|----------------|-------------|
| 1️⃣ | `file_creation.yml` | create a new file on remote web servers with specific ownership and permissions |
| 2️⃣ | `handler_example.yml` | Demonstrates how to use handlers in Ansible — performs a specific action (like restarting a service) only when notified by a task that changes something |
| 3️⃣ | `install-package.yml` | playbook installs and configures essential packages like Git and Apache (httpd) on target web servers |
| 4️⃣ | `multipackage.yml` | This playbook installs multiple essential packages — Vim, Curl, and Unzip — on all managed hosts running Debian/Ubuntu |
| 5️⃣ | `os_condition.yml` | This playbook installs the Apache web server on both Ubuntu/Debian and RedHat/CentOS systems using conditional logic |
| 6️⃣ | `variable.yml` | This playbook demonstrates how to define and use variables in Ansible |
| 7️⃣ | `with_item.yml` | This playbook demonstrates how to use loops in Ansible to perform repetitive tasks efficiently |



## 🚀 How to Use

### 🔹 Prerequisites
- 🐧 Linux Control Node (Ubuntu/CentOS)
- 🧑‍💻 Ansible installed (`ansible --version`)
- 🔑 SSH access to managed hosts
- 🗂️ Inventory file containing your target servers

### 🔹Example `inventory.ini`:
```
[webservers]

192.168.1.10

192.168.1.11

```
- Run Any Playbook

- Use this command:
```
ansible-playbook -i inventory.ini playbook_name.yml
```
## 🧰 Tools & Technologies Used

⚙️ Ansible – Automation & Configuration Management

🐧 Linux – Target system environment

☁️ AWS EC2 / Cloud VMs – For testing and deployment

💾 Git & GitHub – Version control

## 🧠 Learning Focus

This repository demonstrates:

✅ Writing modular and reusable playbooks

✅ Using variables, handlers, loops, and conditionals

✅ Managing configuration files remotely

✅ Practicing DevOps automation workflows


### 👨‍💻 Author
#### Aniket Dnyaneshwar Kolhe

🎓 B.Tech. Computer Science & Engineering

☁️ AWS Cloud Practitioner | DevOps Engineer (Fresher)

📍 Pune, Maharashtra

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/aniket1701)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/aniket-kolhe-027111253)



#### ⭐ If you find these playbooks helpful, don’t forget to star the repo and follow for more DevOps projects!
