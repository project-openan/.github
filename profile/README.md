# OpenAN

**Open Autonomous Networks for Telecom**

[![LFN Candidate](https://img.shields.io/badge/LF_Networking-Candidate_Project-blue)](https://lfnetworking.org)
[![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Website](https://img.shields.io/badge/Website-openan.dev-orange)](https://openan.dev)
[![Zulip](https://img.shields.io/badge/Chat-Zulip-blueviolet)](https://linuxfoundation.zulipchat.com)

OpenAN is an open, vendor-neutral framework for end-to-end autonomous networks. It accelerates cross-layer, cross-domain integration of telecom-specific agents and enables multi-agent collaboration so global operators can deploy autonomous networks with efficient orchestration and interaction.

OpenAN is a candidate project under [LF Networking](https://lfnetworking.org), a Linux Foundation initiative.

## Mission

OpenAN brings operators, vendors, and innovators of the telecom industry together around shared standards, shared skills, and a shared roadmap toward Autonomous Networks Level 5. The project provides open source implementations of the core components needed for telecom-grade multi-agent collaboration, grounded in industry standards including A2A-T, SPG, and intent APIs.

## Components

| Component | Repositories | Description |
|---|---|---|
| **A2A-T SDK** | [`a2a-t-sdk-java`](https://github.com/project-openan/a2a-t-sdk-java), [`a2a-t-sdk-python`](https://github.com/project-openan/a2a-t-sdk-python) | A telecom-grade extension of the A2A protocol for deterministic, network-scenario-compliant cross-layer agent collaboration. Supports JSON-RPC and HTTP+REST. |
| **Registry Center** | [`registry-center`](https://github.com/project-openan/registry-center) | An agent discovery service ("agent labor market") that manages agent addresses, registers skills, handles health management, and uses LLM-aided retrieval to map intents to the right agent. |
| **Orchestration Center** | [`orchestration-center`](https://github.com/project-openan/orchestration-center) | A workflow orchestration hub featuring a workflow canvas, condition editor, property manager, and workflow market that bridges manual design and autonomous programming. |
| **Documentation** | [`docs`](https://github.com/project-openan/docs) | Project documentation. |

## A2A-T Extensions

A2A-T extends the A2A protocol with four telecom-grade primitives:

- **Task-T Schema** : Structured task definitions that eliminate ambiguity in inter-agent requests
- **Sub-Pub-T Eventing** : Network event subscription and publication optimized for telecom O&M data patterns
- **Negotiation-T Control** : Structured negotiation between agents to resolve ambiguity and confirm feasibility
- **Authorization-T Security** : Dynamic security with agent card limitations and explicit authorization before network-changing operations

## Roadmap

| Milestone | Timeframe | Description |
|---|---|---|
| Kickoff | March 2026 (MWC Barcelona) | China Mobile and Huawei announce OpenAN |
| Seed Code and LFN Donation | June 2026 (DTW Copenhagen) | A2A-T SDK, Registry Center, and Orchestration Center are open sourced and donated to LF Networking |
| Launch Innovations | December 2026 (TM Forum IHPP) | Scenario solution packages and additional contributors |
| Commercial Verification | 2027 | Ongoing maintenance and commercial verification of OpenAN deployments |

## Community

- **Website**: [openan.dev](https://openan.dev)
- **Zulip**: Real-time discussion on the [LF Zulip](https://linuxfoundation.zulipchat.com) in `#lfn-openan-discussion`, `#lfn-openan-support`, and `#lfn-openan-tsc`
- **Mailing Lists**: [lists.openan.dev](https://lists.openan.dev)
- **Wiki**: [OpenAN Confluence space](https://lf-networking.atlassian.net/wiki/spaces/OpenAN/overview)
- **Meetings**: Community calls are open to everyone; schedules are published on the wiki and mailing lists

## Governance

OpenAN is governed by its community under the OpenAN Technical Charter:

- The **Technical Steering Committee (TSC)** guides the project's technical direction
- The **Adopter Advisory Committee (AAC)** provides advisory input on market requirements, use cases, and ecosystem engagement

Details are in the [governance](https://github.com/project-openan/governance) repository. Each repository lists its maintainers in its MAINTAINERS.md file.

## Founding Contributors

- **China Mobile** : Kickoff partner
- **Huawei** : Kickoff partner

The full startup TSC roster is listed in [CONTRIBUTING.md](https://github.com/project-openan/.github/blob/main/CONTRIBUTING.md).

## Contributing

Contributions are welcome under the Apache 2.0 license. See [CONTRIBUTING.md](https://github.com/project-openan/.github/blob/main/CONTRIBUTING.md) for the contribution process, DCO sign-off requirements, and CLA details. The best way to get started is to join the Zulip channels and the mailing lists, then pick up an open issue in one of the component repositories.

## License

OpenAN is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Links

- [OpenAN Website](https://openan.dev)
- [LF Networking](https://lfnetworking.org)
- [LFN Charter](https://lfnetworking.org/wp-content/uploads/sites/7/2022/04/LF-Networking-Fund-Charter-updated-2020-04-29.pdf)
- [Contact](mailto:info@lfnetworking.org)
