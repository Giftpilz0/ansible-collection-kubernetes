# Kubernetes Collection

![Ansible-Lint](https://github.com/giftpilz0/ansible-collection-kubernetes/actions/workflows/ci.yml/badge.svg)

Ansible Collection to install a k3s cluster on multiple Linux systems.

Complete documentation:
<https://giftpilz0.github.io/projectdocs/ansible/kubernetes/>

______________________________________________________________________

## Installation

`ansible-galaxy collection install git+https://github.com/Giftpilz0/ansible-collection-kubernetes.git`

## Included Roles

- [k3s](k3s/)

## Requirements

- Fedora >= 38

## Thanks

Many parts of the **k3s** role are heavily based on [k3s-io/k3s-ansible](https://github.com/k3s-io/k3s-ansible)
