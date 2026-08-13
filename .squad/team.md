# Squad Team

> RssReaderApp (Aspiregregator)

## Coordinator

| Name | Role | Notes |
|------|------|-------|
| Squad | Coordinator | Routes work, enforces handoffs and reviewer gates. |

## Members

| Name | Role | Charter | Status |
|------|------|---------|--------|
| aspire-apphost-engineer | Aspire AppHost & Orchestration Engineer | `.squad/agents/aspire-apphost-engineer/charter.md` | ✅ Active |
| orleans-grains-developer | Orleans Grains Developer | `.squad/agents/orleans-grains-developer/charter.md` | ✅ Active |
| feed-ingestion-worker-developer | Feed Ingestion Worker Developer | `.squad/agents/feed-ingestion-worker-developer/charter.md` | ✅ Active |
| blazor-frontend-developer | Blazor Frontend Developer | `.squad/agents/blazor-frontend-developer/charter.md` | ✅ Active |
| data-persistence-engineer | Data & Persistence Engineer | `.squad/agents/data-persistence-engineer/charter.md` | ✅ Active |
| observability-service-defaults-engineer | Observability & Service Defaults Engineer | `.squad/agents/observability-service-defaults-engineer/charter.md` | ✅ Active |

## Always-On Support

| Name | Role | Notes |
|------|------|-------|
| Scribe | Session Logger | Merges decisions, writes orchestration/session logs. |
| Ralph | Work Monitor | Continuous scan → act → rescan loop when active. |
| Rai | RAI Reviewer | Responsible AI review — credentials, safety, fairness. |
| Fact Checker | Fact Checker | Claim verification + Devil's Advocate analysis. |

## Coding Agent

| Name | Role | Notes |
|------|------|-------|
| @copilot | Coding Agent | `copilot-auto-assign: false` |

## Project Context

- **Project:** RssReaderApp (Aspiregregator) — .NET 9 / .NET Aspire distributed RSS reader
- **Architecture:** AppHost (Aspire orchestration) + Grains/Abstractions (Orleans) + FeedUpdater (worker) + Frontend (Blazor/FluentUI) + Defaults (service defaults)
- **Created:** 2026-08-13
