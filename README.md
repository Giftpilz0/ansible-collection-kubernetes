# Kubernetes Collection

![Ansible-Lint](https://github.com/giftpilz0/ansible-collection-kubernetes/actions/workflows/ci.yml/badge.svg)

Ansible Collection to configure and install a k3s cluster on multiple Linux systems.

Complete documentation:
<https://giftpilz0.github.io/docs/projects/ansible/kubernetes/>

______________________________________________________________________

## Installation

`ansible-galaxy collection install git+https://github.com/Giftpilz0/ansible-collection-kubernetes.git`

## Included Roles

- [cilium](cilium/)
- [fluxcli](fluxcli/)
- [helm](helm/)
- [k3s](k3s/)
- [k9s](k9s/)

## Requirements

- Fedora >= 38

## Thanks

Many parts of the **k3s** role are heavily based on [k3s-io/k3s-ansible](https://github.com/k3s-io/k3s-ansible)
