# Hey, I'm Yak 👋

Self-taught Linux and infrastructure engineer transitioning into **DevOps / SRE / Platform Engineering**. I build real things, operate them, troubleshoot them, and document everything — in my homelab and in production.

---

## 🧰 What I Work With

**OS & Systems**
Linux (RHEL/Ubuntu) · Bash · systemd · cron · ufw · networking fundamentals

**Containers & Orchestration**
Docker · Docker Compose · Kubernetes (CKA in progress) · Minikube

**Infrastructure as Code**
Terraform (HashiCorp Certified) · HCL · AWS

**Observability**
Prometheus · Grafana · cAdvisor · node-exporter · Alertmanager

**CI/CD & Delivery**
GitHub Actions · GHCR · Caddy · SSH hardening

**Other**
PostgreSQL · XMPP / Prosody · msmtp · Let's Encrypt · Node.js

---

## 📜 Certifications

| Cert | Status |
|------|--------|
| RHCSA (Red Hat Certified System Administrator) | ✅ Passed — 284/300 |
| HashiCorp Terraform Associate | ✅ Passed |
| CKA (Certified Kubernetes Administrator) | 🔄 In progress |

---

## 🗂️ Projects

| Repo | What It Is |
|------|-----------|
| [`pidupall-prod-infra`](https://github.com/Vilgosha/pidupall-prod-infra) | **Production deployment** — custom Next.js Dockerfile, Docker Compose + Caddy reverse proxy, GitHub Actions CI/CD pipeline publishing to GHCR, SSH hardening |
| [`monitoring-for-homelab`](https://github.com/Vilgosha/monitoring-for-homelab) | **Observability stack** — Prometheus + Grafana + cAdvisor + node-exporter via Docker Compose; includes custom dashboards (JSON), alert rules, and documented troubleshooting (Prometheus UID/permissions issue) |
| [`backup-solution-for-homelab`](https://github.com/Vilgosha/backup-solution-for-homelab) | **Backup automation** — cron-driven daily incremental + monthly full backups with auto-mount/unmount of backup HDD (ransomware mitigation), structured logging to `/var/log/`, email alerts via msmtp |
| [`terraform-aws-web-server`](https://github.com/Vilgosha/terraform-aws-web-server) | **IaC on AWS** — Terraform config provisioning an EC2 web server with `user_data.sh` bootstrap, security groups, and remote state |
| [`k8s-practice`](https://github.com/Vilgosha/k8s-practice) | **Kubernetes lab** — multi-container deployments on Minikube, inter-service communication, LoadBalancer and ClusterIP service patterns, Node.js workloads |
| [`prosody-setup`](https://github.com/Vilgosha/prosody-setup) | **Self-hosted XMPP server** — Prosody in Docker Compose with Caddy TLS termination, PostgreSQL on a separate volume, Let's Encrypt certs; documented version constraints and upstream limitations honestly |

---

## 🏠 Homelab

I run a self-managed **Ubuntu homelab** hosting containerised services and game servers (Minecraft, Factorio, Project Zomboid, and others). This is where the monitoring, backup, and self-hosted service projects live in production — real uptime, real incidents, real fixes.

---

## 🎯 Currently

- 📖 Preparing for the **CKA exam**
- 🏗️ Expanding my **DevOps / Platform Engineering portfolio**
- 🔍 Actively looking for **junior-to-mid DevOps / SRE / Platform Engineering roles**

---

## 📫 Get In Touch

Open to opportunities — feel free to explore the repos or reach out.
