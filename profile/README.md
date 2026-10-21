# ScriptRunnerKit

**Open-source .NET libraries and tools for running scripts — Python first — with typed contracts, pipelines, queues and dashboards.**

Teams that do heavy calculation often have the math in scripts and the systems that need the results in .NET.
ScriptRunnerKit projects connect the two without rewriting the logic and without fragile glue: scripts keep living in
their own language, and .NET gets typed, versioned, observable results.

## Projects

| Project | What it does | Status |
|---------|--------------|--------|
| **[PythonScriptRunner](https://github.com/ScriptRunnerKit/PythonScriptRunner)** | Runs Python *stages* from .NET with typed inputs and outputs, chains them into pipelines, queues them on RabbitMQ with retries and cron schedules, and operates them from an embeddable Vue dashboard. Packages on NuGet, SDK on PyPI, containers on GHCR. | First release (v0.1.0) coming soon |

## What we care about

- **Typed contracts** between .NET and the scripts: inputs and outputs are validated on both sides.
- **Isolation and limits**: every script runs in its own process, with a timeout, a memory limit and a clean environment.
- **Reproducibility**: script dependencies are resolved once and locked with hashes.
- **Observability**: OpenTelemetry traces and metrics, run history and an audit trail out of the box.
- **Batteries included**: ready-to-run hosts, container images and a one-command local environment with .NET Aspire.

## Get involved

- Read the [Code of Conduct](https://github.com/ScriptRunnerKit/.github/blob/main/CODE_OF_CONDUCT.md) and the
  [contributing guide](https://github.com/ScriptRunnerKit/.github/blob/main/CONTRIBUTING.md).
- Found a bug or have an idea? Open an issue in the project repository.
- Found a security issue? Please report it privately — see the
  [security policy](https://github.com/ScriptRunnerKit/.github/blob/main/SECURITY.md).

All projects are released under the MIT license.
