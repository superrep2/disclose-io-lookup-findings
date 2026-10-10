# Disclose.io Lookup Findings — 2026-10-10

Technical record of security contact resolution via the official Disclose.io Lookup MCP server (`https://lookup.disclose.io/mcp`).

## Assets examined
- `npm:lodash`
- `gh:anthropics/claude-code`
- `1.1.1.1`
- `app:Signal`
- `microsoft.com`

## Key results (high-confidence routes)

| Asset | Status | Primary Route | Organization |
|-------|--------|---------------|--------------|
| npm:lodash | COMPLETE | first_party VDP | lodash/lodash |
| gh:anthropics/claude-code | COMPLETE | first_party VDP + HackerOne | Anthropic (US) |
| 1.1.1.1 | PARTIAL | responsible_operator | Cloudflare (AU) |
| app:Signal | PARTIAL | responsible_operator | Signal Foundation |
| microsoft.com | COMPLETE | first_party bug bounty | Microsoft Corporation (US) |

Full contact tables, resolution chains, confidence scores, and sources are in the session log.

## Files
- [`session-log-2026-10-10.txt`](session-log-2026-10-10.txt) — full chronological thread log
- Technical PDF (5 pages) generated from the same findings: available in the originating conversation (ReportLab letter format covering methodology, VDP vs HackerOne, detailed tables, disclaimer).

## Notes
Results are evidence-backed leads for responsible disclosure only. Verify published policy and scope before any report. Disclose.io does not invent contacts.

Generated 2026-10-10 via Grok using the hosted MCP endpoint (protocol 2024-11-05, server `lookup-disclose-io` v2.0.0).
