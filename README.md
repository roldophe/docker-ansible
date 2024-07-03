# docker-ansible

Step 1: Use Ansible Ping Module to Check Hosts Communication
```bash
ansible all -m ping
```

Step 2: Install Docker Using Ansible Playbook
```bash
ansible-playbook install_docker.yaml
```

Step 3: SSH into EC2 Instance
```bash
ssh -i ~/.ssh/devops ubuntu@54.255.241.76
```

Step 4: Check Python Packages Installed for Docker
```
python3 -m pip list | grep docker
```