# DEPRICATED, in favor of ansible-role-add_monitoring_services
# Ansible Playbook



## Purpose
  Execute this play against a supported server, it will add the InfluxData repository and key, then install Telegraf with apt-get (Debian based systems).
  
----

## Execution
<pre>
    ansible-playbook -e "remote_ssh_user=<b>user</b>" -e "play_hosts=<b>ALL</b>" add_ansible_user.yaml 
</pre>

----

## Notes

