# 🛠️ Ansible NGINX Playbook

Ce projet déploie et démarre automatiquement un serveur NGINX sur une machine locale via Ansible.

## Objectifs

- Installer NGINX via Ansible
- Démarrer NGINX
- Activer NGINX au démarrage de la machine
- Rendre NGINX accessible sur le port 80 (`http://localhost`)

## Prérequis

- Ansible installé
- Système Debian/Ubuntu (testé sur Ubuntu 20.04+)

## Exécution

```bash
ansible-playbook -i inventory nginx.yml
