# Amazon Amplify (amazon-amplify)

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
