# k3s-modded (W.I.P.)
k3s + prometheus + gitlab runner + argocd + custom ingress; deployed by ansible

# brief
* site.yaml deploys everything
* reset.yaml destroys everything
* soft-reset.yaml destroys all deployments

# done list
(setup - bare metal install)
setup       - k3s, traefik disabled
setup       - prometheus
deployment  - argocd
deployment  - nginx ingress


# todo list
deployment  - gitlab-runner
switch      - nginx -> openresty
