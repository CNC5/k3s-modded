# k3s-modded
k3s + prometheus + helm + argocd + custom ingress; deployed by ansible

# brief
* site.yaml deploys everything
* reset.yaml destroys everything
* soft-reset.yaml destroys all deployments
* hosts config is in inventory/master/hosts.ini
* misc config is in inventory/master/group_vars/all.yaml

# todo list
(setup - bare metal install)
- [x] setup       - k3s, traefik disabled
- [x] setup       - prometheus
- [x] setup       - helm
- [x] deployment  - argocd
- [x] deployment  - nginx ingress
