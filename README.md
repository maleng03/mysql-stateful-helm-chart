# MySQL StatefulSet Helm Chart

Production-style Helm chart for deploying MySQL 8 on Kubernetes using:

- StatefulSet
- Headless Service
- PersistentVolumeClaims
- Kubernetes Secrets

## Features

- Persistent storage with volumeClaimTemplates
- Secure credential management via Secrets
- Stable DNS using headless Service
- Helm templating for flexible configuration

## Install

```bash
helm install mysql-db ./mysql-stateful