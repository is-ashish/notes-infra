notes-infra/
│── .github/workflows/    # CI/CD pipeline for Kubernetes deployments
│── environments/
│   │── dev/              # Dev environment configs
│   │── staging/          # Staging environment configs
│   │── prod/             # Production configs
│── manifests/            # Kubernetes YAML files
│   │── deployment.yml    # K8s Deployment config
│   │── service.yml       # K8s Service config
│   │── ingress.yml       # Ingress routing config
│   │── hpa.yml           # Auto-scaling settings (Horizontal Pod Autoscaler)
│── scripts/              # Deployment automation scripts
│── Terraform/            # Infrastructure provisioning (if using Terraform)
│── Helm/                 # Helm charts for K8s packaging (if using Helm)
│── README.md             # Infrastructure documentation

