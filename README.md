<div align="center">

<img src="https://readme-typing-svg.demolab.com/?lines=Hi%2C+I'm+Harrison+Vance;Forward+Deployed+Engineer+%28FDE%29;Customer+%26+Implementation+Engineering;API+Integrations+%26+AI+Workflows;APAC+%2F+Work+from+Anywhere&font=Fira+Code&center=true&width=700&height=100&color=00FF41&vCenter=true&pause=1000&size=20" alt="Hi, I'm Harrison Vance · Forward Deployed Engineer · Customer and Implementation Engineering · API Integrations and AI Workflows · APAC / Work from Anywhere" />

<p align="center"><a href="https://github.com/h-vance"><img src="https://www.shieldcn.dev/badge/GitHub-%40h--vance-222222.svg?logo=github&variant=default&size=xs" alt="GitHub" /></a>&ensp;<a href="https://linkedin.com/in/harrison-vance"><img src="https://www.shieldcn.dev/badge/LinkedIn-%40harrison--vance-222222.svg?logo=linkedin&variant=default&size=xs" alt="LinkedIn" /></a>&ensp;<a href="https://harrisonvance.cc"><img src="https://www.shieldcn.dev/badge/Website-harrisonvance.cc-222222.svg?logo=googlechrome&variant=default&size=xs" alt="Website" /></a></p>

**Forward Deployed Engineer (FDE) · Customer Engineer · API Integrations · AI Workflows · Production Diagnostics**<br />

</div>

---

I bring 6 years of experience in customer-facing technical work, including onboarding, support, product demos, API integrations, and production diagnostics. I partner with customers to scope requirements, build proofs of concept, and resolve authentication and webhook bottlenecks. I also build AI agents, Model Context Protocol (MCP) tools, and workflow automations that make triage more repeatable.

### ✦ TECH STACK
<div align="center">

<table>
  <tr><td align="right" width="150">Solutions&nbsp;&amp;&nbsp;Support</td><td>Customer onboarding · Product demos · Proofs of concept · Tier 2 / Tier 3 escalation · Zendesk · Intercom</td></tr>
  <tr><td align="right">API&nbsp;&amp;&nbsp;Diagnostics</td><td>REST APIs · Webhooks · Authentication · SSO / SAML · Okta · Postman · cURL · Chrome DevTools · Network traces</td></tr>
  <tr><td align="right">AI&nbsp;&amp;&nbsp;Automation</td><td>Python · Bash · TypeScript · n8n · Zapier · FastAPI · MCP · GitHub Actions · Claude · Cursor</td></tr>
  <tr><td align="right">Infrastructure</td><td>Linux · Docker · Kubernetes · Terraform · AWS · Prometheus · OpenTelemetry · Datadog · Splunk · Grafana</td></tr>
</table>

</div>

---

### ✦ FEATURED WORK

#### 📂 [AWS Bedrock Ops Agent](https://github.com/h-vance/aws-bedrock-ops-agent) · [live demo ↗](https://aws-bedrock-ops-agent.onrender.com/)
*Production diagnostics agent that turns incident evidence into ranked hypotheses, recommended checks, and escalation notes. It serves the same logic over REST and the Model Context Protocol (MCP). Bedrock calls use OpenTelemetry GenAI tracing to Langfuse; the deployed demo runs in mock mode.*

#### 📂 [n8n Workflow as Code](https://github.com/h-vance/n8n-workflow-as-code)
*Four n8n workflows authored as version-controlled TypeScript and compiled to importable JSON, with CI detecting drift between source and artifact. Three call real systems, including live JSON-RPC into the Bedrock agent's MCP tool.*

#### 📂 [EDI Failure Triage](https://github.com/h-vance/edi-failure-triage)
*Integration diagnostics agent for failed EDI transactions using mock fixtures. It classifies failure state in code, ranks evidence-based causes, drafts a customer reply, and proposes a follow-up fix. Available as a CLI, REST API, MCP tool, and Claude Code skill; an n8n workflow turns an Intercom ticket into a triage note.*

#### 📂 [Prove It (prove-it-labs)](https://github.com/h-vance/prove-it-labs) · [take an exercise ↗](https://h-vance.github.io/prove-it-labs/)
*A hands-on Production & Support Engineering course with 26 exercises across 9 tracks. Each starts with a symptom-only customer ticket against a broken system. CI verifies every exercise fails while broken and passes when fixed against real Docker and kind clusters.*

#### 📂 [Postman API Incident Lab](https://github.com/h-vance/postman-tse-incident-lab)
*Four customer-facing API incidents reproduced locally: revoked key, insufficient scope, wrong route, and rate limit. GitHub Actions assertions verify each diagnosis.*

#### 📂 [Payout Rescue](https://github.com/h-vance/payout-rescue)
*A local Stripe Connect demo for failed seller payouts. It classifies the failure, drafts a seller message or escalation note, and creates a retry only after an operator approves it.*

---

### ✦ HOW THE BUILDS CONNECT

Several projects integrate directly: n8n workflows call the Bedrock agent over JSON-RPC and run Postman checks with Newman. The EDI triage workflow converts a sample Intercom ticket into a diagnostic note.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="how-they-fit-dark.svg">
  <img src="how-they-fit-light.svg" width="860" alt="n8n workflow as code calls the Bedrock operations agent over JSON-RPC and runs Postman incident checks with Newman" />
</picture>

---

### ✦ ADDITIONAL SUPPORT TOOLING

| Repo | Stack | What it demonstrates |
|:-----|:------|:---------------------|
| [Cloud Operations Runbook](https://github.com/h-vance/cloud-operations-runbook) | Linux, cloud, identity | Repeatable procedures for compute, networking, identity, and application troubleshooting |
| [Ops Diagnostics](https://github.com/h-vance/ops-diagnostics) | Python, Bash | API health checks, SSL certificate validation, log analysis, and system snapshots |
| [Log Rotation Maintenance](https://github.com/h-vance/log-rotation-maintenance) | Bash | Automated log rotation, compression, and cleanup |
| [Docker TSE Incident Lab](https://github.com/h-vance/docker-tse-incident-lab) | Docker | Reproducible container failure scenarios with outcomes asserted in CI |
| [AWS Automated Remediation Pipeline](https://github.com/h-vance/aws-automated-remediation-pipeline) | Terraform, Python | CloudWatch-to-Lambda remediation workflow; validated in CI, not applied to a live environment |
| [Cloud Service Baseline](https://github.com/h-vance/cloud-service-baseline) | FastAPI, Docker, Terraform | Test service with endpoints for deliberately triggering monitored failures |

---

**Contact:** [Email](mailto:hvance788@gmail.com) · [LinkedIn](https://linkedin.com/in/harrison-vance) · [Website](https://harrisonvance.cc)
