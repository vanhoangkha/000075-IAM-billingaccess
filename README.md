# Delegate access to the billing console

> Granting billing access with AWS IAM.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000075-IAM-billingaccess/

## Overview

AWS account owners can delegate access to specific IAM users who need to view or manage the AWS Billing and Cost Management data for an AWS account. The instructions that follow will help you set up a pretested scenario. This scenario helps you gain hands-on experience configuring billing permissions without concern for affecting your main AWS production account.

In this case, you will be logged into the root account and you want to grant billing permission to IAM Users or an IAM user group. This lab will answer questions about this section.

## Workshop contents

1. Introduction
2. Preparation
   - Create IAM User Group
3. Enable Access
4. Create IAM Policy
5. Assign Policy
6. Access Test
7. Clean up resources

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone https://github.com/vanhoangkha/000075-IAM-billingaccess.git
cd 000075-IAM-billingaccess
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
