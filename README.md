Objetivo é criar e implantar uma aplicação em um ambiente Kubernetes na AWS, configurando um pipeline CI/CD no GitHub Actions, além de implementar monitoramento e observabilidade.

Desafio
Criar um ambiente Kubernetes na AWS:


Utilizar EKS (ou k3s/k3d localmente caso não tenha acesso à AWS).
Criar um Deployment para rodar um Hello World API (pode ser um simples app em Node.js, Python ou Java).
Criar um Service para expor a aplicação.
Criar um Ingress para permitir acesso externo.
Configurar um pipeline CI/CD no GitHub Actions para:


Buildar a aplicação.
Criar uma imagem Docker e publicá-la no Amazon ECR.
Deploy automatizado no Kubernetes via ArgoCD.
Implementar Monitoramento e Observabilidade:


Configurar Prometheus e Grafana para monitorar a aplicação.
Criar dashboards no Grafana com métricas básicas (uso de CPU, memória, requests).
Configurar Alertmanager para enviar alertas via e-mail ou webhook.
Garantir boas práticas de segurança:


Aplicar RBAC no Kubernetes.
Configurar IAM roles corretamente para acessar AWS EKS e ECR.
Configurar network policies para limitar o tráfego desnecessário.

Diferenciais (Extras que contam pontos)
✔ Configurar Auto Scaling baseado em métricas.
 ✔ Implementar Service Mesh com Istio ou Linkerd.
 ✔ Utilizar Terraform ou Helm para provisionamento.
 ✔ Criar logs estruturados e exportá-los para AWS CloudWatch.
 ✔ Criar uma pipeline de rollback em caso de falha no deploy.

Critérios de Avaliação
 ✅ Infraestrutura como Código (Helm/Terraform/Kustomize).
 ✅ Automação do pipeline CI/CD (GitHub Actions, ArgoCD).
 ✅ Monitoramento e Observabilidade (Prometheus/Grafana).
 ✅ Boas práticas de segurança (IAM, RBAC, Network Policies).
 ✅ Documentação clara e bem explicada.
