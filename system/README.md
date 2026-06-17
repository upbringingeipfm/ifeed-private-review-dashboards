# iFeed Signal Management System

This folder is the working system for weekly signal capture and conversion.

## What Stays Constant

- Tool lanes: Codex, ChatGPT, Claude, Perplexity, DeepSeek, Gemini, miscellaneous.
- Seven-layer lens.
- Raw capture file names.
- Database schema progression.
- Private dashboard route.
- Cockpit handoff route.
- Public weekly digest handoff structure.
- Source and claim-boundary policy.

## What Changes Each Week

- Week number and date range.
- Raw pasted outputs from tools.
- Refined signal register.
- Selected preliminary 20.
- Final 9.
- Public story framing.
- Visual card content.

## Workflow

1. Open `/system/`.
2. Select week and tool.
3. Copy the tool-specific prompt.
4. Paste the prompt into the chosen external tool.
5. Paste the returned raw output into the raw capture workspace.
6. Export the Markdown file into `/weeks/w25/raw/`.
7. Use Codex to process all raw files into the staged JSON databases.
8. If Codex is unavailable, use the ChatGPT fallback prompts in `/templates/prompts/`.
9. Generate or update the private weekly dashboard.
10. Promote selected signals into cockpit handoff.
11. Generate final publish database for the iFeed Weekly Signals template.

## Browser Limitation

A static Netlify page cannot silently write into a local Obsidian vault or GitHub repository. It can:

- store temporary work in browser localStorage,
- copy prompts,
- download Markdown files,
- download stage JSON files.

Codex or a local helper script can perform the direct file-writing step when available.
