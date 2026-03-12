# Notes – CRN OMOP Mapping (Version v2.1)

This document contains free-form notes related to this specific version of the CRN OMOP mapping package.  
Use it to capture decisions, assumptions, discussions, and contextual information that is useful for future maintainers.

---

## 1. Purpose of This Version
- Short description of why this version was created.
- Example:
  - “Updated mappings after new NPR extract.”
  - “Aligned with new SNOMED bundle from Athena YYYY-MM-DD.”

---

## 2. Data Sources Used
List any data sources or extracts used as input for this mapping version.

- Source registry/data extract:
- Extract date (“data freeze”):
- Vocabulary packages (SNOMED, RxNorm, etc.):
- Additional reference files:

---

## 3. Mapping Decisions and Rationale
Document important decisions that were made during mapping.

Examples:
- Why a certain domain was chosen for ambiguous codes.
- Why specific ICD-O-3 → SNOMED conversions were approved.
- Notes on exclusions or interpretation of clinical codes.

Use bullet points:

- Decision:
- Rationale:
- Alternatives considered (optional):

---

## 4. Known Issues or Limitations
If something is not fully mapped or requires follow-up:

- Partially mapped codes:
- Codes lacking standard concepts:
- Issues in lookup Excel:
- Pending validations:
- Deprecations or outdated source codes:

---

## 5. Validation Notes
Anything related to quality checks:

- Issues found during manual review
- Cross-checks done in USAGI
- QA tests that passed or failed
- Any DQD-related comments (if applicable)

---

## 6. Dependencies or External Inputs
If this version depends on:

- Specific R scripts or ETL scripts
- External specifications
- Decisions from domain experts
- Vocabulary releases

List them here.

---

## 7. To-Do for Next Version
Optional, but very useful for iterative work:

- Tasks that should go into vX.(Y+1)
- Codes requiring further review
- Proposed improvements to ETL-spec
- Additions planned for next release

---

## 8. Additional Notes
Anything else you want to capture:

- Meeting notes (short)
- Clarifications from domain experts
- Email decisions
- Technical issues encountered

---
