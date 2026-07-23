<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile-banner-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile-banner-light.png">
  <img alt="Renan Melo — verifiable systems across blockchain infrastructure, real-time products and agent runtimes" src="./assets/profile-banner-dark.png" width="100%">
</picture>

<div align="center">

# Renan Melo

### Blockchain & Agentic Systems Engineer

I build verifiable systems across blockchain infrastructure,<br>
real-time products and agent runtimes.

<br>

<a href="https://renan.snelabs.space"><img alt="Open portfolio" src="https://img.shields.io/badge/Portfolio-Open-111827?style=for-the-badge"></a>
<a href="https://linkedin.com/in/renan-melo-connexions"><img alt="Connect on LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin"></a>
<a href="mailto:byrenanmelo@gmail.com"><img alt="Contact by email" src="https://img.shields.io/badge/Email-Contact-262626?style=for-the-badge&logo=gmail"></a>

<br><br>

São Paulo, Brazil · Open to remote engineering and product collaboration

</div>

## System philosophy

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/system-philosophy-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/system-philosophy-light.png">
  <img alt="Explicit contracts lead to authoritative state, observable execution, deterministic validation and operational evidence" src="./assets/system-philosophy-dark.png" width="100%">
</picture>

## Flagship

<table>
  <tr>
    <td width="48%" valign="top">
      <a href="https://vira.snelabs.space/?lang=en">
        <img src="./assets/vira-preview.png" alt="VIRA synchronized match room with a resolved challenge" width="100%">
      </a>
    </td>
    <td width="52%" valign="top">
      <h2>VIRA</h2>
      <p><code>ACTIVE — LIVE PUBLIC DEPLOYMENT</code></p>
      <p>Synchronized multiplayer football challenges resolved through authoritative match evidence.</p>
      <p><strong>Verified properties</strong></p>
      <ul>
        <li>Server-owned deadlines</li>
        <li>Private pre-lock answers</li>
        <li>Deterministic replay</li>
        <li>Hash-chained event ledger</li>
        <li>Live SSE projections</li>
      </ul>
      <p>
        <a href="https://vira.snelabs.space/?lang=en">Live</a> ·
        <a href="https://github.com/4LFR3Dv1/VIRA-">Source</a> ·
        <a href="https://www.youtube.com/watch?v=LnOd2kWTiGA">Demo</a> ·
        <a href="https://vira.snelabs.space/public/playback">Playback</a>
      </p>
    </td>
  </tr>
</table>

