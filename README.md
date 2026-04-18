# Ansible Automation Platform (ansible-automation-platform)
Ansible Automation Platform provides a REST API for managing automation workflows, job templates, inventories, credentials, and projects. The API enables programmatic access to the automation controller for launching jobs, managing infrastructure inventory, and orchestrating complex multi-tier deployments across hybrid cloud environments.

**URL:** [https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ansible-automation-platform/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Configuration Management, DevOps, Infrastructure as Code, Orchestration

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Ansible Automation Controller API
RESTful API for job templates, workflows, inventories, credentials, projects, and job execution.

### Ansible Automation Hub API
REST API for certified and validated Ansible content collections.

### Ansible Event-Driven Automation API
API for Event-Driven Ansible Controller with rulebooks and event sources.

### Ansible Galaxy API
REST API for community Ansible roles and collections.

## Features

| Name | Description |
|------|-------------|
| Job Template Management | Define and manage reusable automation job templates. |
| Workflow Orchestration | Build multi-step automation workflows with conditional logic. |
| Inventory Management | Manage dynamic and static inventories of infrastructure hosts. |
| Role-Based Access Control | Fine-grained access control for automation resources. |
| Event-Driven Automation | Automatically respond to infrastructure events. |
| Content Collections | Discover and manage certified Ansible content collections. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Provisioning | Automate provisioning of servers, networks, and cloud resources. |
| Configuration Management | Maintain consistent configuration across thousands of servers. |
| Application Deployment | Automate application deployment pipelines with rolling updates. |
| Security Compliance | Enforce security policies through automated remediation workflows. |
| Network Automation | Automate network device configuration across multi-vendor environments. |

## Integrations

| Name | Description |
|------|-------------|
| Red Hat Satellite | Content management and patch automation integration. |
| ServiceNow | ITSM integration for change management approval workflows. |
| AWS | Cloud automation modules for AWS services. |
| Azure | Cloud automation modules for Azure services. |
| Terraform | Infrastructure as code integration. |
| Jenkins | CI/CD pipeline integration for automated deployment. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ansible-controller-api.yaml](openapi/ansible-controller-api.yaml)

### JSON-LD

- [ansible-automation-platform-context.jsonld](json-ld/ansible-automation-platform-context.jsonld)

## Rules

- [ansible-automation-platform-spectral-rules.yml](rules/ansible-automation-platform-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
