# MONITORING

This directory contains monitoring and observability configurations.

## Files
- `kibana-deploy.yaml`: Deployment configuration for Kibana (monitoring dashboard).

## Usage
Apply these files to your Kubernetes cluster or monitoring stack to deploy Kibana and related monitoring tools.

Apply command

```
oc apply -f kibana-deploy.yaml
```