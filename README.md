<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg" />
  <img src="./assets/header-light.svg" alt="Juan David Matos, Senior Software Engineer and Tech Lead. Developer experience and agentic engineering." width="100%" />
</picture>

<p align="center">
  <a href="https://linkedin.com/in/juan-david-matos-553a73204"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:juandmatos0014@gmail.com"><img src="https://img.shields.io/badge/Email-juandmatos0014%40gmail.com-3B5BDB?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://wa.me/18299357237"><img src="https://img.shields.io/badge/WhatsApp-%2B1%20829%20935%207237-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <img src="https://img.shields.io/badge/Open%20to-remote%20senior%20%2F%20staff%20roles-2DA44E?style=flat-square" alt="Open to remote senior and staff roles" />
</p>

<br />

### About

I'm a senior software engineer and tech lead with 6+ years shipping production systems on **TypeScript, Node.js, NestJS, .NET and AWS**. I led a team of up to 12 engineers for about 2.5 years. Today I build for other developers: agent loops that fix failing builds, run tests and open pull requests, shared agent workflows a whole team uses every day, and a path to production with quality gates, observability and DORA metrics.

<table>
  <tr>
    <td align="center" width="25%"><h3>6+</h3><sub>years in production</sub></td>
    <td align="center" width="25%"><h3>12</h3><sub>engineers led</sub></td>
    <td align="center" width="25%"><h3>470+</h3><sub>tests in my current suite</sub></td>
    <td align="center" width="25%"><h3>AWS</h3><sub>Certified Cloud Practitioner</sub></td>
  </tr>
</table>

<br />

### Agents I've built

Two AI agents I built. Each picture follows one request from start to finish.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/agent-support-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/agent-support-light.svg" />
  <img src="./assets/agent-support-light.svg" alt="Support automation agent: an incoming request reaches the agent, which resolves the ticket, opens a pull request and updates the project board." width="100%" />
</picture>

**Support automation agent.** Built for a client with n8n and LLM tool calling. It understands an incoming request, resolves the support ticket, opens a pull request and updates the project board, so routine engineering tasks need less manual handling.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/agent-customer-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/agent-customer-light.svg" />
  <img src="./assets/agent-customer-light.svg" alt="Customer service agent: a customer message reaches the agent, which reads customer data, calls its tools and returns a reply grounded in that data." width="100%" />
</picture>

**Customer service agent.** An LLM agent that answers from real customer data and context instead of guessing. It connects the model to the right data sources and tools, and handles customer data securely.

<br />

### What I build

<table>
  <tr>
    <td valign="top" width="28%"><b>Self-healing CI loop</b><br /><sub>GitHub Actions · Claude Agent SDK</sub></td>
    <td valign="top">When a build fails, an agent reproduces the error, proposes a patch, runs the suite and opens a PR. A human always approves the merge. Isolated branches, cost limits and a decision log as guardrails.</td>
  </tr>
  <tr>
    <td valign="top"><b>PR review agent with evals</b><br /><sub>MCP · LangGraph · FastAPI</sub></td>
    <td valign="top">An MCP server exposes pull requests and builds to agents. The review agent is a LangGraph graph served through FastAPI and measured against an eval set for precision and cost.</td>
  </tr>
  <tr>
    <td valign="top"><b>Developer platform starter</b><br /><sub>GitHub Actions · Kubernetes · GCP</sub></td>
    <td valign="top">A reusable template with quality and security gates, OpenTelemetry tracing, Helm and Cloud Run deploys, and a DORA metrics dashboard built from the GitHub API.</td>
  </tr>
</table>

<br />

### Stack

<table>
  <tr>
    <td width="22%"><b>Agents</b></td>
    <td>Claude Agent SDK · MCP · LangGraph · Google ADK · tool calling · evals · Claude Code · n8n</td>
  </tr>
  <tr>
    <td><b>Developer experience</b></td>
    <td>GitHub Actions · Azure DevOps · CodeQL · SonarQube · gitleaks · OpenTelemetry · SLOs · DORA / SPACE</td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td>TypeScript · Node.js · NestJS · Fastify · Python · FastAPI · .NET / C# · GraphQL · REST</td>
  </tr>
  <tr>
    <td><b>Cloud</b></td>
    <td>AWS (Lambda, API Gateway, SQS, SNS, EventBridge) · GCP (Cloud Run) · Azure · Docker · Kubernetes · Helm · Terraform</td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td>PostgreSQL · SQL Server · MongoDB · Redis · Elasticsearch · DynamoDB</td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>React · Next.js · Angular · Blazor</td>
  </tr>
</table>

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,py,nodejs,nestjs,fastapi,dotnet,react,aws,gcp,azure,docker,kubernetes,terraform,githubactions,postgres&perline=15" alt="TypeScript, Python, Node.js, NestJS, FastAPI, .NET, React, AWS, GCP, Azure, Docker, Kubernetes, Terraform, GitHub Actions, PostgreSQL" />
</p>

<br />

### Experience

<table>
  <tr>
    <td valign="top" width="28%"><b>Arroyo Consulting</b><br /><sub>Mar 2025 – now</sub></td>
    <td valign="top"><b>Senior Software Engineer · Tech Lead</b><br />Tech lead of an internal enterprise platform and owner of its path to production on Azure. Designed the AI-assisted workflow the team uses daily: shared Claude Code agents for code review and architecture compliance, backed by a 470+ test suite. AWS microservices with Lambda and API Gateway.</td>
  </tr>
  <tr>
    <td valign="top"><b>Perceny</b><br /><sub>Dec 2024 – Apr 2025</sub></td>
    <td valign="top"><b>Senior Software Engineer</b><br />REST and GraphQL APIs with NestJS for multi-tenant SaaS products, end to end across Next.js and Node.js.</td>
  </tr>
  <tr>
    <td valign="top"><b>Solvex Dominicana</b><br /><sub>Oct 2021 – Oct 2024</sub></td>
    <td valign="top"><b>Team Lead / Lead Developer</b><br />Promoted to lead a team of up to 12: technical direction, code reviews and engineering standards. Event-driven microservices in NestJS on AWS (Lambda, EventBridge, SQS, SNS, API Gateway) for high-volume transactional workloads.</td>
  </tr>
  <tr>
    <td valign="top"><b>Independent</b><br /><sub>2019 – 2021</sub></td>
    <td valign="top"><b>Freelance Software Developer</b><br />Client projects in Java / Spring Boot, Oracle PL/SQL, React and Node.js, with Jenkins pipelines to OpenShift.</td>
  </tr>
</table>

<br />

<p align="center">
  <sub>Let's talk: <a href="mailto:juandmatos0014@gmail.com">juandmatos0014@gmail.com</a> · <a href="https://linkedin.com/in/juan-david-matos-553a73204">LinkedIn</a> · <a href="https://www.hackerrank.com/juand0014">HackerRank</a> · <a href="https://www.leetcode.com/juand0014">LeetCode</a></sub>
</p>
