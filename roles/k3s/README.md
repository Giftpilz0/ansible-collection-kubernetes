# Ansible - k3s

\=========

## Role Variables

______________________________________________________________________

| Variables | Type | Options | Defaults |
| --------- | ---- | ------- | -------- |
|           |      |         |          |

## Dependencies

______________________________________________________________________

## Example Playbook

______________________________________________________________________

### Basic

```
- name: Import k3s Role
  hosts: all
  roles:
    - role: giftpilz0.kubernetes.k3s
```

TODO:
Firewalld services

## Master Node Inbound

6443        | kube-apiserver          | from worker, api users
8472  | udp | flannel - vxlan backend | from master and worker

## etcd Node Inbound

2379        | etcd-client             | from master and worker
2380        | etcd-server             | from master and worker

## Worker Node Inbound

10250       | kubelet                 | from master
30000-32767 | kube-nodeport-services  | from external
8472  | udp | flannel - vxlan backend | from master and worker
