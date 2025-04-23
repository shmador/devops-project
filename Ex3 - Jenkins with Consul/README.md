# How to Use - Jenkins and Nginx Setup

1. Run the following to start the services:

```bash
docker-compose up
```

2. Access `localhost:8080` and create a new Jenkins pipeline using the `Jenkinsfile` in this directory  
   Set up a build parameter named `PORT` and trigger a build

3. Run the Ansible playbook:

```bash
ansible-playbook -i inventory.ini playbook.yaml
```

Now there should be an Nginx server running on the specified port on the remote machine

