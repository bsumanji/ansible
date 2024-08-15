---
- hosts: kubernetes

  vars_files:
    - roles/kubernetes-cluster-setup/vars/hosts_entries.yml
  roles:
    - kubernetes-cluster-setup


