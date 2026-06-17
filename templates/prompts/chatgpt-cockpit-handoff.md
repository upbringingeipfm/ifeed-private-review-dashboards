# ChatGPT Fallback Prompt: Cockpit Handoff Database

Convert the selected weekly refined register into a cockpit-friendly database.

For every signal include:
- id
- title
- date
- source_url
- domain_group
- reader_group
- decision_status
- source_audit
- evidence_posture
- why_it_matters
- editorial_use
- duplicate/prior coverage
- confidence
- notes

Return valid JSON using schema version `ifeed-cockpit-handoff-v1`.
