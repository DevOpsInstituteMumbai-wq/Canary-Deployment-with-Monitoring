# Canary-Deployment-with-Monitoring

Objective: Implement a canary deployment for a microservice and monitor metrics using Prometheus/Grafana.
Tasks:
1.	Canary Setup:
o	Deploy two versions of an app (v1 and v2) with a 80/20 traffic split.
o	Use Deployment and Service for each version.
2.	Traffic Management:
o	Configure Ingress (e.g., Nginx) to split traffic between versions.
3.	Monitoring:
o	Deploy Prometheus and Grafana using Helm.
o	Create a dashboard to track request rates and pod health.
4.	Auto-Scaling:
o	Configure Horizontal Pod Autoscaler (HPA) for the app.

