memcached-zabbix-template
=========================

Description
-----------

This is a minimal template to get info from your Mecached server from two possible places. Via zabbix-agentd in clients or via externalscripts in zabbix server. Choose your option.

Monitoring information by now:

  * 'bytes',
  * 'cmd_get',
  * 'cmd_set',
  * 'curr_items',
  * 'curr_connections',
  * 'limit_maxbytes',
  * 'uptime',
  * 'get_hits',
  * 'get_misses',
  
  And the special HIT ratio in %:
  
  * 'ratio'
  
