# Ansible + k3s Lab

Este repositorio contiene playbooks de Ansible para:
- Configurar servidores
- Instalar k3s en modo HA (multi-master)
- Desplegar aplicaciones en Kubernetes

## Requisitos
- Oracle Linux 9
- Python 3.12
- Ansible
- Acceso SSH a los nodos

## Estructura
- `playbook/` → playbooks Ansible
- `inventario/` → inventarios de ejemplo  

## Uso
```bash
source venv/bin/activate
ansible-playbook playbook/k3s-install.yaml
ansible-playbook playbook/k3s-config.yaml

