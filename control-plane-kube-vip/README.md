# K8S Control Plane with Kube-Vip

## Description

Ansible Role for setup K8s control plane HA with the [kube-vip](https://kube-vip.chipzoller.dev/docs/) solution.\
This Ansible Role use kube-vip as a [Static Pods](https://kube-vip.chipzoller.dev/docs/installation/static/) and [Flannel](https://github.com/flannel-io/flannel#flannel) as a CNI.

> This Role should be used in Bare Metal/On-premise environments

## Requirements

- you need [ansible up and running](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).
- Setup your [inventory file](https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html).
- Configure the variable files in vars/

## Steps

1. Clone repo:
```
git clone
```
3. Running playbook
```
sudo ansible-playbook -i [INVENTORY FILE]  control-plane-vip-playbook.yaml
```
