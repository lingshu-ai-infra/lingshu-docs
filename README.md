# lingshu-docs

Detailed technical documentation site for LingShu AI Infra.

## Planned sections

- **Architecture** — 4-layer diagram, state machine, ControllerManager flow
- **Operator authoring** — Op protocol, schema versioning, lifecycle
- **Deployment** — K8s manifests, Helm, single-cluster → multi-cluster
- **Operations** — Runbook, failure scenarios, capacity tuning
- **API reference** — Protobuf 11 messages, Client SDK JavaDoc

## Stack

Docusaurus 3.5.2 + webpack 5.94.0 override (matching the lingshu-docs deploy playbook).
