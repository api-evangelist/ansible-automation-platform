# Ansible Automation Platform (ansible-automation-platform)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