![VIRA status](https://img.shields.io/badge/status-live_public_deployment-16a34a)
![VIRA CI](https://img.shields.io/github/actions/workflow/status/4LFR3Dv1/VIRA-/verify.yml?branch=main&label=verification)
![VIRA tests](https://img.shields.io/badge/core_tests-145_passing-16a34a)
![VIRA license](https://img.shields.io/badge/license-not_selected-6b7280)

<details>
<summary><strong>Architecture, evidence and current limitations</strong></summary>

<br>

The browser never decides the deadline, result or ranking. The server admits private answers, locks each round, resolves against eligible TxLINE observations and rebuilds public projections from append-only history.

- The permanent playback uses a disclosed, sanitized captured TxLINE fixture.
- The current event store is intentionally single-writer.
- Solana commitment is asynchronous and does not control resolution.
- No external security audit or public license is claimed.

[Architecture](https://github.com/4LFR3Dv1/VIRA-/blob/main/docs/ARCHITECTURE.md) ·
[Integrity model](https://github.com/4LFR3Dv1/VIRA-/blob/main/docs/INTEGRITY_MODEL.md) ·
[Security](https://github.com/4LFR3Dv1/VIRA-/blob/main/docs/SECURITY.md) ·
[Evaluation guide](https://vira.snelabs.space/help?lang=en)

</details>

## Proof strip

<table>
  <tr>
    <td align="center" width="25%"><strong>● Live systems</strong><br>Public runtime probes</td>
    <td align="center" width="25%"><strong>✓ Deterministic replay</strong><br>State rebuilt from history</td>
    <td align="center" width="25%"><strong>✓ Passing CI gates</strong><br>Build, tests and verification</td>
    <td align="center" width="25%"><strong>△ On-chain evidence</strong><br>Scoped devnet commitments</td>
  </tr>
</table>

## Verification paths

| System | Runtime | Repository | Verification | Evidence |
| --- | --- | --- | --- | --- |
| **VIRA** | ● Live | [Source](https://github.com/4LFR3Dv1/VIRA-) | Tests + [CI](https://github.com/4LFR3Dv1/VIRA-/actions/workflows/verify.yml) | [Playback](https://vira.snelabs.space/public/playback) + [readiness](https://vira.snelabs.space/ready) |
| **Solana Agent** | ◐ Pre-alpha | [Source](https://github.com/4LFR3Dv1/Solana-Agent) | Tests + pinned-toolchain CI | Stable sanitized devnet pack pending |
| **Portfolio** | ● Live | [Source](https://github.com/4LFR3Dv1/Portfolio) | `npm run verify` + CI | [Evidence room](https://renan.snelabs.space) |
| **Anchor Counter** | ◐ Devnet artifact | [Source](https://github.com/4LFR3Dv1/Web3Experts-Solana-Zero-to-Hero-2-Deploy-Your-First-Anchor-Program) | Anchor test | Program + transaction links |

## Selected systems

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/4LFR3Dv1/Solana-Agent">Solana Agent Runtime</a></h3>
      <p><code>ACTIVE — PRE-ALPHA</code></p>
      <p>Governed runtime for bounded Solana engineering missions.</p>
      <p><strong>Proof:</strong> contracts · policies · approvals · journal · CI</p>
      <p><a href="https://github.com/4LFR3Dv1/Solana-Agent">Repository</a> · <a href="https://github.com/4LFR3Dv1/Solana-Agent/tree/main/docs">Architecture</a> · <a href="https://github.com/4LFR3Dv1/Solana-Agent/actions">CI</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/4LFR3Dv1/Portfolio">Portfolio</a></h3>
      <p><code>ACTIVE — LIVE PUBLIC DEPLOYMENT</code></p>
      <p>Bilingual evidence room for architecture, responsibility and public proof.</p>
      <p><strong>Proof:</strong> live cases · verification gate · CI</p>
      <p><a href="https://renan.snelabs.space">Live</a> · <a href="https://github.com/4LFR3Dv1/Portfolio">Repository</a> · <a href="https://renan.snelabs.space">Evidence room</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/4LFR3Dv1/Agentic-Engineering">Agentic Engineering</a></h3>
      <p><code>PROPOSED — NOT YET BUILT</code></p>
      <p>Public grant package separating prior work, future deliverables and acceptance criteria.</p>
      <p><strong>Proof:</strong> scope · threat boundaries · workflow evidence</p>
      <p><a href="https://github.com/4LFR3Dv1/Agentic-Engineering">Application</a> · <a href="https://github.com/4LFR3Dv1/Agentic-Engineering/tree/main/docs">Documents</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/4LFR3Dv1/EditalSales">EditalSales</a></h3>
      <p><code>EXPERIMENTAL — HARDENING</code></p>
      <p>Opportunity radar and CRM with ingestion, local fallbacks and optional AI enrichment.</p>
      <p><strong>Proof:</strong> reproducible build · persistence tests · CI</p>
      <p><a href="https://github.com/4LFR3Dv1/EditalSales">Repository</a> · <a href="https://github.com/4LFR3Dv1/EditalSales/actions">Verification</a></p>
    </td>
  </tr>
</table>

<details>
<summary><strong>Solana Agent architecture visualization</strong></summary>

<br>

This is a conceptual map of the governed runtime — not a screenshot of a released product interface.

<img src="./assets/solana-agent-architecture.png" alt="Conceptual architecture visualization for the Solana Agent governed runtime" width="100%">

</details>

## Engineering focus

<table>
  <tr>
    <td width="33%" valign="top"><h3>Authority</h3><p>Server-owned state, explicit deadlines, serialized mutation and fail-closed decisions.</p></td>
    <td width="33%" valign="top"><h3>Evidence</h3><p>Append-only ledgers, deterministic replay, decision receipts and operational probes.</p></td>
    <td width="33%" valign="top"><h3>Agents</h3><p>Bounded tools, policy profiles, approvals, durable journals and human review.</p></td>
  </tr>
  <tr>
    <td width="33%" valign="top"><h3>Financial systems</h3><p>Self-custody boundaries, local-first execution and transaction-safety research.</p></td>
    <td width="33%" valign="top"><h3>Real-time products</h3><p>SSE, WebSockets, provider normalization and resilient projections.</p></td>
    <td width="33%" valign="top"><h3>Security practice</h3><p>Threat modeling, least authority, secret boundaries and residual-risk documentation.</p></td>
  </tr>
</table>

## Technology

**Systems:** TypeScript, Go, Python, Node.js, FastAPI, gRPC, SQLite, PostgreSQL<br>
**Interfaces:** React, Electron, Vite, SSE and WebSockets<br>
**Blockchain:** Solana, Anchor, Bitcoin, Liquid and Lightning<br>
**Delivery:** Docker, GitHub Actions, Playwright, Vitest, pytest and deterministic test harnesses

## Contact

[Portfolio](https://renan.snelabs.space) ·
[LinkedIn](https://linkedin.com/in/renan-melo-connexions) ·
[Email](mailto:byrenanmelo@gmail.com)
