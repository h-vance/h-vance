<div align="center">

<img src="https://readme-typing-svg.demolab.com/?lines=Hi%2C+I'm+Harrison+Vance;Technical+Support+Engineer;AI+Agent+Tooling+%26+Incident+Automation&font=Fira+Code&center=true&width=560&height=60&color=00FF41&vCenter=true&pause=1000&size=20" />
  

<p align="center"><a href="https://github.com/h-vance"><img src="https://www.shieldcn.dev/badge/GitHub-%40h--vance-222222.svg?logo=github&variant=default&size=xs" /></a>&ensp;<a href="https://linkedin.com/in/harrison-vance"><img src="https://www.shieldcn.dev/badge/LinkedIn-%40harrison--vance-222222.svg?logo=linkedin&variant=default&size=xs" /></a>&ensp;<a href="https://harrisonvance.cc"><img src="https://www.shieldcn.dev/badge/Website-harrisonvance.cc-222222.svg?logo=googlechrome&variant=default&size=xs" /></a>&ensp;<img src="https://www.shieldcn.dev/badge/Location-Remote-222222.svg?logo=googlemaps&variant=default&size=xs" /></p>

---

### ✦ TECH STACK
<div align="center">

<table>
  <tr><td align="right" width="130">Support&nbsp;Ops</td><td><img src="https://www.shieldcn.dev/badge/Zendesk-222222.svg?variant=default&logo=Zendesk&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Intercom-222222.svg?variant=default&logo=Intercom&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Postman-222222.svg?variant=default&logo=Postman&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Datadog-222222.svg?variant=default&logo=Datadog&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Grafana-222222.svg?variant=default&logo=Grafana&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/OpenTelemetry-222222.svg?variant=default&logo=opentelemetry&logoColor=FFFFFF&size=xs" /></td></tr>
  <tr><td align="right" width="130">AI&nbsp;&amp;&nbsp;Agents</td><td><img src="https://www.shieldcn.dev/badge/Claude-222222.svg?variant=default&logo=Claude&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Cursor-222222.svg?variant=default&logo=Cursor&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Codex-222222.svg?variant=default&logo=openaigym&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Ollama-222222.svg?variant=default&logo=Ollama&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/MCP-222222.svg?variant=default&logo=modelcontextprotocol&logoColor=FFFFFF&size=xs" /></td></tr>
  <tr><td align="right" width="130">Infra</td><td><img src="https://www.shieldcn.dev/badge/Linux-222222.svg?variant=default&logo=Linux&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Docker-222222.svg?variant=default&logo=Docker&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Kubernetes-222222.svg?variant=default&logo=Kubernetes&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Terraform-222222.svg?variant=default&logo=Terraform&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Ubuntu-222222.svg?variant=default&logo=Ubuntu&logoColor=FFFFFF&size=xs" /></td></tr>
  <tr><td align="right" width="130">Tools</td><td><img src="https://www.shieldcn.dev/badge/Python-222222.svg?variant=default&logo=Python&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/TypeScript-222222.svg?variant=default&logo=typescript&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/FastAPI-222222.svg?variant=default&logo=fastapi&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/GNU%20Bash-222222.svg?variant=default&logo=gnubash&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Git-222222.svg?variant=default&logo=Git&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/GitHub%20Actions-222222.svg?variant=default&logo=githubactions&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/n8n-222222.svg?variant=default&logo=n8n&logoColor=FFFFFF&size=xs" /> <img src="https://www.shieldcn.dev/badge/Notion-222222.svg?variant=default&logo=Notion&logoColor=FFFFFF&size=xs" /></td></tr>
</table>

</div>

---

### ✦ FEATURED WORK

#### 📂 [aws-bedrock-ops-agent](https://github.com/h-vance/aws-bedrock-ops-agent) &nbsp;·&nbsp; [live demo ↗](https://aws-bedrock-ops-agent.onrender.com/)
*An L2 triage copilot that ingests incident evidence bundles and returns ranked hypotheses, recommended checks, and escalation-ready notes. The same triage logic is served over both REST and the Model Context Protocol from a single deploy, and every Bedrock call is traced with OpenTelemetry GenAI semantic conventions.*

#### 📂 [n8n-workflow-as-code](https://github.com/h-vance/n8n-workflow-as-code)
*Four n8n workflows authored as version-controlled TypeScript and compiled to importable JSON. Three of the four call real systems instead of mocking them: live JSON-RPC into the Bedrock agent's MCP tool, `newman` against a real Postman collection, and container restarts over the Docker Engine API and a live `kind` cluster.*

#### 📂 [postman-tse-incident-lab](https://github.com/h-vance/postman-tse-incident-lab)
*Four customer-facing API incidents (revoked key, insufficient scope, wrong route, rate limiting), each reproduced against a local API, each diagnosis verified by assertions that run in CI, each with the customer response or engineering handoff a TSE should provide.*

#### 📂 [self-healing-microservices-cluster](https://github.com/h-vance/self-healing-microservices-cluster)
*A Kubernetes workload that recovers from injected faults on its own, with recovery asserted on every push rather than described. CI creates a real `kind` cluster, installs kube-prometheus-stack, and injects three faults: a forced liveness failure, a container OOM against its memory limit, and a pod deletion. The build fails if the workload does not come back, and a Prometheus alert routes through Alertmanager to a remediation controller that records deployment state before and after.*

---

### ✦ HOW THEY FIT TOGETHER

*These aren't four unrelated demos. They call each other.*

```mermaid
flowchart LR
    N["n8n-workflow-as-code"]
    B["aws-bedrock-ops-agent"]
    P["postman-tse-incident-lab"]
    I["incident-postmortems"]

    N -->|"JSON-RPC over /mcp"| B
    N -->|"npx newman run"| P
    B -->|"hypotheses + escalation notes"| I
    N -->|"drafts postmortem"| I
```

---

### ✦ SUPPORT TOOLING & DIAGNOSTICS

| Repo | Stack | Problem | Resolution |
|:-----|:------|:--------|:-----------|
| [Incident-Postmortems](https://github.com/h-vance/incident-postmortems) | Docs | Incidents repeating with no record | Blameless RCAs in standard formats |
| [Ops-Diagnostics](https://github.com/h-vance/ops-diagnostics) | Python, Bash | Manual verification slowing MTTR | Auto-ping endpoints, health parsing, log monitoring |
| [Log-Rotation-Maintenance](https://github.com/h-vance/log-rotation-maintenance) | Bash | Logs filling server storage | Auto-rotation, compression, cleanup |
| [Cloud-Operations-Runbook](https://github.com/h-vance/cloud-operations-runbook) | Docs | Tribal knowledge gaps | 15+ standardized SOPs |

---

**Contact:** [hvance788@gmail.com](mailto:hvance788@gmail.com) | [LinkedIn](https://linkedin.com/in/harrison-vance) | [harrisonvance.cc](https://harrisonvance.cc)
