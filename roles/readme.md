# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rollen:
* common: Standard-Einrichtungsschritte für jeden Host
* development: Einrichten der Hosts mit Entwickler-Tools und Verzeichnissen
* jumphost: Einrichten des Jump-Hosts
* kubernetes: Einrichten des Kubernetes-Clusters (master und node) via k3s, rke, kubeadm oder minikube
* machinelearning: Einrichten der Hosts für Machinelearning-Tools (Google Coral, Intel NCS und nvidia Jetpack)
* statistics: Erheben statistischer Daten bei den Hosts
* system_update: System-Update, ausgegliedert da es beim Update via Ansible nahezu immer Probleme gibt
* worker: Einrichten eines Ansible-Workers (Single-Node-Setup)
