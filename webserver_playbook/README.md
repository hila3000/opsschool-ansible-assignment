To run the playbook-

1. make sure you have hosts file with this content in the root directory of ansible:
[web]
server1_ip_or_name

2. run this command-
ansible-playbook -i hosts --key-file /root/.ssh/relevant_key.pem webserver_playbook/webserver_setup.yml -u centos
