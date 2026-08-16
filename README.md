# Agentic Cinema: The Blockbuster Hackathon

Hackathon submission repo.

## Official page

**https://agentic-cinema.devpost.com/**

| | |
|---|---|
| Devpost page | <https://agentic-cinema.devpost.com/> |
| Official rules | <https://agentic-cinema.devpost.com/rules> |
| Resources | <https://agentic-cinema.devpost.com/resources> |
| Deadline | **Sep 7, 2026 @ 2:00pm PT per official rules (Devpost card says Sep 9 — VERIFY)** |
| Submission window | Jul 27, 2026 09:00 PT – Sep 7, 2026 14:00 PT |
| Format | Online |

## Required stack

- **Google Cloud** + **Agent Builder** (Gemini)
- One **Partner track** product: IBM · Grafana · Clickhouse · Replit · Parallel
- Must run on web, Android, or iOS

⚠️ **Google-only AI.** Rules: *"No other AI models, agent frameworks, or AI APIs are permitted, regardless of vendor — this includes but is not limited to AWS, Microsoft, OpenAI, and Anthropic AI tools."* Domain must target filmmakers, screenwriters, studio crews, or fans. Team max 4.

## Partner tracks — pick exactly one

Each has a *runtime* integration test. Naming the partner in the README does not count.

| Track | What is actually checked |
|---|---|
| **Parallel** | Parallel's **Search API called at runtime** — official `parallel-web` SDK (Python/TS), Vercel AI SDK `@parallel-web/ai-sdk-tools`, LangChain `ParallelWebSearchTool`, or Grounding with Parallel Web Search as provider |
| **ClickHouse** | ClickHouse used at runtime via the official **`mcp-clickhouse`** MCP server against a Cloud or self-hosted cluster. ClickHouse Agent Skills optional |
| **Grafana** | Grafana stack at runtime, primarily the **Grafana Cloud MCP server** (`grafana/mcp-grafana` or hosted endpoint). AI Observability alone does *not* satisfy it — the MCP connection is what's checked |
| **IBM** | Must be **built using IBM Bob** as part of development. Confluent optional but encouraged. No IBM Bob usage = track requirement not met "regardless of how the code was written" |
| **Replit** | Built with **Replit Agent** *and* deployed on Replit (`replit.app` / `replit.dev` URL) |

Lowest friction for a solo entry: **Parallel** (one API integration) or **ClickHouse** (one MCP
server). IBM and Replit constrain your whole development process, not just the code.

## Accepted Google Cloud SDKs

`google-adk` · `google-genai` · `google-generativeai` · `google-cloud-aiplatform`
(any generation — legacy libraries count equally). Must be **imported and actually called** — a
library import, an app/backend entry point, or a loaded agent/flow/MCP config. Not just referenced.

## Submission checklist

- [x] **Public + open source with a license file** (MIT — required; detectable at the top of the
      repo page / About section)
- [ ] Public repo with all source, assets and run instructions, demonstrating Google Cloud **and**
      the partner service **at runtime in code**
- [ ] Hosted Project URL for judging and testing
- [ ] Demo video
- [ ] Text description — features, technologies used, data sources, findings and learnings
- [ ] Runs on web, Android, or iOS
- [ ] Submitted on Devpost before the deadline

## Originality

⚠️ **Strictest of the five** — must be *"Your original creation, not a modification or extension of Your or anyone else's existing work."* Build clean-room; share nothing with the other repos.

---

*Rules summarised from the official page on 2026-08-16. The official rules govern — re-check before submitting.*
