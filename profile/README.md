# Redmine Kit

Open-source tools for [Redmine](https://www.redmine.org/): Redmine plugins for theme authors and for running Redmine on AWS serverless services, and the design of a serverless Redmine.

**Documentation:** https://redmine-kit.github.io/ · 日本語: https://redmine-kit.github.io/ja/

## Plugins

| Plugin | What it does | Status | Documentation |
| --- | --- | --- | --- |
| [Redmine Lookbook](https://github.com/redmine-kit/redmine_lookbook) | Previews Redmine 7's components and pages in Lookbook, switching themes, languages and layouts, for theme authors | Early development | [Docs](https://redmine-kit.github.io/redmine_lookbook/) |
| [Redmine Serverless](https://github.com/redmine-kit/redmine_serverless) | Runs Redmine on AWS Lambda: the Lambda runtime, the settings that cannot work on Lambda, and the status and connections administration page | Design stage | [Docs](https://redmine-kit.github.io/redmine_serverless/) |
| [Redmine Serverless Cost Explorer](https://github.com/redmine-kit/redmine_serverless_costexplorer) | Shows the AWS account's costs from Cost Explorer in Redmine's administration: this month, the forecast, by service and by day | Early development | [Docs](https://redmine-kit.github.io/redmine_serverless_costexplorer/) |
| [Redmine Serverless S3](https://github.com/redmine-kit/redmine_serverless_s3) | Stores attachments in Amazon S3, with direct uploads and downloads through presigned URLs; also works outside Lambda | Design stage | [Docs](https://redmine-kit.github.io/redmine_serverless_s3/) |
| [Redmine Serverless SES](https://github.com/redmine-kit/redmine_serverless_ses) | Sends and receives email with Amazon SES: retries of sending, importing received mail, addresses per project | Design stage | [Docs](https://redmine-kit.github.io/redmine_serverless_ses/) |
| [Redmine Serverless SQS](https://github.com/redmine-kit/redmine_serverless_sqs) | Runs Redmine's background jobs on Amazon SQS: the settings of aws-activejob-sqs, records of failed jobs, and resending | Design stage | [Docs](https://redmine-kit.github.io/redmine_serverless_sqs/) |
| [Redmine Serverless SSM](https://github.com/redmine-kit/redmine_serverless_ssm) | Loads settings and secrets from AWS Systems Manager Parameter Store into environment variables before Rails starts | Early development | [Docs](https://redmine-kit.github.io/redmine_serverless_ssm/) |
| [Redmine GitHub](https://github.com/redmine-kit/redmine_github) | Connects GitHub repositories through a GitHub App, instead of repositories on the server | Under consideration | [Docs](https://redmine-kit.github.io/redmine_github/) |

## Projects

| Project | What it is | Status | Documentation |
| --- | --- | --- | --- |
| [serverless](https://github.com/redmine-kit/serverless) | A design for running the latest Redmine on AWS Lambda, with RDS for PostgreSQL, S3, SQS and SES, using the Redmine Serverless plugins | Design stage | [Docs](https://redmine-kit.github.io/serverless/) |
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
