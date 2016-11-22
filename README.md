mosh
====


What is does this role do?
--------------------------

This role installs the mosh server role and configures the firewall for use with mosh.  Mosh is a layer that works on top of ssh to provide support for roaming devices that may not maintain the same IP and may stay disconnected for extended periods of time.


Meta
----

Files Managed:
  * /etc/iptables.d/mosh.rules

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)
  * [sshd](https://github.com/void-ansible-roles/sshd)
