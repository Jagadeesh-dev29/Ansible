# start Ansible in loacal server
   ansible-palybook -i inventory.ini <playbook -name>
# To run Ansible in local server we need to give
      hosts : local
      connection :local
# giving sudo access in Ansible to install packages
      become:yes
     