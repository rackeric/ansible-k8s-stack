# ansible-k8s-stack
Ansible playbooks for k8s stack, haproxy, etcd, kubernetes

```
ansible-playbook -i hosts roles/client.yml 
ansible-playbook -i hosts roles/common.yml 
ansible-playbook -i hosts roles/haproxy.yml 
ansible-playbook -i hosts roles/etcd.yml
ansible-playbook -i hosts roles/k8s_master.yml
ansible-playbook -i hosts roles/k8s_worker.yml
```
