# Mimir Helm Chart

This repository contains a Helm chart for deploying **Grafana Mimir** in monolithic mode along with other components like **Nginx**, **Grafana**, **Minio**, and **Prometheus**. This chart simplifies the deployment of a scalable, observability solution on Kubernetes.

## Components Deployed

- **Grafana Mimir (Monolithic Mode)**: A highly available time-series database for storing and querying large volumes of metrics.
- **Nginx**: A reverse proxy for handling requests and load balancing.
- **Grafana**: A tool for visualizing time-series data.
- **Minio**: Object storage compatible with S3, used for storing Grafana Mimir’s long-term storage.
- **Prometheus**: A monitoring system that collects metrics from various systems.

## Prerequisites

- **Helm 3.x**: You will need Helm to deploy the chart.
- **Kubernetes 1.16+**: Kubernetes cluster to deploy the components.
- **Kubectl**: CLI for interacting with your Kubernetes cluster.

## Installation

The blog here explains the process of using this helm chart as a demo.
https://medium.com/@kedarnath93/grafana-mimir-as-a-long-term-storage-for-prometheus-metrics-part-2-2e7561977335
