---
date: 2018-11-22 12:26:40
layout: post
title: What is Kubernetes?
subtitle: Why is so important to use mlops approach
description: Kubernetes is an open-source container orchestration platform.
#image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559822138/theme9_v273a9.jpg
#image: https://imag.malavida.com/mvimgbig/download-fs/drawboard-pdf-15322-5.jpg
#image: https://media2.giphy.com/media/l1IY2AbVzZ6f7tGQo/giphy.gif?cid=ecf05e47c46f4c993306fa86540461d15f358257b387d43f&rid=giphy.gif
#image: https://media0.giphy.com/media/BCs20EzQnYRXi/giphy.gif?cid=ecf05e47f232b1b79d83818de57145545e1c0893e38473eb&rid=giphy.gif
image: https://d33wubrfki0l68.cloudfront.net/2475489eaf20163ec0f54ddc1d92aa8d4c87c96b/e7c81/images/docs/components-of-kubernetes.svg
optimized_image: https://d33wubrfki0l68.cloudfront.net/2475489eaf20163ec0f54ddc1d92aa8d4c87c96b/e7c81/images/docs/components-of-kubernetes.svg
category: Cloud
tags:
  - books
  - read
author: hernansaltiveri
paginate: true
---

# Kubernetes

**Kubernetes**, often abbreviated as **K8s** (due to 8 characters between 'K' and 's'), is an open-source container orchestration platform. Originally developed by Google and now maintained by the Cloud Native Computing Foundation (CNCF), Kubernetes automates the deployment, scaling, and management of containerized applications. It provides a robust framework for managing container workloads and services, enabling organizations to build and run scalable, resilient, and portable applications using containers.

## Key Features and Concepts

1. **Container Orchestration:** Kubernetes manages the deployment and scaling of containers, abstracting away the underlying infrastructure and providing a unified API for container management.

2. **Nodes:** Kubernetes clusters consist of nodes, which can be worker nodes (running containers) and control plane nodes (managing the cluster).

3. **Pods:** Pods are the smallest deployable units, containing one or more containers that share the same network namespace and are typically scheduled together on the same node.

4. **Replication and Scaling:** Kubernetes ensures a specified number of pod replicas are running at all times and can automatically scale based on metrics and policies.

5. **Services:** Kubernetes provides services for network communication between pods, offering stable, discoverable endpoints.

6. **Load Balancing:** Built-in load balancing distributes network traffic across multiple pods for high availability and load distribution.

7. **Storage Orchestration:** Kubernetes manages storage volumes and offers persistent storage for containers, dynamically provisioning and managing resources.

8. **Config and Secret Management:** Configuration data and secrets are managed separately from application code for security and flexibility.

9. **Health Checks and Self-healing:** Kubernetes monitors pod health and replaces or reschedules unhealthy pods automatically.

10. **Rolling Updates and Rollbacks:** Supports rolling updates without downtime and can perform rollbacks in case of issues.

11. **Declarative Configuration:** Users define the desired state using YAML or JSON configuration files, and Kubernetes reconciles the actual state with the desired state.

12. **Extensibility:** Kubernetes is highly extensible, with a rich ecosystem of plugins, extensions, and custom resources.

Kubernetes is widely adopted in cloud-native application development and container-based infrastructure. It simplifies container management, offering scalability, resilience, and automation. Kubernetes has become the standard for deploying and orchestrating containers in production environments, used by many organizations to build and manage modern, containerized applications.
