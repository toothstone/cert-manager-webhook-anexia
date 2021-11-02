# Changelog
All notable changes to this project will be documented in this file.

Please be aware that this repo contains *two* versioned projects,
the webhook application released as a Docker image, and a Helm chart to deploy it.
The webhook version is managed via git tags,
the chart version is stated in its [`Chart.yaml`](deploy/cert-manager-webhook-anexia/Chart.yaml).

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

# Webhook application & image

## [webhook unreleased]
### Added
* Implemented cert-manager ACME webhook according to the requirements given in the template

# Helm chart
## [chart unreleased]
### Added
* Helm chart to deploy the Anexia cert-manager ACME webhook
* Role and RoleBinding to read Secrets which are needed to access the Anexia CloudDNS API

[webhook unreleased]: https://github.com/toothstone/cert-manager-webhook-anexia/commits/main
[chart unreleased]: https://github.com/toothstone/cert-manager-webhook-anexia/commits/main