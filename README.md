## Hi, I'm Fatuma 👋

**Cloud Engineer · AWS · Terraform · AWS CDK · Serverless · Los Angeles**

I design and build AWS infrastructure as code, with a focus on secure, cost-aware architectures that can be torn down and rebuilt with a single command. Most of my work lives at the intersection of networking, identity and serverless application delivery.

### Featured projects

| Project | What it shows | Stack |
|---|---|---|
| [**Halal Finder**](https://github.com/fatumaabdo14-cmd/halal-finder-serverless) · [live](https://d1e3ukex7mhofw.cloudfront.net) | Full-stack serverless app with GPS-based search, fully provisioned with Terraform | CloudFront, S3, API Gateway, Lambda, DynamoDB, Terraform |
| [**Halal Finder Security**](https://github.com/fatumaabdo14-cmd/halal-finder-security-cdk) | Authentication, authorization, encryption at rest and audit logging added to a live app | Cognito, Lambda, KMS, CloudTrail, CDK |
| [**TechHealth Patient Portal**](https://github.com/fatumaabdo14-cmd/techhealth-cdk) | Healthcare workload migrated to IaC; database with zero public exposure, ~$64/mo saved on NAT | VPC, EC2, RDS, Secrets Manager, CDK |
| [**StartupCo IAM Hardening**](https://github.com/fatumaabdo14-cmd/startupco-iam-security) | Shared root credentials replaced with least-privilege groups, MFA-enforced roles and KMS | IAM, KMS, S3, Terraform |
| [**Image Sharing Platform**](https://github.com/fatumaabdo14-cmd/image-sharing-platform) | Architecture for ~250k DAU: multipart uploads, event-driven thumbnails, global delivery | S3, Cognito, Lambda, EventBridge, CloudFront, CloudFormation |
| [**Lambda CI/CD Pipeline**](https://github.com/fatumaabdo14-cmd/lambda-cicd-pipeline) | Ephemeral CloudFormation test stack per pull request, cleaned up automatically on merge | GitHub Actions, CloudFormation, Lambda |

More: [multi-tier web stack (CDK)](https://github.com/fatumaabdo14-cmd/my-web-app-infrastructure) · [task API pipeline](https://github.com/fatumaabdo14-cmd/task-api-cicd-pipeline) · [CloudFormation templates](https://github.com/fatumaabdo14-cmd/aws-cloudformation-templates) · [Next.js on S3 + CloudFront (Terraform)](https://github.com/fatumaabdo14-cmd/terraform-portfolio-project)

### Tech

**Cloud:** AWS (VPC, EC2, ALB, Auto Scaling, RDS, S3, CloudFront, Lambda, API Gateway, DynamoDB, Cognito, IAM, KMS, Secrets Manager, CloudTrail, CloudWatch)
**IaC:** Terraform · AWS CDK (TypeScript) · CloudFormation
**CI/CD:** GitHub Actions · Git
**Languages:** Python · TypeScript · JavaScript · Bash

### How I work

- Everything in code: environments are reproducible from the repo, not the console.
- Least privilege by default: security groups reference each other, roles get only the actions they need, credentials live in Secrets Manager.
- Cost is a design input: no idle NAT gateways, on-demand tables, and stacks destroyed when not in use.

### Connect

[LinkedIn](https://www.linkedin.com/in/fatuma-abdo-3b729a3a4) · [Medium](https://medium.com/@fatumaabdo14) · fatumaabdo14@gmail.com
