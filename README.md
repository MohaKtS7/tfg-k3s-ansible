# TFG - Automatización de Clúster K3s con Ansible

Este repositorio contiene los playbooks, configuraciones y scripts necesarios para desplegar y gestionar un clúster K3s automatizado mediante Ansible.

## Estructura
- `inventory/`: definición de nodos y variables.
- `playbooks/`: automatización de despliegues.
- `scripts/`: utilidades como copia de seguridad.
- `manifests/`: manifiestos Kubernetes opcionales.

## Requisitos
- Ansible
- Conexión SSH entre el nodo de control y las VMs
