ansible-galera-mariadb

[galera] create ansible playbooks for installing and configuring galera mariadb nodes

go to the roles/defaults folder and change this variable like you want to configure your nodes

1 - hostname

2 - mysql_user

3 - new_root_passwd

4 - mysql_old_root_password

5 - addresses

after changing this variables, now go to hosts file for configuring your inventory file .

now you can run the anisble playbook by using:

ansible-playbook -i hosts mariadb.yml

wait ansible finishing...

congratulation, now you have galera nodes configured
