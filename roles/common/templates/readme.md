# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "common"
Standard-Einrichtungsschritte für jeden Host

## Verzeichnis "templates"
Jinja2-Templates, welche von der Rolle benötigt werden könnten

## Templates:
* avahi/sftp-ssh.service.j2:
* avahi/ssh.service.j2:
* hostfile/hosts-all.j2:
* hostfile/hosts-serveNet.j2:
* hostfile/hosts.j2:
* network/30-ansible.cfg.j2:
* network/35-serveNet-ansible.cfg.j2:
* network/dhcpcd.exit-hook.j2:
* network/wpa_supplicant.conf.j2:
