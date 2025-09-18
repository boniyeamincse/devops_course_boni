
# 📘 Course Outline: Prometheus – Infrastructure Monitoring

## Module 1: Introduction to Prometheus
- What is Prometheus?  
- Role of monitoring in DevOps  
- Prometheus architecture (TSDB, Exporters, Alertmanager, Grafana)  
- Installing Prometheus  

## Module 2: Prometheus Fundamentals
- Time-series data concepts  
- Metrics types (counter, gauge, histogram, summary)  
- PromQL basics (Prometheus Query Language)  
- Writing first queries  

## Module 3: Exporters & Integrations
- Node Exporter for system metrics  
- cAdvisor for container monitoring  
- Application exporters (MySQL, Redis, Nginx, etc.)  
- Writing custom exporters  

## Module 4: Prometheus Configuration
- prometheus.yml explained  
- Defining scrape configs  
- Relabeling and filtering targets  
- Service discovery (Kubernetes, Consul, EC2, etc.)  

## Module 5: Alerting with Prometheus
- Setting up Alertmanager  
- Writing alerting rules  
- Grouping, inhibition, and silencing alerts  
- Integrating with Slack, Email, PagerDuty  

## Module 6: Prometheus + Grafana
- Installing Grafana  
- Connecting Prometheus as a data source  
- Building dashboards for metrics visualization  
- Sharing and importing Grafana dashboards  

## Module 7: Prometheus in Kubernetes
- Monitoring Kubernetes clusters  
- kube-state-metrics and API server monitoring  
- Helm charts for Prometheus and Grafana  
- Prometheus Operator for Kubernetes  

## Module 8: Scaling & High Availability
- Prometheus federation  
- Remote storage options (Thanos, Cortex, VictoriaMetrics)  
- Sharding and scaling Prometheus  
- Best practices for HA setup  

## Module 9: Security & Optimization
- Securing Prometheus endpoints  
- Authentication and authorization strategies  
- Resource optimization and retention policies  
- Managing large-scale environments  

## Module 10: Hands-On Projects
- Monitoring a Linux server with Node Exporter + Prometheus + Grafana  
- Building dashboards for Docker containers  
- Kubernetes cluster monitoring with Prometheus Operator  
- Full alerting workflow: Prometheus → Alertmanager → Slack  
