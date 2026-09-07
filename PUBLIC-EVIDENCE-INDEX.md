# TruncAI-OTiX Public Evidence Index

> Status: **PUBLISHED WITH OWNER APPROVAL**
>
> Disclosure level: **D0 · PUBLIC**
>
> Baseline: **V2.1**
>
> Publication date: **2026-09-07**

## Purpose

This capsule provides a compact, non-confidential map of what a public reviewer can verify and what remains an internally reported result. It is designed for discovery, initial diligence and claim checking. It is not a source-code release, an independent audit or a production-readiness statement.

## Verification boundary

| Evidence class | What it means here |
|---|---|
| Publicly verifiable | A reviewer can inspect the cited public artifact directly. |
| Internally evidenced | The result is recorded in the controlled V2.1 evidence set but the underlying executable material is not included in D0. |
| Inconclusive | The available evidence does not support a PASS claim. |
| Not claimed | The project expressly does not assert the outcome. |

## Publicly verifiable evidence

| Item | Public artifact | What can be checked |
|---|---|---|
| Project overview | [truncaiotix.com](https://truncaiotix.com/) | Public positioning, capability boundary, limitations and contact route. |
| Machine-readable overview | [llms.txt](https://truncaiotix.com/llms.txt) | Compact project description and public discovery links. |
| Official public repository | [TruncAI-OTiX-public](https://github.com/truncai-otix/TruncAI-OTiX-public) | D0 materials, repository history and public provenance. |
| Publication history | [PUBLICATION-LOG.md](PUBLICATION-LOG.md) | Dated record of public-surface updates. |
| Capsule integrity | [CHECKSUMS.sha256](CHECKSUMS.sha256) | SHA-256 digests for the published capsule files. |

The capsule is based on public repository commit `e53487d276e0e56a1288a6af85a397450a494cf6`. That identifier anchors the public starting point; it does not attest to controlled internal materials.

## Internally reported V2.1 evidence

The following statements are drawn from the controlled V2.1 baseline. D0 does not expose the source, fixtures, detailed test procedures or full evidence bundles required for independent reproduction.

| Area | Internally reported result | Public qualification |
|---|---|---|
| Evidence Spine | 40/40 internal tests passed | Synthetic, local and limited to the evaluated V2.1 object. |
| Agent Governance | 26/26 internal tests passed | Does not prove real-world human supervision or operational deployment. |
| Assurance Lab | 30/30 internal tests passed | Includes a deterministic campaign of 10,000 virtual cases; this is not operating history. |
| Baseline Closure | 17/17 internal tests passed | Internal closure checks only. |
| Aggregate regression | 113/113 internal tests passed | Not independently reproduced or externally certified. |
| Authority boundary | C0–C2 permitted; C3–C4 prohibited in the tested object | A scoped design and test result, not an absolute security guarantee. |
| Continuity evidence | INCONCLUSIVE | Not counted as PASS. |
| Real human-review evidence | INCONCLUSIVE | Not counted as PASS. |

## High-level technical scope

V2.1 is an internal executable reference for capturing, governing, checking and replaying advisory AI trajectories in a local, synthetic, non-operational environment. Its four high-level components are:

- Evidence Spine
- Agent Governance
- Assurance Lab
- Baseline Closure

See [PUBLIC-ARCHITECTURE.md](PUBLIC-ARCHITECTURE.md) for the intentionally coarse architecture view and [PUBLIC-CLAIMS-MATRIX.md](PUBLIC-CLAIMS-MATRIX.md) for controlled public wording.

## D0 disclosure boundary

This capsule intentionally excludes:

- source code and executable packages;
- exact schemas, algorithms and policy-rule implementations;
- test fixtures, detailed test procedures and negative-test payloads;
- datasets, representative records and operational interfaces;
- dependency inventories and the controlled SBOM;
- credentials, security configuration and threat-model details;
- prompts, internal workflows and proprietary implementation detail;
- valuation, transaction, patentability and freedom-to-operate material;
- personal or future legal-entity identity details.

Controlled technical evaluation remains a separate process. Public availability of this capsule does not convert controlled material into open source and does not grant access to D1–D4.

## Explicit non-claims

TruncAI-OTiX V2.1 is not claimed to be production-ready, externally validated, industrially validated, certified, independently audited, legally compliant by default, secure against all threats, or proven in continuous operation. No operational savings, accuracy, safety or regulatory-conformity outcome is claimed.
