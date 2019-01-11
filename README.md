# opsschool-ansible-assignment
1 playbook that deploys common role + db and webservers role (yes, on same server.. it's just a POC), as part of Ansible session #2 homework assignment


How to run the playbook?
1. git clone https://github.com/hila3000/opsschool-ansible-assignment
2. cd opsschool-ansible-assignment
1. edit the hosts file to include server/s.
2. run this command (from the root folder of opsschool-ansible-assignment):
ansible-playbook --key-file path_to_your_key_file -i hosts playbooks/db_with_web.yml -e hosts_group=db