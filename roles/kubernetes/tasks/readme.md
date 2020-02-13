# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "kubernetes"
Einrichten des Kubernetes-Clusters (master und node) via k3s, rke, kubeadm oder minikube

## Verzeichnis "tasks"
Playbook-Tasks, welche in der Rolle durchgeführt werden

## Files:
* cleanup/k3s-cleanup.yml:
* cleanup/kubeadm-cleanup.yml:
* cleanup/main.yml:
* cleanup/minikube-cleanup.yml:
* cleanup/rke-cleanup.yml:
* initial/initial-host.yml:
* initial/initial-install_helm.yml:
* initial/initial-install_software.yml:
* initial/main.yml:
* k3s/k3s-create_user.yml:
* k3s/k3s-download.yml:
* k3s/k3s-master.yml:
* k3s/k3s-node.yml:
* k3s/main.yml:
* kubeadm/kubeadm-create_user.yml:
* kubeadm/kubeadm-master.yml:
* kubeadm/kubeadm-node.yml:
* kubeadm/kubeadm-postinstall.yml:
* kubeadm/kubeadm-user_setup.yml:
* kubeadm/main.yml:
* main.yml:
* minikube/main.yml:
* postinstall/main.yml:
* rke/main.yml:
* rke/rke-create_config.yml:
* rke/rke-create_user.yml:
* rke/rke-download.yml:
