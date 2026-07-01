# Magpie Capital — Security Audits

This repository is the canonical, public home for Magpie Capital's third-party
security audit reports. When an engagement is complete and a report is cleared
for publication, the report (PDF) and a summary entry are committed here.

> **Status:** Magpie's smart-contract audit process is **actively underway**.
> The protocol is **not yet audited**. Independent security firms have been
> **engaged to review** the on-chain lending programs; **reports will be
> published here when complete.** Please do not treat the absence of a published
> report as a completed review.

## Engagements

| Firm | Scope | Status | Report |
| --- | --- | --- | --- |
| **Sec3** | Magpie V4 program (`magpie-v4`) — in-vault auto-sell | Access granted; **scoped estimate received (V4 program)** — scope + engagement being finalized | Pending |
| **Hashlock** | Full protocol (V4 flagship + V1/V3 + supporting, ~7,700 LOC Rust/Anchor) | Accepted collaborator; formal proposal received — engagement being finalized | Pending |
| **QuillAudits** | Full-stack security — on-chain lending programs (`magpie-v4`) + supporting protocol surfaces | Repository access accepted; **full-stack security proposal received** — engagement being finalized, review underway | Pending |
| **OtterSec** | Magpie on-chain lending programs (`magpie-v4`) | Invited to audit; awaiting response | Pending |
| **Neodyme** | Magpie on-chain lending programs (`magpie-v4`) | Invited to audit; awaiting response | Pending |

**"Report: Pending"** means no report exists yet — it does not mean a report is
being withheld. When a report is published, its row will link to the PDF in this
repository, and (where the firm publishes its own report set) to the firm's
public copy for independent cross-checking.

## How this repository works

- The audit-target program lives in **`magpiecapital/magpie-v4`**, which is kept
  **private** during pre-audit review. Engaged firms are added as **read-only**
  collaborators.
- When a report is completed and cleared for publication, it is committed under
  `reports/`, the **Engagements** table above is updated with a link, and the
  report's status changes from _Pending_ to a dated entry.
- All public Magpie surfaces share one status sentence and are updated together,
  so the audit status never drifts between pages.

## Reporting a vulnerability

This repository is for published audit reports, not for vulnerability reports.
To report a security issue, see our security policy and
**https://magpie.capital/security**, or use the private "Report a vulnerability"
flow on the affected repository's **Security** tab.

---

_Maintained by Magpie Capital. Status: audit process underway · firms engaged
for review · report shared when complete._
