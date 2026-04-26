# Subversive Stack

Secure Distributed/Decentralized Ledgers (SDDL), pronounced “Saddle”.

We build toward user-controlled, privacy-first distributed ledgers that do not depend on token speculation or unproven security assumptions.

This is an early-stage project. We currently focus on permissioned environments using the [commonware](https://commonware.xyz/) stack (minus consensus).

## Current State

We have pivoted from Substrate to the commonware.xyz primitives. Most repositories here are read-only mirrors or minor adaptations of upstream components.

We are at day zero. There is no production network and no permissionless features. Permissionless capabilities will be added only after public, reproducible proof of resilience to shutdown-breakdown vulnerabilities.

## Core Principles

1. Users come first. Their control and data sovereignty take priority over validators, stakers, or economic incentives.
2. We reject token models and incentive structures that encourage speculation.
3. We begin with permissioned deployments, starting with single legal entities, to protect user data.
4. Permissionless features will be introduced only when supported by clear evidence of security under adverse conditions.
5. We state what exists today without exaggeration.

## Why Commonware

Many existing frameworks rest on security assumptions that lack formal proof, especially regarding economic resilience. The commonware.xyz stack offers a more modular and better-specified foundation. We believe this provides a stronger base for systems with stronger guarantees.

## Engagement

- Most developers should work directly with the upstream commonware.xyz repositories.
- To influence direction of the subversive-stack, open issues in the Gateway repository.
- Bug reports should be filed upstream first.

This is a volunteer-driven project with no full-time team. Progress will reflect that reality.

## Shutdown-Breakdown Vulnerabilities

These definitions remain under development.

- **Shutdown** occurs when a sufficient number of network participants cease operation. A vulnerability exists if user data can still be altered afterward.
- **Breakdown** occurs when any associated token loses meaningful economic value. A vulnerability exists if user data remains alterable after this point.

We will not ship permissionless designs without public demonstrations of resilience to both.

## Changelog

- 2025-12-24: Major pivot from Substrate to commonware.xyz. Current status clarified.
- 2023-09-15: Project initiated around Substrate-based ideas.

---

This project moves deliberately. Those seeking rapid iteration or token-driven development will find little of interest here.
