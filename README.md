# Zabbix agents mass install with Ansible (CentOs)
This is a simple playbook for mass installing zabbix agents with ansible. 
Proxy and firewall options are provided.

### Guides
1. In zabbix-agents.yml replace everything related to proxy  with your settings or if internet is available directly, comment it out.
2. In zabbix_agentd.conf replace Server=<your zabbix-server address> . You may want to use Active agent: replace  ServerActive=<your zabbix-server address>  then.
  
<b>Userful links<b>
  * [Complete installation options](https://www.zabbix.com/download?zabbix=5.0&os_distribution=centos&os_version=7&db=postgresql&ws=nginx)
  * [Tunning zabbix-server processes](https://blog.zabbix.com/monitoring-how-busy-zabbix-processes-are/457/  )
  * [Solving DB issues of zabbix-server version 5](https://bestmonitoringtools.com/upgrade-zabbix-to-the-latest-version/#Step_6_Patch_DB_and_fix_warning_database_is_not_upgraded_to_use_double_precision_values)
  * [Easy solution for SELinux issues !](https://www.zabbix.com/forum/zabbix-help/367261-selinux-and-zabbix )



