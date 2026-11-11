# Hi, I'm Francesco Cheema

**DevOps & Cloud Engineer** in Vancouver, BC. I build and operate infrastructure that keeps running when nobody is watching: CI/CD, containers, Kubernetes, infrastructure as code and observability on AWS.

**Certified:** CKA · AWS Solutions Architect – Associate · Terraform Associate · RHCSA · Azure Administrator (AZ-104)

## Featured projects

### [GroundsOps AI](https://github.com/FrancescoCheema/groundsops-ai-showcase): a SaaS I built and run

Landscaping companies photograph a yard, paint the area to change, and get an AI concept, a calibrated material estimate, a quote, a crew schedule and an invoice in one workspace.

- AWS infrastructure in Terraform (Cognito, S3, compute in ca-central-1)
- 8 GitHub Actions pipelines: tests, Playwright E2E, Trivy, Gitleaks and dependency audits, staging deploys, smoke tests
- Encrypted database backups with restore verification, systemd monitoring and AWS alarms
- Multi-tenant FastAPI + PostgreSQL backend, Next.js frontend, Stripe billing, 110 automated backend tests

### [Fleet GPS Monitoring](https://github.com/FrancescoCheema/Fleet-GPS-Monitoring): Kubernetes delivery pipeline

Two services deployed to kind and AWS-hosted K3s through a seven-stage Jenkins pipeline: image builds, Trivy scanning, cluster provisioning, secret injection, rollout validation and health checks. Terraform for EC2, IAM, ECR and S3 remote state; Prometheus, Grafana and Alertmanager for monitoring.

### More projects

| Project | What it shows |
| --- | --- |
| [Self-Healing EC2 Auto-Remediation](https://github.com/FrancescoCheema/Self-Healing-EC2-Auto-Remediation-System) | CloudWatch, Lambda, SNS and Auto Scaling replace unhealthy instances in under 60 seconds |
| [Real-Time GitOps Dashboard](https://github.com/FrancescoCheema/Real-time-Gitops-Dashboard) | GitHub webhooks turned into Prometheus metrics and Grafana dashboards |

## Toolbox

- **Cloud & IaC:** AWS · Azure · Terraform · CloudFormation · Ansible
- **Containers & delivery:** Docker · Kubernetes · K3s · Helm · GitHub Actions · Jenkins
- **Observability & security:** Prometheus · Grafana · CloudWatch · Trivy · Gitleaks
- **Systems & code:** Linux (RHEL) · Bash · Python · PowerShell · PostgreSQL

## Connect

[LinkedIn](https://www.linkedin.com/in/francesco-cheema-18959b227/) · Happy to talk DevOps, cloud and platform engineering.
