Project Chart Helm Chart
This Helm chart deploys a Kubernetes application using Helm, with the following components:

Deployment: Manages the application deployment.
Service: Exposes the application within the Kubernetes cluster.
ConfigMap: Stores configuration data for the application.


Prerequisites
Kubernetes cluster
Helm installed (v3.x)

To install the Helm chart, run the following command:

helm install project-chart ./project-chart -f values.yaml

Configuration:
The following table lists the configurable parameters and their default values.

Number of replicas for Deployment	1
List of containers:	See values.yaml
ConfigMap data	See values.yaml
For detailed configuration options, refer to the values.yaml file.

ConfigMap Configuration
The ConfigMap in this Helm chart allows you to customize the configuration of your application. Below are the configurable parameters under configmap in values.yaml:

key1: Description of key1 (default: value1).
key2: Description of key2 (default: value2).
Modify these values in the values.yaml file according to your application's requirements.
