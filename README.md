# Stephen McCruden

Field Engineer II | Infrastructure Automation | Kubernetes & GitOps

I am a Field Engineer II at Motorola Solutions in the Washington,
D.C. area. I support mission-critical public-safety communications systems in
an environment where reliability, disciplined change control, careful
troubleshooting, and clear technical documentation matter.

Outside of work, I am developing those same principles through a reproducible
Kubernetes platform built on Proxmox. My focus is not simply deploying tools;
it is learning how to design, automate, observe, break, recover, and document a
complete system.

I am interested in SRE, DevOps, platform engineering, and cloud infrastructure
opportunities.

## Featured project

### [Reproducible Proxmox Kubernetes Homelab](https://github.com/Stephen-McCruden/homelab)

A three-node Kubernetes platform in which each layer has a defined source of
truth:

```text
Terraform -> Proxmox VMs -> Ansible -> Kubernetes -> Flux -> Applications
```

- Provisions Fedora Cloud virtual machines across a three-node Proxmox cluster
  with Terraform.
- Configures and hardens the nodes, container runtime, and Kubernetes cluster
  with idempotent Ansible roles.
- Uses kubeadm, containerd, Cilium, Flux, and Helm for a declarative platform
  lifecycle.
- Provides persistent storage through Longhorn and private HTTPS access through
  the Tailscale Operator.
- Manages certificates and secrets with cert-manager, SOPS, External Secrets,
  and Azure Key Vault.
- Collects metrics, logs, and Kubernetes events with Prometheus, Grafana, Loki,
  and Alloy.
- Delivers my portfolio site through GitHub Actions, GHCR, immutable image
  digests, and Flux image automation.
- Documents architecture, dependency ordering, deployment, operations,
  troubleshooting, and known limitations.

Current reliability work includes off-cluster backups, application restore
testing, full destroy-to-green rebuilds, and measured recovery objectives.

## Other work

- **[mccruden.com](https://mccruden.com)** — My infrastructure engineering
  portfolio and technical blog.
- **[Website source](https://github.com/Stephen-McCruden/mccruden.com)** — An
  Astro site packaged in an unprivileged NGINX container and delivered to
  Kubernetes through an automated preview and production workflow.

## Technologies

| Area | Tools and platforms |
| --- | --- |
| Infrastructure | Linux, Proxmox VE, Terraform, Ansible, HCP Terraform |
| Containers and orchestration | Kubernetes, kubeadm, containerd, Helm, Flux |
| Networking and access | Cilium, Traefik, MetalLB, Cloudflare, Tailscale |
| Security and secrets | cert-manager, SOPS, External Secrets, Azure Key Vault |
| Observability and storage | Prometheus, Grafana, Loki, Alloy, Longhorn |
| Automation and development | Git, GitHub Actions, Bash, Python, HCL, YAML |

I hold the CompTIA Network+ certification and am continuing to deepen my
Kubernetes, Linux, Python, cloud, and infrastructure-as-code skills.

## Engineering principles

- Automate repeatable work and make repeated execution safe.
- Keep one authoritative owner for each piece of infrastructure.
- Treat observability, recovery, and documentation as part of the system.
- Prefer durable fixes in code over undocumented production changes.
- Test failure and restoration instead of assuming resilience.

## Connect

- [Portfolio and technical blog](https://mccruden.com)
- [LinkedIn](https://www.linkedin.com/in/stephen-mccruden)
