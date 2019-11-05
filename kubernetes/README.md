# Kubernetes

Manage applications that are containerized within isolated processes (like Docker or rkt.) Borg rewrite in the open that manages a cluster of machines to schedule containers on those different machines. It enables service discovery so that the various services made out of the containers can find each other. Basically manage your distributed application in a very automated manner.

## Resources

- [Kubernetes home](https://kubernetes.io)
- [Cloud Native Computing Foundation](https://www.cncf.io/)

## Architecture

Head Node is the brains of Kubernetes and contains:
- API server
- Scheduler
- Controller manager
- Etcd
- kubelet
- Container engine

Worker Node
- kubelet
- kube-proxy
- Container engine

## Getting started
