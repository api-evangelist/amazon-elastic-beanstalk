# Amazon Elastic Beanstalk (amazon-elastic-beanstalk)
AWS Elastic Beanstalk is a platform-as-a-service (PaaS) that makes it easy to deploy, manage, and scale web applications and services. You simply upload your code and Elastic Beanstalk automatically handles the deployment, capacity provisioning, load balancing, auto-scaling, and application health monitoring.

**URL:** [https://aws.amazon.com/elasticbeanstalk/](https://aws.amazon.com/elasticbeanstalk/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, AWS, Auto Scaling, Deployment, Elastic Beanstalk, PaaS, Platform As A Service, Web Applications

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### AWS Elastic Beanstalk API
API for managing AWS Elastic Beanstalk applications, environments, and related resources including configuration templates and application versions.

**Human URL:** [https://aws.amazon.com/elasticbeanstalk/](https://aws.amazon.com/elasticbeanstalk/)

#### Tags:

 - Auto Scaling, Deployment, PaaS, Web Applications

#### Properties

- [Documentation](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/)
- [OpenAPI](openapi/amazon-elastic-beanstalk-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/elasticbeanstalk/latest/api/)
- [GettingStarted](https://aws.amazon.com/elasticbeanstalk/getting-started/)
- [Pricing](https://aws.amazon.com/elasticbeanstalk/pricing/)
- [FAQ](https://aws.amazon.com/elasticbeanstalk/faqs/)
- [JSONSchema](json-schema/amazon-elastic-beanstalk-application-description-message-schema.json)
- [JSONSchema](json-schema/amazon-elastic-beanstalk-application-description-schema.json)
- [JSONSchema](json-schema/amazon-elastic-beanstalk-application-descriptions-message-schema.json)
- [JSONLD](json-ld/amazon-elastic-beanstalk-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/elasticbeanstalk/)
- [Documentation](https://docs.aws.amazon.com/elasticbeanstalk/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/elasticbeanstalk/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/elasticbeanstalk/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/elasticbeanstalk)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Automatic Deployment | Upload code and Elastic Beanstalk handles deployment automatically |
| Auto Scaling | Automatically scale capacity up and down based on application needs |
| Health Monitoring | Monitor application health and performance with built-in dashboards |
| Multi-Language Support | Support for Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker |
| Environment Management | Manage multiple deployment environments (development, staging, production) |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Hosting | Deploy and host web applications without managing infrastructure |
| API Backend Deployment | Deploy REST API backends with automatic scaling and load balancing |
| Microservices Deployment | Deploy containerized microservices using Docker or multi-container configurations |
| Blue-Green Deployments | Perform zero-downtime deployments using environment URL swapping |

## Integrations

| Name | Description |
|------|-------------|
| Amazon EC2 | Runs application environments on EC2 instances |
| Amazon RDS | Provision and manage RDS databases alongside environments |
| Amazon S3 | Store application versions and deployment artifacts |
| AWS CloudFormation | Manage environment infrastructure as code |
| AWS CodePipeline | Integrate with CI/CD pipelines for automated deployments |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-elastic-beanstalk](openapi/amazon-elastic-beanstalk-openapi.yml)

### JSON Schema

- [amazon-elastic-beanstalk-application-description-message](json-schema/amazon-elastic-beanstalk-application-description-message-schema.json)
- [amazon-elastic-beanstalk-application-description](json-schema/amazon-elastic-beanstalk-application-description-schema.json)
- [amazon-elastic-beanstalk-application-descriptions-message](json-schema/amazon-elastic-beanstalk-application-descriptions-message-schema.json)
- [amazon-elastic-beanstalk-environment-descriptions-message](json-schema/amazon-elastic-beanstalk-environment-descriptions-message-schema.json)
- [amazon-elastic-beanstalk-environment](json-schema/amazon-elastic-beanstalk-environment-schema.json)

### JSON Structure

- [amazon-elastic-beanstalk-application-description-message](json-structure/amazon-elastic-beanstalk-application-description-message-structure.json)
- [amazon-elastic-beanstalk-application-description](json-structure/amazon-elastic-beanstalk-application-description-structure.json)
- [amazon-elastic-beanstalk-application-descriptions-message](json-structure/amazon-elastic-beanstalk-application-descriptions-message-structure.json)
- [amazon-elastic-beanstalk-environment-descriptions-message](json-structure/amazon-elastic-beanstalk-environment-descriptions-message-structure.json)
- [amazon-elastic-beanstalk-environment](json-structure/amazon-elastic-beanstalk-environment-structure.json)

### JSON-LD

- [amazon-elastic-beanstalk](json-ld/amazon-elastic-beanstalk-context.jsonld)

### Examples

- [amazon-elastic-beanstalk-application-description](examples/amazon-elastic-beanstalk-application-description-example.json)
- [amazon-elastic-beanstalk-application-description-message](examples/amazon-elastic-beanstalk-application-description-message-example.json)
- [amazon-elastic-beanstalk-application-descriptions-message](examples/amazon-elastic-beanstalk-application-descriptions-message-example.json)
- [amazon-elastic-beanstalk-environment-descriptions-message](examples/amazon-elastic-beanstalk-environment-descriptions-message-example.json)
- [amazon-elastic-beanstalk-environment](examples/amazon-elastic-beanstalk-environment-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Elastic Beanstalk](capabilities/shared/api.yaml) — 5 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon Elastic Beanstalk Management](capabilities/amazon-elastic-beanstalk-capability.yaml) | 5 | Cloud Architect |

## Vocabulary

- [Amazon Elastic Beanstalk Vocabulary](vocabulary/amazon-elastic-beanstalk-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflows, and 2 personas

## Rules

- [amazon-elastic-beanstalk-spectral-rules.yml](rules/amazon-elastic-beanstalk-spectral-rules.yml) — 0 rules enforcing Amazon Elastic Beanstalk API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
