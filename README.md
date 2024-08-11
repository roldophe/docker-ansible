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
ssh -i ~/.ssh/devops ubuntu@54.169.175.160
```

Step 4: Check Python Packages Installed for Docker
```
python3 -m pip list | grep docker
```


Step 5: Install Portainer Using Ansible Playbook
```bash
ansible-playbook install_portainer.yaml
```

Step 6: Install Wordpress Using Ansible Playbook
```bash
ansible-playbook install_wordpress.yaml
```

Step 7: Setup Traefik with Docker using Ansible
```bash
ansible-playbook traefik_setup.yml
```


Step 8: Deploy Traefik container
```bash
ansible-playbook deploy-traefik.yaml
```