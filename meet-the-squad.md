# Meet the Squad

**Project:** RssReaderApp (Aspiregregator)
**Naming style:** Descriptive, role-based (no themed universe)

## Team

| Name | Role | Specialty | How to talk to them |
|------|------|-----------|----------------------|
| aspire-apphost-engineer | Aspire AppHost & Orchestration Engineer | Aspire resource wiring, Azure Storage/Orleans clustering references, deployment manifests | Assign issues labeled `squad:aspire-apphost-engineer` |
| orleans-grains-developer | Orleans Grains Developer | `SourceGrain`/`SourceLibraryGrain`, grain persistence, `Abstractions` interfaces, feed parsing | Assign issues labeled `squad:orleans-grains-developer` |
| feed-ingestion-worker-developer | Feed Ingestion Worker Developer | `FeedUpdater` worker service, feed refresh scheduling | Assign issues labeled `squad:feed-ingestion-worker-developer` |
| blazor-frontend-developer | Blazor Frontend Developer | `Frontend` Blazor components, ViewModels, FluentUI | Assign issues labeled `squad:blazor-frontend-developer` |
| data-persistence-engineer | Data & Persistence Engineer | EF Core/SQL Server, Azure Storage tables/blobs | Assign issues labeled `squad:data-persistence-engineer` |
| observability-service-defaults-engineer | Observability & Service Defaults Engineer | `Defaults` project — OpenTelemetry, service discovery, resilience | Assign issues labeled `squad:observability-service-defaults-engineer` |

## Always-On Support

| Name | Role | What they do |
|------|------|---------------|
| Scribe | Session Logger | Merges decisions, writes orchestration/session logs |
| Ralph | Work Monitor | Continuous scan → act → rescan loop when active |
| Rai | RAI Reviewer | Responsible AI review of code, content, and decisions |
| Fact Checker | Fact Checker | Verifies claims and plays devil's advocate on plans |

## How to Work With Your Squad

- Label an issue `squad:{agent-name}` (color `9B8FCC`) to route it to that specialist.
- Use `/squad research`, `/squad plan`, `/squad triage` to iterate before implementation.
- See `.squad/routing.md` for the full domain → agent routing table.
- `@copilot` is on the roster with `copilot-auto-assign: false` — assign manually when appropriate.

## What Happened Here

This squad was cast from GitHub issue #1, which explicitly described the repository's
.NET 9 / .NET Aspire architecture and requested descriptive, role-based agent names
mapped 1:1 to the codebase's projects:

- **AppHost** → Aspire AppHost & Orchestration Engineer
- **Grains + Abstractions** → Orleans Grains Developer
- **FeedUpdater** → Feed Ingestion Worker Developer
- **Frontend** → Blazor Frontend Developer
- **EF Core / Azure Storage usage** → Data & Persistence Engineer
- **Defaults** → Observability & Service Defaults Engineer

No fictional universe was used — all names describe what each agent owns, per the
issue's explicit request.

---
*Cast on 2026-08-13*
