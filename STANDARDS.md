# Standards

## Where standards live

All canonical standards documents live in
[constraint-spine](https://github.com/C-Zenno/constraint-spine).
This file describes the discipline; the spine contains the substance.

## Versioning

The canon is versioned via git tags (`public-spine-v0`, `v0.1`, etc.).
Each tag is a citable, immutable snapshot. Citations should reference
the tag, not a branch head.

Format: `constraint-spine, tag: public-spine-vN`

Every edit to the spine is a governance event: reviewed, diffable,
and tagged before it becomes citable.

## Receipt discipline

Constraint Physics operates on a **claims/receipts/refusal** model:

- A **claim** is a bounded statement about what was observed or computed,
  declared under explicit posture constraints.
- A **receipt** is a provenance record that makes a claim auditable —
  who declared it, under what bounds, at what version.
- A **refusal** is a legitimate output: the system may decline to produce
  a claim when conditions are outside declared bounds.

This is not an ethics framework. It is a record-keeping discipline.
Claims are bounded. Receipts are verifiable. Refusal is structural,
not moral.

## What standards do not contain

- Schemas, wire formats, or data models (those are operational)
- Threshold definitions or trigger conditions
- Procedures for how to produce or validate claims
- Certification mechanics or compliance checklists

Standards describe what the field requires of its records.
They do not describe how to build systems that produce those records.

## Current standard documents

→ [Canon Policy](https://github.com/C-Zenno/constraint-spine/blob/main/CANON.md)
→ [ADR-0008: Canon = versioned docs](https://github.com/C-Zenno/constraint-spine/blob/main/registry/DECISIONS/ADR-0008.md)
→ [CRL-0 License Posture](https://github.com/C-Zenno/constraint-spine/blob/main/docs/licenses/CRL-0.md)
→ [OEL-1 License Posture](https://github.com/C-Zenno/constraint-spine/blob/main/docs/licenses/OEL-1.md)
