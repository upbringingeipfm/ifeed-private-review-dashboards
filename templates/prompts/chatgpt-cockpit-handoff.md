# ChatGPT Fallback Prompt: Cockpit Handoff Database

Convert the selected weekly refined register into a cockpit-friendly database.

Purpose:
This is not public copy. It is a private operating view for reviewing the week, seeing what was selected or dropped, and preserving source/claim-risk reasoning.

For every signal include:
- id
- title
- date
- source_url
- source_type
- origin_tools
- domain_group
- reader_group
- decision_status
- source_audit
- evidence_posture
- why_it_matters
- editorial_use
- duplicate/prior coverage
- confidence
- verification_status
- placement: selected_9 | preliminary_20 | alternative | watch | ireland_india | drop
- notes

Also include:
- dashboard_filters
- selection_summary
- verification_backlog
- dropped_noise_summary

Return valid JSON using schema version `ifeed-cockpit-handoff-v1`.
