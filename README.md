**Note:** This project is a fork of `opentelemetry-demo`. Thanks to the team and contributors for opensourcing this wonderful demo project. Definitely one of the best on internet.

<!-- markdownlint-disable-next-line -->
# <img src="https://opentelemetry.io/img/logos/opentelemetry-logo-nav.png" alt="OTel logo" width="45"> OpenTelemetry Demo

[![Slack](https://img.shields.io/badge/slack-@cncf/otel/demo-brightgreen.svg?logo=slack)](https://cloud-native.slack.com/archives/C03B4CWV4DA)
[![Version](https://img.shields.io/github/v/release/open-telemetry/opentelemetry-demo?color=blueviolet)](https://github.com/open-telemetry/opentelemetry-demo/releases)
[![Commits](https://img.shields.io/github/commits-since/open-telemetry/opentelemetry-demo/latest?color=ff69b4&include_prereleases)](https://github.com/open-telemetry/opentelemetry-demo/graphs/commit-activity)
[![Downloads](https://img.shields.io/docker/pulls/otel/demo)](https://hub.docker.com/r/otel/demo)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg?color=red)](https://github.com/open-telemetry/opentelemetry-demo/blob/main/LICENSE)
[![Integration Tests](https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml/badge.svg)](https://github.com/open-telemetry/opentelemetry-demo/actions/workflows/run-integration-tests.yml)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/opentelemetry-demo)](https://artifacthub.io/packages/helm/opentelemetry-helm/opentelemetry-demo)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/9247/badge)](https://www.bestpractices.dev/en/projects/9247)

## Welcome to the OpenTelemetry Astronomy Shop Demo

This repository contains the OpenTelemetry Astronomy Shop, a microservice-based
distributed system intended to illustrate the implementation of OpenTelemetry in
a near real-world environment.

Our goals are threefold:

- Provide a realistic example of a distributed system that can be used to
  demonstrate OpenTelemetry instrumentation and observability.
- Build a base for vendors, tooling authors, and others to extend and
  demonstrate their OpenTelemetry integrations.
- Create a living example for OpenTelemetry contributors to use for testing new
  versions of the API, SDK, and other components or enhancements.

We've already made [huge
progress](https://github.com/open-telemetry/opentelemetry-demo/blob/main/CHANGELOG.md),
and development is ongoing. We hope to represent the full feature set of
OpenTelemetry across its languages in the future.

If you'd like to help (**which we would love**), check out our [contributing
guidance](./CONTRIBUTING.md).

If you'd like to extend this demo or maintain a fork of it, read our
[fork guidance](https://opentelemetry.io/docs/demo/forking/).

## Quick start

You can be up and running with the demo in a few minutes. Check out the docs for
your preferred deployment method:

- [Docker](https://opentelemetry.io/docs/demo/docker_deployment/)
- [Kubernetes](https://opentelemetry.io/docs/demo/kubernetes_deployment/)

## Documentation

For detailed documentation, see [Demo Documentation][docs]. If you're curious
about a specific feature, the [docs landing page][docs] can point you in the
right direction.

## Demos featuring the Astronomy Shop

We welcome any vendor to fork the project to demonstrate their services and
adding a link below. The community is committed to maintaining the project and
keeping it up to date for you.

|                           |                |                                  |
|---------------------------|----------------|----------------------------------|
| [AlibabaCloud LogService] | [Elastic]      | [OpenSearch]                     |
| [AppDynamics]             | [Google Cloud] | [Sentry]                         |
| [Aspecto]                 | [Grafana Labs] | [ServiceNow Cloud Observability] |
| [Axiom]                   | [Guance]       | [Splunk]                         |
| [Axoflow]                 | [Honeycomb.io] | [Sumo Logic]                     |
| [Azure Data Explorer]     | [Instana]      | [TelemetryHub]                   |
| [Coralogix]               | [Kloudfuse]    | [Teletrace]                      |
| [Dash0]                   | [Liatrio]      | [Tracetest]                      |
| [Datadog]                 | [Logz.io]      | [Uptrace]                        |
| [Dynatrace]               | [New Relic]    |                                  |

## Contributing

To get involved with the project see our [CONTRIBUTING](CONTRIBUTING.md)
documentation. Our [SIG Calls](CONTRIBUTING.md#join-a-sig-call) are every other
Monday at 8:30 AM PST and anyone is welcome.

