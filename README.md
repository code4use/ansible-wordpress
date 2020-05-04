[Install Wordpress on a Ubuntu 16.04 VPS with Ansible](https://www.0xadf.com/jekyll/update/2017/08/09/wordpress-ansible.html)

Alex Foster 2017

ansible-playbook -i hosts install.yml --extra-vars "webmaster_password=$STRONG_PASSWORD domain_name=$DOMAIN database_user=$DB_USER database_password=$ANOTHER_PASSWORD"

This playbook also creates user named "webmaster" on target systems.
