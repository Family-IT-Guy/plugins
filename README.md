# Family IT Guy Plugins

Claude Code plugin marketplace by Family IT Guy.

## Install

```bash
# Add the marketplace (one-time)
claude plugins marketplace add Family-IT-Guy/plugins

# Install a plugin
claude plugins install rule-creator@familyitguy
```

Restart Claude Code after installing. To update later:
`claude plugins marketplace update familyitguy`.

## Available Plugins

| Plugin | What it does |
|--------|--------------|
| `rule-creator` | Write the smallest instruction that actually changes how your AI behaves — a custom-instructions block, a CLAUDE.md/AGENTS.md/GEMINI.md rule, or a skill — fitted to your harness and proven with a before/after demo. |
| `afk` | Set the autonomous working contract for when you step away. Claude does the most valuable work it safely can unsupervised — no production changes, nothing sent, no metered spend — and hands you a clean decision queue when you're back. |
| `assess` | Critique how you're directing the model — sharpen your prompt against the question-method lenses instead of executing it. Summon with `/assess`. |
| `catch-me-up` | Come back to a session after time away and get re-oriented: it reads your project's state docs and git history, reconciles them against the conversation, and hands back a briefing plus the questions you haven't asked yet. Summon with `/catch-me-up`. |
| `research-engine` | Cited web research via Perplexity Sonar API. Background sub-agents, primary-source verification, cascade follow-ups, persistent thread files. |
| `youtube-ingest` | Ingest YouTube video transcripts, metadata, and search results via yt-dlp. No API key needed. |
| `qa-webapp` | Comprehensive 7-phase QA for any web app — functional, visual, performance, accessibility, security, cross-browser, failure-mode, and edge-case testing across a local → preview → prod pipeline. Separates analysis from remediation and lets you set scope and priority. No credentials of its own; needs `playwright-cli`. Summon with `/qa-webapp`. |
