# Awesome-Infrastructure-As-Code-IaC

## Top Infrastructure as Code (IaC) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Declarative Provisioning, GitOps Workflows & Self-Hosted IaC Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial IaC platforms** and **open-source projects** that provision and manage cloud infrastructure through declarative code — from multi-cloud provisioning engines to policy-as-code enforcement and GitOps-driven deployment pipelines.



**Examples** include AWS CloudFormation, Terraform Cloud, Pulumi, Spacelift, OpenTofu, Crossplane, env0, Scalr, Terragrunt, and SaltStack Cloud (the category leaders).



**Open-source emphasis**: Infrastructure as Code is one of the strongest open-source domains. **Terraform** and **OpenTofu** lead as the de facto IaC standards with 44K and 26K+ GitHub stars respectively . **Pulumi** brings real programming languages to IaC with 23K+ stars . **Crossplane** delivers Kubernetes-native cloud resource management . **Terragrunt** and **Terramate** orchestrate Terraform across accounts and environments . **Ansible** and **Chef** handle configuration management, while **Packer** builds machine images . **Atlantis** and **Digger** enable PR-based Terraform workflows . **Open Policy Agent** enforces policy-as-code . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Terraform Cloud](https://www.terraform.io/cloud)**  

  **HashiCorp's managed IaC platform** — remote state, collaboration, policy enforcement, and CI/CD integration . **The most widely used commercial IaC platform** . **Best for enterprise Terraform governance** .



- **[Pulumi Cloud](https://www.pulumi.com/)**  

  **Managed IaC with real programming languages** — TypeScript, Python, Go, .NET, Java . **Best for developer-centric IaC** .



- **[Spacelift](https://spacelift.io/)**  

  **IaC orchestration platform** — Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes . **Best for complex multi-IaC workflows** .



- **[AWS CloudFormation](https://aws.amazon.com/cloudformation/)**  

  **AWS's native IaC service** — declarative templates for AWS resource provisioning . **The reference for AWS-native IaC** . **Best for AWS-centric organizations** .



- **[env0](https://www.env0.com/)**  

  **IaC automation platform** — self-service environments with guardrails . **Best for developer self-service** .



- **[Scalr](https://scalr.com/)**  

  **Terraform automation and collaboration** — policy enforcement and cost management . **Best for enterprise Terraform governance** .



- **[SaltStack Cloud](https://www.vmware.com/products/aria-automation-configuration.html)** — Event-driven infrastructure automation, now part of VMware Aria .



## Open-Source GitHub Projects



### Core IaC Engines



- **[Terraform](https://github.com/hashicorp/terraform)**  

  **The de facto IaC standard**, BUSL-1.1 licensed with **44,000+ GitHub stars** . **Declarative configuration for any cloud** — AWS, Azure, GCP, and 3,000+ providers . **The reference for infrastructure provisioning** . **Best for multi-cloud infrastructure as code** .



- **[OpenTofu](https://github.com/opentofu/opentofu)**  

  **Open-source Terraform fork**, MPL-2.0 licensed with **26,000+ GitHub stars** . **Community-driven under Linux Foundation** — no BSL concerns . **Drop-in replacement for Terraform** . **Best for organizations wanting open governance** .



- **[Pulumi](https://github.com/pulumi/pulumi)**  

  **IaC with real programming languages**, Apache-2.0 licensed with **23,000+ GitHub stars** . **TypeScript, Python, Go, .NET, Java** . **Full programming language power** — loops, functions, classes, and testing . **Best for developer-centric IaC** .



- **[Crossplane](https://github.com/crossplane/crossplane)**  

  **Kubernetes-native cloud resource management**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Extends Kubernetes API to manage cloud resources** — provision AWS, Azure, GCP from Kubernetes . **The standard for Kubernetes-native infrastructure** . **Best for platform teams building internal developer platforms** .



### Orchestration & Workflow



- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**  

  **Terraform wrapper for DRY configurations**, MIT licensed with **8,000+ GitHub stars** . **Orchestrates Terraform across accounts and environments** . **Keeps configurations DRY** . **Best for complex multi-account deployments** .



- **[Terramate](https://github.com/terramate-io/terramate)**  

  **Orchestration and code generation for Terraform**, MPL-2.0 licensed . **Adds stacks, orchestration, and GitOps to Terraform** . **Best for scaling Terraform deployments** .



- **[Atlantis](https://github.com/runatlantis/atlantis)**  

  **Terraform pull request automation**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Collaborative IaC via pull requests** . **Plan and apply from PR comments** . **Best for Terraform collaboration** .



- **[Digger](https://github.com/diggerhq/digger)**  

  **Open-source Terraform Cloud alternative**, MIT licensed . **CI/CD-native IaC orchestration** . **Best for Terraform in CI/CD** .



- **[Spacelift Agent](https://github.com/spacelift-io/spacelift-agent)** — Self-hosted agent for Spacelift .



### Policy & Governance



- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**  

  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across cloud, Kubernetes, and CI/CD** . **Best for policy-as-code enforcement** .



- **[Checkov](https://github.com/bridgecrewio/checkov)**  

  **Static analysis for IaC security and compliance**, Apache-2.0 licensed with **7,000+ GitHub stars** . **Scans Terraform, CloudFormation, Kubernetes, and more** . **Best for IaC security scanning** .



- **[tfsec](https://github.com/aquasecurity/tfsec)**  

  **Terraform security scanner**, MIT licensed with **7,000+ GitHub stars** . **Static analysis for Terraform misconfigurations** . **Best for Terraform security** .



- **[Infracost](https://github.com/infracost/infracost)**  

  **Cloud cost estimation for IaC**, Apache-2.0 licensed with **11,000+ GitHub stars** . **Shows cost impact of Terraform changes in PRs** . **Best for IaC cost visibility** .



### Configuration Management



- **[Ansible](https://github.com/ansible/ansible)**  

  **The standard for configuration management**, GPL-3.0 licensed with **63,000+ GitHub stars** . **Agentless automation for systems, networks, and clouds** . **Best for configuration automation** .



- **[Chef](https://github.com/chef/chef)**  

  **Infrastructure automation and configuration management**, Apache-2.0 licensed . **Policy-driven configuration** . **Best for enterprise configuration management** .



- **[Puppet](https://github.com/puppetlabs/puppet)**  

  **Configuration management and automation**, Apache-2.0 licensed . **Declarative configuration with agent-based enforcement** . **Best for large-scale configuration management** .



- **[SaltStack](https://github.com/saltstack/salt)**  

  **Event-driven infrastructure automation**, Apache-2.0 licensed . **Remote execution and configuration management** . **Best for event-driven automation** .



- **[Packer](https://github.com/hashicorp/packer)**  

  **Machine image builder**, BUSL-1.1 licensed with **15,000+ GitHub stars** . **Builds identical images for multiple platforms** . **Best for golden image creation** .



- **[Vagrant](https://github.com/hashicorp/vagrant)**  

  **Development environment automation**, BUSL-1.1 licensed . **Reproducible development environments** . **Best for local development environments** .



### Additional Strong Open-Source Options



- **Nix** — Reproducible package and system configuration management .

- **NixOS** — Linux distribution built on Nix with declarative system configuration .

- **Guix** — Functional package manager and Linux distribution .

- **Cloud-init** — Standard for early initialization of cloud instances .

- **Ignition** — First-boot provisioning for Fedora CoreOS and Flatcar .

- **KubeVirt** — Virtual machine management on Kubernetes .

- **Terraform Providers** — 3,000+ community providers for Terraform/OpenTofu .



**Frameworks for building custom IaC solutions**: Combine **Terraform** or **OpenTofu** for multi-cloud provisioning . Use **Pulumi** for IaC with real programming languages . Deploy **Crossplane** for Kubernetes-native cloud resource management . Choose **Terragrunt** or **Terramate** for orchestration at scale . Integrate **Atlantis** or **Digger** for PR-based Terraform workflows . Use **Open Policy Agent** for policy-as-code . Choose **Ansible**, **Chef**, or **Puppet** for configuration management . Use **Packer** for golden images . Note that true enterprise IaC with managed state, policy enforcement, and cost optimization (Terraform Cloud, Spacelift, Scalr) remains primarily commercial territory; open-source stacks provide strong provisioning, orchestration, and policy foundations that require integration for complete IaC deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IaC platforms control infrastructure and credentials. **Secure state files and secrets** — state contains sensitive data . Self-hosted solutions require proper security hardening and backup procedures.

- **Terraform's BUSL license** prompted the creation of **OpenTofu** under Linux Foundation governance . Evaluate licensing against your use case before committing.

- **State management is critical** — remote state backends (S3, GCS, Azure Blob) with locking are essential for team collaboration . Never commit state files to Git .

- **IaC security scanning is essential** — use Checkov, tfsec, or similar tools to catch misconfigurations before deployment .

- **License considerations**: Terraform uses BUSL-1.1, OpenTofu uses MPL-2.0, Pulumi uses Apache-2.0, Ansible uses GPL-3.0, and Packer uses BUSL-1.1. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong provisioning, orchestration, and policy foundations, but **managed state, policy enforcement, and cost optimization** remain primarily commercial offerings.



---



**Made for platform engineers, cloud architects, and organizations seeking IaC sovereignty.**  

Let's make infrastructure as code more open, transparent, and declarative.
