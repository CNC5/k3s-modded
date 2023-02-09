# k3s-modded (W.I.P.)
k3s + prometheus + gitlab runner + argocd + custom ingress; deployed by ansible

# brief
* site.yaml deploys everything
* reset.yaml destroys everything
* soft-reset.yaml destroys all deployments

# todo list
(setup - bare metal install)
- [ ] deployment  - gitlab-runner
- [ ] switch      - nginx -> openresty
- [x] setup       - k3s, traefik disabled
- [x] setup       - prometheus
- [x] deployment  - argocd
- [x] deployment  - nginx ingress
