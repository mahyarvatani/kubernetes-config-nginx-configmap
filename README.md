# Kubernetes Nginx Deployment Project

## Overview

This Kubernetes project automates the deployment of an Nginx pod with a service and ingress. The Nginx web server is configured using two ConfigMaps, allowing for flexible and dynamic configuration management.

## Prerequisites

Before using this Kubernetes configuration, make sure you have the following prerequisites:

1. A running Kubernetes cluster.
2. `kubectl` installed and configured to communicate with your Kubernetes cluster.

## Project Structure

```plaintext
.
├── k8s/
│   ├── configmaps/
│   │   ├── cm1.yaml
│   │   └── cm2.yaml
│   ├── deployments/
│   │   └── pod1.yaml
│   ├── services/
│   │   └── service-nodeport.yaml
│   └── ingress/
│       └── ingress.yaml
├── README.md
└── .gitignore
