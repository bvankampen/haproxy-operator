# Hackweek 2024 Project

## Description

Build an operator which configures an external HAProxy load balancer with the right ip's of the nodes so k8s and/or workload traffic routed automatically. When you add or remove a node (or the IP changes) the HAProxy config will be updated.

## Goals

- Build an operator which manages an external HAProxy load balancer
- To learn more about creating operators for Kubernetes.
- Lean more about Go
