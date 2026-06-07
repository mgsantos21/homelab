I'm building a fully GitOps-driven homelab running on **K3s** over bare-metal laptops, using modern DevOps tooling to simulate real production environments.

📌 Current architecture:
- **FluxCD** for GitOps deployments and reconciliation  
- **Helm** for templating and managing charts  
- **Prometheus + Grafana** for observability
- **Cloudflare** for DNS and secure public access  
- **Secrets management** with SOPS
