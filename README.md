# Amazon CloudShell (amazon-cloudshell)
AWS CloudShell is a browser-based terminal that enables users to manage and explore AWS resources directly from the AWS Management Console. Pre-authenticated, pre-installed with AWS CLI and dev tools, with 1 GB of persistent storage per region.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloudshell/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, CloudShell, Terminal, CLI, Browser-Based

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CloudShell API
API for creating and managing CloudShell environments — browser-based terminal sessions for AWS resource management.

**Human URL:** [https://aws.amazon.com/cloudshell/](https://aws.amazon.com/cloudshell/)

#### Tags:

 - AWS, CloudShell, Terminal, Development

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloudshell/latest/userguide/)

- [APIReference](https://docs.aws.amazon.com/cloudshell/latest/userguide/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloudshell/)
- [SpectralRules](rules/amazon-cloudshell-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloudshell-vocabulary.yaml)
- [NaftikoCapability](capabilities/shell-environment.yaml)

## Features

| Name | Description |
|------|-------------|
| Pre-Authenticated Access | Sign in with AWS Console credentials — no additional authentication required. |
| Pre-Installed Tools | Amazon Linux 2 environment with AWS CLI, SDKs, and development tools pre-installed. |
| Persistent Storage | Up to 1 GB of persistent storage per AWS region for scripts and configurations. |
| No Additional Cost | Running commands in CloudShell incurs no extra charges beyond standard AWS service fees. |
| File Management | Upload and download files directly from the browser. |

## Use Cases

| Name | Description |
|------|-------------|
| Quick CLI Access | Execute AWS CLI commands from any browser without local setup. |
| Script Execution | Run existing scripts with integrated AWS CLI documentation and auto-completion. |
| Security Operations | Reduce incident response times with seamless console-authenticated terminal access. |
| Training and Demos | Provide consistent, pre-configured AWS environments for training and demonstrations. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Management Console | Launch directly from any AWS Console page with existing credentials. |
| AWS CLI | Pre-installed and pre-configured AWS CLI for all service access. |
| AWS IAM | CloudShell inherits permissions from the signed-in IAM user or role. |
| Amazon S3 | Upload files to and download files from S3 using CloudShell. |

## Artifacts

### JSON Schema

- No schemas generated

### JSON-LD

- [Amazon CloudShell Context](json-ld/amazon-cloudshell-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon CloudShell](capabilities/shared/cloudshell.yaml) — 4 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Cloud Shell Environment Management](capabilities/shell-environment.yaml) | Amazon CloudShell | 4 | Cloud Administrator |

## Vocabulary

- [Amazon CloudShell Vocabulary](vocabulary/amazon-cloudshell-vocabulary.yaml) — Unified taxonomy covering operations, workflows, and personas

## Rules

- [Amazon CloudShell Spectral Rules](rules/amazon-cloudshell-spectral-rules.yml) — 19 rules enforcing Amazon CloudShell API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
