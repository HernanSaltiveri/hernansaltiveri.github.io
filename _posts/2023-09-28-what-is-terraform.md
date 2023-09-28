---
date: 2018-11-22 12:26:40
layout: post
title: What is Terraform?
subtitle: Why is so important to use?
description: Terraform is an open-source **infrastructure as code (IaC)** tool developed by HashiCorp. 
#image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559822138/theme9_v273a9.jpg
#image: https://imag.malavida.com/mvimgbig/download-fs/drawboard-pdf-15322-5.jpg
#image: https://media2.giphy.com/media/l1IY2AbVzZ6f7tGQo/giphy.gif?cid=ecf05e47c46f4c993306fa86540461d15f358257b387d43f&rid=giphy.gif
#image: https://media0.giphy.com/media/BCs20EzQnYRXi/giphy.gif?cid=ecf05e47f232b1b79d83818de57145545e1c0893e38473eb&rid=giphy.gif
image: https://lh5.googleusercontent.com/KMZupO9bRik3N9G_M1u1zSuAwlu2H41gm8oh3fixa6QSMUCTQRFlO41KzYRzrxtqjRjqKsNPyalUiLQ-1Caj0KEE4FUt8v_kFhHkvGOUBQvi4cji29htbCjNPW0M0p_UokAtjwGe
optimized_image: https://lh5.googleusercontent.com/KMZupO9bRik3N9G_M1u1zSuAwlu2H41gm8oh3fixa6QSMUCTQRFlO41KzYRzrxtqjRjqKsNPyalUiLQ-1Caj0KEE4FUt8v_kFhHkvGOUBQvi4cji29htbCjNPW0M0p_UokAtjwGe
category: DevOpss
tags:
  - books
  - read
author: hernansaltiveri
paginate: true
---

# Terraform

Terraform is an open-source **infrastructure as code (IaC)** tool developed by HashiCorp. It enables users to define and provision infrastructure resources, such as virtual machines, networks, storage, and more, in a declarative and version-controlled manner. Terraform simplifies the process of managing infrastructure by allowing you to describe your requirements using a human-readable configuration language and automating the creation and management of resources across various cloud providers and on-premises environments.

## Key Features and Concepts

1. **Declarative Configuration:** Terraform uses a domain-specific language (DSL) to define infrastructure as code. You declare the desired resources and their configurations, without specifying the step-by-step process to create them.

2. **Providers:** Terraform supports a wide range of cloud providers (e.g., AWS, Azure, Google Cloud) and on-premises infrastructure (e.g., VMware, OpenStack). Each provider has its set of resource types that Terraform can manage.

3. **Resources:** Resources are the infrastructure components defined in your Terraform configuration, such as virtual machines, databases, network subnets, and more. Terraform can create, update, or delete these resources to match your configuration.

4. **State Management:** Terraform maintains a state file that tracks the real-world resources it has created and their current states. This state helps Terraform understand resource relationships and manage updates and changes.

5. **Plan and Apply:** Terraform operates in a two-step process. First, you use `terraform plan` to preview infrastructure changes without applying them. Then, you use `terraform apply` to execute the changes when satisfied with the plan.

6. **Modularity and Reusability:** Terraform configurations can be modularized and reused, simplifying the management and scaling of infrastructure. Modules provide reusable building blocks for infrastructure components.

7. **Version Control:** Terraform configurations can be stored in version control systems (e.g., Git) to track changes, collaborate with team members, and maintain a history of infrastructure modifications.

Terraform is widely adopted in DevOps and cloud-native environments because it offers a consistent and automated approach to infrastructure management. It leverages infrastructure as code principles, providing repeatability, scalability, and the ability to automate infrastructure provisioning and updates. This contributes to increased operational efficiency and reliability.
