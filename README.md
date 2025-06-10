# 🔐 Ansible Automation – Apache Install & Package Updates

This beginner-friendly DevOps project uses Ansible to automate Linux VM configuration: update packages and install Apache.

## 🚀 Tools Used
- Ansible
- SSH
- YAML
- Linux VM (AWS EC2 or Local)

## 📁 Project Structure
- `inventory.ini` – Target VM info
- `ansible.cfg` – Ansible config
- `playbooks/update_system.yml` – Update packages
- `playbooks/install_apache.yml` – Install and start Apache

## 🛠️ Setup Instructions

1. Clone the repo  
2. Edit `inventory.ini` with your VM details  
3. Run:
   ```bash
   ansible-playbook playbooks/update_system.yml
   ansible-playbook playbooks/install_apache.yml

Visit http://<your-ip> in your browser to confirm Apache is working.
