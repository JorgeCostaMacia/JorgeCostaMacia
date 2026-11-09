I build software end to end, from the domain model to the servers it runs on.

**Design** · DDD, hexagonal / clean architecture, CQRS, event-driven systems, SOLID, TDD with xUnit and Testcontainers  
**Backend** · .NET / C#, EF Core, PHP / Symfony, messaging (Kafka, RabbitMQ)  
**Identity** · Keycloak, OAuth 2.0 / OpenID Connect, JWT  
**Frontend** · JavaScript, TypeScript, HTML / CSS, Angular, Angular Material, Sass / SCSS  
**Data** · PostgreSQL, MySQL, data pipelines and warehousing  
**Ops** · Linux, Docker, Kubernetes, Nginx / Apache, Git / GitFlow, CI/CD with GitHub Actions  
**Observability** · Grafana, Prometheus, Loki  
**AI** · agent-assisted development with Claude Code, authoring agent skills

### Open source

.NET libraries on [NuGet](https://www.nuget.org/profiles/JorgeCostaMacia):

- [ddd-dotnet](https://github.com/JorgeCostaMacia/ddd-dotnet) — DDD building blocks: value objects, aggregates, entities, domain events
- [bus-dotnet](https://github.com/JorgeCostaMacia/bus-dotnet) — transport-agnostic command/event bus, with
  [Kafka](https://github.com/JorgeCostaMacia/bus-kafka-dotnet) and [RabbitMQ](https://github.com/JorgeCostaMacia/bus-rabbitmq-dotnet) transports
- [http-dotnet](https://github.com/JorgeCostaMacia/http-dotnet) — ASP.NET Core defaults: ProblemDetails, logging, versioning, OpenAPI
- [quartz-dotnet](https://github.com/JorgeCostaMacia/quartz-dotnet) · [serilog-dotnet](https://github.com/JorgeCostaMacia/serilog-dotnet) — Quartz.NET and Serilog baselines

Tooling:

- [gitflow-vscode](https://github.com/JorgeCostaMacia/gitflow-vscode) — GitFlow for VS Code on pure git
- [skills](https://github.com/JorgeCostaMacia/skills) — agent skills for AI coding agents: DDD, clean architecture, testing, .NET
