# System Architecture Examples

## Release-Kraken
### A Centralised Multi-purpose DevOps Monitoring & Automation Suite of Tools



### Release Page Generator

![rk-page-gen](./docs/release_page_generator.drawio.png)
https://github.com/drmonkeysee/ecs-scheduler = runs on cron

runs a taskdef once only on a 30 min cron

1. Pulls & filters this weeks JIRA releases from multiple dev teams
2. Displays issues left to do in that release 2/8
3. Consults data-store for mapped bamboo jobs for that particular release  - publishes the current version that is deployed to (UAT & PROD)

use python requests & bs4

auto-updates every 30 mins

### Cloudwatch Alerter

![rk-alerter](./docs/rk_sqs_alerter.drawio.png)

### Terraform PR Enforcer

![rk-pr-enforcer](./docs/rk_terraform_pr_enforcer.drawio.png)


### Terraform Module Manger
TBD

### ECR Security Scanner

![rk-alerter](./docs/rk_sqs_alerter.drawio.png)

### Bamboo Permission Enforcer
TBD

### Grafana visualiser

![rk-grafana](./docs/rk_grafana.drawio.png)



### EC2 Tag Enforcer
TBD



