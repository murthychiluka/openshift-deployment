# FULLSTACK-DEPLOYMENT
#  change the namespace and git urls  according to your project

This directory contains deployment configurations for the full stack application.

## Files
- `build.yaml`: Build pipeline configuration for the application.
- `dc.yaml`: deployment configuration file.

## Usage
Use these files to build and deploy the full stack application. Refer to your CI/CD or orchestration tool documentation for details.

Run the commands one by one 
```
oc apply -f build.yaml
```
```
oc start-build flask-build --follow
```

```
oc apply -f dc.yaml

```
