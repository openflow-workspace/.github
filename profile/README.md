# Openflow

### Your workspace. Your business systems. Your data.

An opinionated, self-hostable enterprise suite built around **openDesk**, bringing together **ERPNext**, **Discourse**, **Apache Airflow**, **PostgreSQL with pg_ducklake**, **S3-compatible storage**, and **Apache Superset**.

We are building a practical open-source alternative to common commercial enterprise suites: a coherent workspace with shared identity, connected business processes, and useful analytics from the start.

**Early stage: requirements and architecture.** The integrated distribution and standard process packages are being designed. There is no supported complete Openflow release yet.

---

## Find your starting point

| I want to... | Start here |
|---|---|
| Understand the project | [Distribution overview](https://github.com/openflow-workspace/distribution#readme) |
| Explore the architecture and scope | [Requirements](https://github.com/openflow-workspace/distribution/blob/main/REQUIREMENTS.md) |
| See what comes first | [Roadmap](https://github.com/openflow-workspace/distribution/blob/main/docs/roadmap.md) |
| Contribute with a coding agent | [Contribution guide](https://github.com/openflow-workspace/distribution/blob/main/CONTRIBUTING.md) and [AGENTS.md](https://github.com/openflow-workspace/distribution/blob/main/AGENTS.md) |
| Propose a focused improvement | [Open an issue](https://github.com/openflow-workspace/distribution/issues/new/choose) |

## One suite, clear responsibilities

- **Collaborate:** openDesk for files, communication, and project work.
- **Run the business:** ERPNext for core business operations.
- **Build shared knowledge:** Discourse for discussion and community.
- **Move and improve data:** Airflow pipelines across Bronze, Silver, and Gold.
- **Keep an open data foundation:** S3-compatible storage and PostgreSQL with pg_ducklake.
- **Understand the business:** Superset with predefined datasets, metrics, and dashboards.

### Useful processes, not just installed applications

Our planned standard process packages combine extraction, transformations, data quality checks, synthetic examples, metric definitions, and Superset dashboards. Initial candidates are **sales and receivables**, **purchasing and inventory**, and **project delivery**.

The data path is deliberate: **source systems → Bronze raw data → Silver structured data → Gold business datasets → Superset**.

## Help shape the first release

Contributions from people working with or without coding agents are welcome. Start with a bounded problem and checkable results: a connector contract, a metric definition, a compatibility investigation, a synthetic dataset, or a documentation improvement.

[Read how to contribute →](https://github.com/openflow-workspace/distribution/blob/main/CONTRIBUTING.md)

All Openflow-owned project content is authored in English. Openflow is an independent downstream project; upstream names identify their respective projects and do not imply endorsement.
