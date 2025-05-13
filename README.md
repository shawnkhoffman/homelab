# 🏠 Shawn Hoffman's Homelab

This repository contains the full declarative configuration for my personal homelab. It's built on a foundation of GitOps and Infrastructure-as-Code (IaC), using **Proxmox**, **Kubernetes**, **ArgoCD**, **Terraform**, and **Ansible** to manage compute, storage, networking, and services in a secure, scalable, and automated way.

---

## 🔧 Tech Stack

| Layer           | Tools Used                          |
|----------------|--------------------------------------|
| Hosting       | [Proxmox](https://www.proxmox.com/en/) |
| Automation     | [GitHub Actions](https://github.com/features/actions) |
| CI Runners     | [actions-runner-controller](https://github.com/actions/actions-runner-controller) |
| Provisioning   | [Terraform](https://www.terraform.io/) with [Proxmox provider by bpg](https://github.com/bpg/terraform-provider-proxmox), [cloud-init](https://cloudinit.readthedocs.io/en/latest/), and [Ansible](https://www.ansible.com/) |
| Cluster Mgmt   | [Kubernetes](https://kubernetes.io/) |
| GitOps         | [ArgoCD](https://argo-cd.readthedocs.io/) |
| Storage        | ZFS + [OpenEBS ZFS-LocalPV](https://github.com/openebs/zfs-localpv) |
| Networking     | [MetalLB](https://metallb.io/), [Tailscale](https://tailscale.com/) |
| Secrets Mgmt   | [HashiCorp Vault](https://hashicorp.com/vault), [GitHub Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets), [SOPS](https://github.com/mozilla/sops) |
| Monitoring     | [Grafana](https://grafana.com/), [Prometheus](https://prometheus.io/) |

---
