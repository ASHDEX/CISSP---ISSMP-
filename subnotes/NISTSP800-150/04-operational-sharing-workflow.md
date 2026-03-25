# 04 - Operational Participation Workflow (Section 4)

## Core Operational Activities
- Ongoing communication with sharing communities.
- Consume and respond to security alerts.
- Consume and use indicators.
- Organize/store indicators.
- Produce/publish indicators (mature organizations).

## Alerts: Practical Response Model
- Confirm source trustworthiness.
- Assess scope and impact (affected assets, mission effect, severity).
- Prioritize mitigation (patches, config changes, signatures, controls).
- Automate indicator extraction/handling where possible.

## Indicator Processing Pipeline
1. Validation (integrity/provenance checks)
2. Decryption
3. Decompression
4. Content extraction
5. Prioritization
6. Categorization (designation and handling requirements)

## Good Indicator Characteristics
- Timely
- Relevant
- Accurate
- Specific
- Actionable

## Knowledgebase Guidance
- Store source, use rules, timestamps, validity window, associated CVE/CWE/CPE/CCE, actor/TTP links.
- Protect repository (access control, backup, patching, secure development).
- Define retention/disposal with legal and evidence requirements in mind.

## Publishing Indicators
- Include context metadata, provenance, sensitivity tags, and update/retraction mechanism.
- Use standard machine-readable formats for interoperability and speed.
- Protect data in transit and at rest, and enforce sharing rules with trusted recipients.

Source: [NISTSP800-150.pdf](NISTSP800-150.pdf)
