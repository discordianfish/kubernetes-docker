# Kubernetes
There are two Docker images to get you started.

First you need to deploy [fish/kubernetes-node](kubernetes-node/) to
all Docker nodes in your cluster, then you can deploy
[fish/kubernetes-server](kubernetes-server/) and use
`cmd/cloudcfg/cloudcfg` to schedule your containers.
