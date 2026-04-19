# Amazon Amplify (amazon-amplify)
AWS Amplify is a set of tools and services for building secure, scalable full-stack applications powered by AWS. It provides frontend and mobile developers with a complete workflow for building, deploying, and hosting cloud-powered applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Frontend, Full Stack, Hosting, Mobile Development, Web Applications

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Amplify REST API
RESTful API for AWS Amplify enabling management of apps, branches, domain associations, backend environments, and deployments for full-stack web and mobile applications.

**Human URL:** [https://aws.amazon.com/amplify/](https://aws.amazon.com/amplify/)

#### Tags:

 - AWS, Frontend, Full Stack, Mobile Development

#### Properties

- [Documentation](https://docs.aws.amazon.com/amplify/latest/APIReference/)
- [OpenAPI](openapi/amazon-amplify-openapi.yaml)
- [JSONSchema](json-schema/amazon-amplify-app-schema.json)
- [JSONLD](json-ld/amazon-amplify-context.jsonld)
- [Pricing](https://aws.amazon.com/amplify/pricing/)
- [Getting Started](https://aws.amazon.com/amplify/getting-started/)
- [Authentication](https://docs.aws.amazon.com/amplify/latest/APIReference/Welcome.html)
- [SDKs](https://aws.amazon.com/tools/)
- [FAQ](https://aws.amazon.com/amplify/faqs/)
- [User Guide](https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html)
- [API Reference](https://docs.aws.amazon.com/amplify/latest/APIReference/Welcome.html)
- [Service Level Agreement](https://aws.amazon.com/amplify/sla/)
- [Status](https://status.aws.amazon.com/)
- [JSONSchema](json-schema/amazon-amplify-app-schema.json)
- [JSONSchema](json-schema/amazon-amplify-branch-schema.json)
- [JSONSchema](json-schema/amazon-amplify-createapprequest-schema.json)
- [JSONSchema](json-schema/amazon-amplify-createappresult-schema.json)
- [JSONSchema](json-schema/amazon-amplify-createbranchrequest-schema.json)
- [JSONStructure](json-structure/amazon-amplify-app-structure.json)
- [JSONStructure](json-structure/amazon-amplify-branch-structure.json)
- [JSONStructure](json-structure/amazon-amplify-createapprequest-structure.json)
- [JSONLD](json-ld/amazon-amplify-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/amplify/)
- [Documentation](https://docs.aws.amazon.com/amplify/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/mobile/)
- [GitHubOrganization](https://github.com/aws-amplify)
- [Console](https://console.aws.amazon.com/amplify/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [Status](https://health.aws.amazon.com/health/status)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-amplify)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-amplify-spectral-rules.yml)
- [NaftikoCapability](capabilities/amplify-app-management.yaml)
- [Vocabulary](vocabulary/amazon-amplify-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| App Management | Create, update, and delete Amplify apps connected to Git repositories with automated build and deployment settings. |
| Branch Management | Manage feature branches and environments with independent build configurations, environment variables, and preview URLs. |
| Deployment Automation | Trigger and monitor deployments across branches with build history, logs, and status tracking. |
| Domain Association | Associate custom domains with Amplify apps and manage SSL certificates and subdomain routing configurations. |
| Backend Environment Management | Manage AWS backend environments linked to Amplify applications for full-stack cloud resource provisioning. |

## Use Cases

| Name | Description |
|------|-------------|
| CI/CD Pipeline Automation | Automate build and deployment workflows for frontend apps by programmatically managing Amplify apps and branch deployments. |
| Multi-Environment Management | Manage development, staging, and production environments as separate branches with independent configurations. |
| Infrastructure as Code | Provision and configure Amplify hosting environments as part of infrastructure-as-code pipelines using the REST API. |
| Developer Portal Integration | Integrate Amplify app management into internal developer portals for self-service application deployment and hosting. |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodeCommit | Connect Amplify apps to AWS CodeCommit repositories for source code hosting and automated deployments. |
| GitHub | Link Amplify deployments to GitHub repositories with automatic builds triggered on pull requests and branch merges. |
| AWS CloudFront | Amplify hosting uses CloudFront for global CDN distribution of static assets and dynamic content. |
| AWS Route 53 | Configure custom domains for Amplify apps using Route 53 DNS management and SSL certificate provisioning. |

## Artifacts

### OpenAPI

- [Amazon Amplify REST API OpenAPI](openapi/amazon-amplify-openapi.yaml)

### JSON Schema

- [amazon-amplify-app-schema.json](json-schema/amazon-amplify-app-schema.json)
- [amazon-amplify-branch-schema.json](json-schema/amazon-amplify-branch-schema.json)
- [amazon-amplify-createapprequest-schema.json](json-schema/amazon-amplify-createapprequest-schema.json)
- [amazon-amplify-createappresult-schema.json](json-schema/amazon-amplify-createappresult-schema.json)
- [amazon-amplify-createbranchrequest-schema.json](json-schema/amazon-amplify-createbranchrequest-schema.json)
- [amazon-amplify-createdomainassociationrequest-schema.json](json-schema/amazon-amplify-createdomainassociationrequest-schema.json)
- [amazon-amplify-getappresult-schema.json](json-schema/amazon-amplify-getappresult-schema.json)
- [amazon-amplify-listappsresult-schema.json](json-schema/amazon-amplify-listappsresult-schema.json)
- [amazon-amplify-productionbranch-schema.json](json-schema/amazon-amplify-productionbranch-schema.json)
- [amazon-amplify-updateapprequest-schema.json](json-schema/amazon-amplify-updateapprequest-schema.json)

## Capabilities

- [Amazon Amplify API](capabilities/shared/amazon-amplify.yaml) — 2 operations for app management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amplify App Management](capabilities/amplify-app-management.yaml) | Amazon Amplify REST API | 2 | Frontend Developer, DevOps Engineer |

## Vocabulary

- [Amazon Amplify Vocabulary](vocabulary/amazon-amplify-vocabulary.yaml)

## Rules

- [Amazon Amplify Spectral Rules](rules/amazon-amplify-spectral-rules.yml) — 5 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
