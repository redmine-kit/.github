# Redmine Kit

Open-source tools for [Redmine](https://www.redmine.org/): Redmine plugins for theme authors and for running Redmine on AWS serverless services, and the design of a serverless Redmine.

**Documentation:** https://redmine-kit.github.io/ · 日本語: https://redmine-kit.github.io/ja/

## Plugins

| Plugin | What it does | Status | Documentation |
| --- | --- | --- | --- |
| [Redmine Lookbook](https://github.com/redmine-kit/redmine_lookbook) | Previews Redmine 7's components and pages in Lookbook, switching themes, languages and layouts, for theme authors | Early development | [Docs](https://redmine-kit.github.io/redmine_lookbook/) |
| [Redmine AWS](https://github.com/redmine-kit/redmine_aws) | The base of the Redmine AWS plugins: the AWS item of the administration menu, the Status tab with the connection test, and the shared settings of the AWS clients; works on any server | Early development | [Docs](https://redmine-kit.github.io/redmine_aws/) |
| [Redmine AWS Lambda](https://github.com/redmine-kit/redmine_aws_lambda) | Runs Redmine on AWS Lambda: the Lambda runtime and the settings that cannot work on Lambda | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_lambda/) |
| [Redmine AWS S3](https://github.com/redmine-kit/redmine_aws_s3) | Stores attachments in Amazon S3; uploads and downloads go through CloudFront with signed URLs on Redmine's domain, not through Redmine; also works outside Lambda | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_s3/) |
| [Redmine AWS SES](https://github.com/redmine-kit/redmine_aws_ses) | Sends and receives email with Amazon SES: retries of sending, importing received mail, addresses per project | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_ses/) |
| [Redmine AWS SQS](https://github.com/redmine-kit/redmine_aws_sqs) | Runs Redmine's background jobs on Amazon SQS: the settings of aws-activejob-sqs, records of failed jobs, and resending | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_sqs/) |
| [Redmine AWS SSM](https://github.com/redmine-kit/redmine_aws_ssm) | Loads settings and secrets from AWS Systems Manager Parameter Store into environment variables before Rails starts | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_ssm/) |
| [Redmine AWS Cost Explorer](https://github.com/redmine-kit/redmine_aws_costexplorer) | Shows the AWS account's costs from Cost Explorer in Redmine's administration: this month, the forecast, by service and by day | Early development | [Docs](https://redmine-kit.github.io/redmine_aws_costexplorer/) |
| [Redmine GitHub](https://github.com/redmine-kit/redmine_github) | Connects GitHub repositories through a GitHub App, instead of repositories on the server | Under consideration | [Docs](https://redmine-kit.github.io/redmine_github/) |

## Projects

| Project | What it is | Status | Documentation |
| --- | --- | --- | --- |
| [serverless](https://github.com/redmine-kit/serverless) | The image, infrastructure templates and deploy commands for running the latest Redmine on AWS Lambda, with RDS, S3, SQS and SES, using the Redmine AWS plugins | Early development | [Docs](https://redmine-kit.github.io/serverless/) |
| [design-guide](https://github.com/redmine-kit/design-guide) | How Redmine 7's own screens are built, for plugin screens that follow core, and how Redmine 7 applies a theme, with a checklist for theme authors | Early development | [Docs](https://redmine-kit.github.io/design-guide/) |

## Getting involved

- **Questions and bug reports:** open an issue in the repository concerned. Questions about the designs are welcome.
- **Pull requests:** read the [contributing guide](https://github.com/redmine-kit/.github/blob/main/CONTRIBUTING.md) first; for larger changes, start with an issue.
- **Security:** do not report vulnerabilities in public. Use **Report a vulnerability** in the repository's Security tab; see the [security policy](https://github.com/redmine-kit/.github/blob/main/SECURITY.md).
- **Conduct:** we follow the [code of conduct](https://github.com/redmine-kit/.github/blob/main/CODE_OF_CONDUCT.md).
- **Languages:** documentation is written in English, with a Japanese translation. Issues and pull requests in English or Japanese are welcome.

## License

The plugins and projects are released under the GNU General Public License, version 2 or later, like Redmine. Each repository has its license file.

Redmine Kit is an independent project and is not affiliated with or endorsed by the Redmine project.
