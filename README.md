## Hi, I'm Mihail

I'm a backend developer working mostly with C# and .NET. I care about code that stays easy to change as a project grows, which usually means clear service boundaries, good test coverage and a CI pipeline that catches problems before they reach `master`.

Lately most of my public work has gone into InstaConnect.

### InstaConnect

[**InstaConnect**](https://github.com/VTUMihail1/InstaConnect) is a social media backend split into four services (Identity, Posts, Chats and Follows) that sit behind an nginx gateway and talk to each other through RabbitMQ events.

- Each service follows Clean Architecture, with MediatR commands and queries, FluentValidation and Mapster
- MongoDB with transactions, Redis for caching and SignalR for real-time chat and notifications
- Unit, integration and functional tests using xUnit, NSubstitute and Testcontainers
- A GitHub Actions pipeline that only builds and tests the services a change actually touches
- The whole stack, including the gateway and observability, runs locally with Docker Compose

### What I work with

**Languages and frameworks:** C#, .NET, ASP.NET Core, HTML, CSS<br>
**Data:** MongoDB, SQL Server, MySQL, Redis<br>
**Messaging:** RabbitMQ, MassTransit, SignalR<br>
**Testing:** xUnit, NSubstitute, FluentAssertions, Testcontainers<br>
**Tooling:** Docker, nginx, GitHub Actions, OpenTelemetry, Git, Jira

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mihail-nikolov-a24b29255/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/VTUMihail/)
