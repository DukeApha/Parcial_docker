# Automatización de Servidor Web con Ansible y Docker

Este proyecto automatiza la configuración de servidores web utilizando Ansible y contenedores Docker.

## Tecnologías
- Ansible
- Docker
- Nginx

## Ejecución

```bash
docker-compose up -d
ansible-playbook -i inventory.ini playbook.yml
