# Metal

- Assumes:
  - That OS (Rocky Linux) is already provisioned on the servers
  - That the localhost can ssh to the servers
- Ansible builds k3s cluster
- Ansible then sets up metallb in the cluster
