# Nexoryx_MLOps_Platform

Production-ready MLOps platform for Kubernetes with:

- Apache Airflow
- MLflow
- MinIO
- PostgreSQL
- Redis
- Spark
- JupyterHub
- Prometheus
- Grafana
- NGINX Ingress

## Features

- Kubernetes-native architecture
- MLflow tracking server
- Airflow workflow orchestration
- Spark job execution
- Object storage using MinIO
- Monitoring with Prometheus and Grafana
- Persistent storage
- Horizontal scaling
- Ingress-based routing
- Secrets management
- Production-ready manifests

## Stack

- Kubernetes
- Docker
- Apache Airflow
- MLflow
- Apache Spark
- PostgreSQL
- Redis
- MinIO
- JupyterHub
- Grafana
- Prometheus

## Deploy

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-mlops
```

## Components

- airflow-webserver
- airflow-scheduler
- mlflow
- spark-master
- spark-workers
- postgres
- redis
- minio
- grafana
- prometheus

## Notes

Update passwords, ingress domains, and storage classes before production deployment.
