# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "kubernetes"
Einrichten des Kubernetes-Clusters (master und node) via k3s, rke, kubeadm oder minikube

## Verzeichnis "templates"
Jinja2-Templates, welche von der Rolle benötigt werden könnten

## Templates:
* k3s/k3s.service.master.j2:
* k3s/k3s.service.node.j2:
* rke/cluster.bak.yml.j2:
* rke/cluster.yml.j2:
