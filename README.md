
## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) zabbix-server

This role installs [Zabbix](http://www.zabbix.com/), an Open Source
monitoring service.  `debops.zabbix_server`

### Documentation

coming soon

### Role dependencies

- `debops.etc_services`
- `debops.nginx`
- `debops.mysql`
- `debops.secret`
- `debops.postgresql`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.


### Authors and license

`zabbix_server` role was written by:
- Kim Rasmussen | [e-mail](mailto:mail@khh.nu) | [GitHub](https://github.com/xorgic)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)
