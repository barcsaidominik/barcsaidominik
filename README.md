## Dominik Barcsai

.NET backend developer from Budapest with five years of C#, ASP.NET Core and SQL Server in client projects, and an MSc in Cyber Security Engineering (Óbuda University, 2026).

I mostly work on backend services: microservices with RabbitMQ and MassTransit, REST and contract-first APIs, background jobs, reporting and query performance. As a deputy tech lead I also review code and mentor junior and mid-level developers. On the security side, I care about what can be checked automatically in a pipeline and about writing down what is *not* covered.

### Public projects

| Project | What it is |
|---|---|
| [SecurityToolkit](https://github.com/barcsaidominik/SecurityToolkit) | A .NET 10 CLI that installs into a .NET/Angular repository and runs pinned security scanners (Semgrep, Gitleaks, OSV-Scanner, DevSkim, NuGet/npm audit, SonarQube) locally, as a pre-commit hook and in a generated CI pipeline, with one report and one gate decision. |
| [dotnet-template](https://github.com/barcsaidominik/dotnet-template) | A security-focused full-stack reference template: .NET 10, Angular, Clean Architecture with CQRS, JWT with rotated refresh tokens, tenant-scoped queries, gRPC behind a YARP gateway, PostgreSQL. Also the test target of my MSc thesis experiment. |
| [homelab-monitor](https://github.com/barcsaidominik/homelab-monitor) | Deterministic monitoring for a Windows home server: an incident state machine with dependency suppression and flapping detection, an outbox for notifications, and a dead man's switch. |
| [homelab-case-study](https://github.com/barcsaidominik/homelab-case-study) | How I run a family home server like production: restore-tested backups, least privilege on Windows, decision records and incident write-ups. |
| [Jellyfin API Key Middleware](https://github.com/barcsaidominik/Jellyfin-API-Key-Middleware-Plugin) | A Jellyfin plugin (ASP.NET Core middleware) that limits each API key to an allowlist of endpoints. |

### Tech I use

- **Backend:** C#, .NET, ASP.NET Core, EF Core, Dapper, T-SQL, gRPC, Quartz.NET, SignalR
- **Messaging:** RabbitMQ, ActiveMQ, MassTransit
- **Frontend:** Angular, TypeScript
- **DevOps and security:** Azure DevOps Pipelines, GitHub Actions, Docker, Semgrep, SonarQube, Gitleaks

### How I work with AI

I use Claude Code every day. Several of these repositories were written mostly with it, and each one says so. I set the requirements and the design decisions, review every change, and only call something done when there is a test or a measurement behind it.

### Contact

[LinkedIn](https://www.linkedin.com/in/dominik-barcsai-989a65123/)
