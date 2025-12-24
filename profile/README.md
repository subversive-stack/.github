# Subversive Stack: Not DeFi. Not Web3. 

The Subversive Stack is an opinionated framework for developing **secure distributed ledgers - SDL (pronounced: Saddle)**, focused on empowering end-users. We adopt or build tools that prioritize privacy, security, and real-world utility—without promoting token or coin speculation. Our mission: Place users front and center through principled open-source development.

## Overview

Subversive Stack provides a curated set of tools and primitives for building SDL networks. We're pivoting (from Polkadot to Commonware), to leverage the lightweight and efficient [commonware.xyz](https://commonware.xyz) stack for core functionality, emphasizing data security and end-user privacy. Permissionless configurations, including `commonware-consensus`, remain out of scope until proven secure against shutdown-breakdown vulnerabilities.

## Core Opinions

1. **User-Centric Design**: End users come first. Validators, miners, stakers, and similar roles are not our primary focus.  Tools for developers and users who value control and verifiable security.
2. **No Speculative Incentives**: We maintain designs free from economic models that encourage value speculation; emphasis remains on sustainable infrastructure.
3. **Permissioned by Default**: We prioritize SDLs to ensure user data security. This is currently our core, and only, use case.
4. **Permissionless with Proof**: Permissionless features will only be integrated upon public proof and demonstration of resilience to shutdown-breakdown vulnerabilities.
5. **Phased Evolution**: Beginning with permissioned environments (single legal entity); permissionless features (e.g., `commonware-consensus`) remain out of scope until secure configurations are mathematically proven, and implemented.
6. **Not DeFi. Not Web3.**: Our approach centers on SDLs, distinct from broader ecosystems reliant on unproven assertions of security and safety.

## Shutdown-Breakdown Vulnerabilities

This section is a work-in-progress. Contributions to refine these definitions are welcome—open an issue in the [Gateway repository](https://github.com/subversive-stack/gateway).

- **Shutdown**: Occurs when all, or some threshold of, network/protocol security-participants (e.g., operators, validators) cease activity. Public code and resources remain accessible; Private code and resources remain in place. Vulnerability exists if user data can be altered post-shutdown.
- **Breakdown**: Happens when any associated token price drops to "zero", or some threshold value. Vulnerability exists if user data can be altered afterward. The "zero/breakdown" boundary is critical; resource costs for attacks (e.g., 51%) beyond this point are irrelevant to this definition.

If you have a proof of invulnerability and a reproducible demo, submit an issue in the [Gateway repository](https://github.com/subversive-stack/gateway) with links and reproduction steps.

## Related Organizations

- **[Subversive Upstream](https://github.com/subversive-upstream)**: Tracks upstream repositories (e.g., commonware.xyz components) that constitute our stack.
- **[Subversive Crates (TBC)](https://github.com/subversive-crates)**: Forked repositories from upstream sources, tailored for Subversive Stack. Only included when actively used here. To Be Completed.

## Resources

- **Bug Reports**: Use upstream repository "Issues" with a minimal reproducible example (code or repo link). If upstream rejects the issue, open an issue in the repo under this org, linking to the upstream issue.
- **Help & Discussion**: To Be Decided.
- **Documentation**: For commonware.xyz specifics, refer to their documentation until Subversive-Stack diverges significantly. Additional guides coming soon(TM).

## Contribution Guidelines

Why Contribute?: Develop secure distributed ledgers that serve users through verified mechanisms, separate from speculative markets.

We operate as an old-school open-source project: Volunteer-driven, with strengths in community focus and limitations in resources. Submit issues/PRs that align with our emphasis on secure, non-speculative designs.

Influence Subversive's direction via issues in the [Gateway repository](https://github.com/subversive-stack/gateway). Remember: We're speculation-free by design and committed to user-first innovation. This is volunteer-driven open source—no full-time team. Expect the strengths (community-driven evolution) and limitations (slower pace) of that model.

### Current Focus: Pivot to Commonware.xyz

We have shifted from traditional blockchain primitives—based on unproven security assumptions, including lack of formal proofs for minimal thresholds and token-value exceeding minimum thresholds — to more agnostic primitives initally via a subset of the commonware.xyz stack. This enables verified, permissioned networks while addressing limitations in assumed-secure systems. Key components include:

- Core runtime and primitives for permissioned (single legal entity) distributed ledgers.
- Tools for privacy-preserving applications and user-controlled data.

Repositories in this org are forks, or adaptations from upstream sources (when required), customized for the Subversive-Stack's opinionated approach.

### Guidance for Developers

- **Don't Fork Here**: Fork from the original upstream repos to avoid fragmentation.
- **Issues & PRs**: Open them in upstream repos. We monitor for alignment with our principles but have no full-time team — contributions are community-driven.

## Change Log

- **2025-12-24**: Pivoted to commonware.xyz stack; clarified scope exclusion for permissionless features. (Initial log entry.)
- **2023-09-15**: Initial release using Substrate (breaking out the upstream Polkadot-SDK monorepo).
