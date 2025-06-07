# Ansible NGINX Playbook

Ce projet déploie et démarre automatiquement un serveur NGINX sur une machine locale via Ansible.

## Objectifs

- Installer NGINX via Ansible
- Démarrer NGINX
- Activer NGINX au démarrage de la machine
- Rendre NGINX accessible sur le port 80 (`http://localhost`)

## Prérequis

- Ansible installé :
`sudo apt update`
`sudo apt install ansible -y`

- Système Debian/Ubuntu (testé sur Ubuntu 20.04+)

## Exécution

```bash
ansible-playbook -i inventory nginx.yml

# Instructions

- 1 Cloner ce repository
`git clone https://github.com/vidaloi/ansible-nginx-playbook.git `
`cd ansible-nginx-playbook`

- 2 Lancer le playbook Ansible
`ansible-playbook -i inventory nginx.yml`

