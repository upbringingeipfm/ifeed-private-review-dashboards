# ChatGPT Fallback Prompt: Public Weekly Digest Database

Create the public iFeed Weekly Signals publish database from the final 9.

Rules:
- No overclaiming.
- Use careful source language.
- Make every signal a useful story, not random news.
- Each signal needs headline, short story, what happened, why it matters, claim boundary, Monday move, source label, source URL, date, right-side visual card content, and screenshot-safe expanded card text.
- Separate private review reasoning from public copy.
- Avoid naming weak secondary claims as confirmed fact.
- Use "reported", "announced", "published", "opened", "proposed", or "asked for comment" only when the source supports that verb.
- If a signal is regulatory guidance, do not imply approval.
- If a signal is AI model/tool news, distinguish access, validation, deployment, qualification, and regulatory acceptance.
- Each public story should teach the reader something practical.

Return valid JSON using schema version `ifeed-weekly-publish-v1` with:
- issue metadata
- final 9 signals
- homepage card summary
- expanded card content
- right-side visual card content
- source list
- public claim-boundary notes
