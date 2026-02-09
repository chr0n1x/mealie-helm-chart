# mealie-helm-chart

[github repo here](https://github.com/chr0n1x/mealie-helm-chart)

simple helm chart for [mealie](https://docs.mealie.io/)

wanted something with a transparent build/publish pipeline. so here we go. this entire repo/chart is released via public github actions.

# requirements

1. k8s
2. your own DB (I run [cnpg](https://cloudnative-pg.io/) for my own instances, and I wrap this chart)
3. your own ingress (I run traefik, but you can bring your own and hook into this deployment)

that's really it

To see how I wrap this chart with other bits of functionality, see [my wrapper chart in my homelab cluster git-ops repo](https://github.com/chr0n1x/rpi-talos/tree/main/k8s/argocd-deploy/mealie)
