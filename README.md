# k3s-modded (W.I.P.)
k3s + prometheus + helm + gitlab runner + argocd + custom ingress; deployed by ansible

# brief
* site.yaml deploys everything
* reset.yaml destroys everything
* soft-reset.yaml destroys all deployments
* hosts config is in inventory/master/hosts.ini
* misc config is in inventory/master/group_vars/all.yaml

# todo list
(setup - bare metal install)
- [ ] deployment  - gitlab-runner
- [ ] switch      - nginx -> openresty
- [x] setup       - k3s, traefik disabled
- [x] setup       - prometheus
- [x] setup       - helm
- [x] deployment  - argocd
- [x] deployment  - nginx ingress
