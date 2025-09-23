---
id: 70_diagrams
version: 1.0.2
uses: ./00_master_context.md
output:
  - /05_Diagrams/wallet_design_flow.mmd
  - /05_Diagrams/wallet_sequence.mmd
status: draft
---

## Objective
Generate **two separate Mermaid diagrams** visualizing the custody model and transaction flow for **Parent-Owned LLC**.

## Must-use context
- OpsCo is always legal owner of BTC, holding ≥1 key.
- Parent-Owned LLC coordinates XPUBs but has no unilateral control.
- Senior Technician supervises Juniors and reviews logs.
- Employees act as custodial agents, not beneficial owners.

## Requirements

### 1. Wallet Design Flowchart (`wallet_design_flow.mmd`)
- Show OpsCo, Parent-Owned LLC, Senior Tech, Junior Tech, and Key Management Policy.
- Use `<br/>` for line breaks in labels.
- Use simple `["Label"]` rectangle syntax.
- No fancy bullets or unicode.

### 2. Wallet Transaction Flow (`wallet_sequence.mmd`)
- Show transaction lifecycle from OpsCo request → Manager PSBT build → Senior & Junior sign → broadcast.
- Use simple participant names (OpsCo, Manager, Senior, Junior, Network).
- No `autonumber`, no aliases.

## Constraints
- Mermaid syntax only.
- GitHub-compatible (no unicode, no `[[[ ]]]`, no `\n`).
- Each diagram in its own file.

## Acceptance
- Output must be two `.mmd` files under `/05_Diagrams/`.
- Must render without errors on GitHub.
