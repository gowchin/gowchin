<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,50:1e3a8a,100:2563eb&height=210&section=header&text=Gowthaman%20Chinnathambi&fontSize=44&fontColor=ffffff&fontAlignY=36&desc=Director%20%C2%B7%20Cloud%20Intelligence%20%26%20XOps&descSize=18&descAlignY=58&animation=fadeIn" alt="Gowthaman Chinnathambi" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=3B82F6&center=true&vCenter=true&width=720&lines=Cloud+%E2%80%A2+Platform+%E2%80%A2+Observability+%E2%80%A2+Data+%E2%80%A2+AI;Building+production-grade+agentic+AI+platforms;OpenTelemetry+%26+Seagate+CORTX+contributor;Hands-on+architect.+10%2B+years+shipping+to+production." alt="Typing summary"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-10%2B%20years-1e3a8a?style=flat-square" alt="10+ years"/>
  <img src="https://img.shields.io/badge/Clouds-AWS%20%C2%B7%20Azure%20%C2%B7%20GCP-2563eb?style=flat-square" alt="Multi-cloud"/>
  <img src="https://img.shields.io/badge/Focus-Agentic%20AI%20%C2%B7%20Platform%20%C2%B7%20XOps-3b82f6?style=flat-square" alt="Focus"/>
  <img src="https://img.shields.io/badge/Open%20Source-OpenTelemetry%20%C2%B7%20CORTX-0ea5e9?style=flat-square" alt="Open source"/>
</p>

---

### About

I'm a hands-on engineering leader who connects the whole stack: **application → API → data → cloud → platform → observability → AI**. I started as a Java backend engineer and have since built data pipelines, cloud platforms, release systems, telemetry pipelines and, most recently, agentic AI platforms that run in production.

Today I lead **Cloud Intelligence & XOps**: setting architecture and platform strategy, building reusable frameworks and accelerators, and growing engineers who can work across cloud, data and AI.

- 🧠 **Now:** agent platforms, MCP and A2A tooling, RAG, LLM evaluation and AI observability
- 🏗️ **Always:** Kubernetes, Terraform/OpenTofu, GitOps and self-service infrastructure
- 🔭 **Specialty:** OpenTelemetry pipelines and cost-aware observability, including for AI systems
- 🤝 **Open source:** release engineering for Seagate CORTX; contributor to the OpenTelemetry Collector

---

### What I build

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Agentic &amp; Generative AI</h4>
      Multi-agent workflows with LangGraph, LangChain and AWS Strands. MCP and A2A tool integration, RAG over enterprise knowledge, conversational analytics over Snowflake, Databricks and data lakes, plus memory, session and caching layers, prompt catalogs and evaluation pipelines.
    </td>
    <td width="50%" valign="top">
      <h4>☁️ Cloud &amp; Platform Engineering</h4>
      Production platforms on AWS and Azure: EKS, AKS and ECS, serverless, HA/DR. Self-service Terraform/OpenTofu modules, GitOps with Argo CD and Helm, secrets with Vault and External Secrets, and CI/CD platforms that teams adopt without being told to.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔭 Observability &amp; XOps</h4>
      OpenTelemetry Collector pipelines, custom telemetry connectors, service discovery, and Grafana, Prometheus and Datadog stacks. Telemetry designed with cost in mind. AI observability with Langfuse and LangSmith, plus AI-assisted troubleshooting through MCP.
    </td>
    <td width="50%" valign="top">
      <h4>🗄️ Data &amp; MLOps</h4>
      Airflow, PySpark, Snowflake, Databricks and Delta Lake pipelines. Metadata, lineage and pipeline monitoring across platforms. SageMaker model pipelines, dataset management and continuous model validation.
    </td>
  </tr>
</table>

---

### Career arc

```mermaid
flowchart LR
    A["☕ Java Backend<br/>Spring · REST · SQL"] --> B["🗄️ Data Engineering<br/>Scraping · ETL · Enrichment"]
    B --> C["☁️ Cloud & DevOps<br/>AWS · CI/CD · Containers"]
    C --> D["🚀 Release & Platform<br/>GitOps · K8s · OSS"]
    D --> E["📊 Data, MLOps &<br/>Observability"]
    E --> F["🤖 GenAI & Agents<br/>RAG · MCP · Eval"]
    F --> G["🧭 Director<br/>Cloud Intelligence & XOps"]
```

I've done this across **automotive, media & entertainment, storage, security & communications, retail, nonprofit and enterprise data** environments, nearly always on production systems rather than proofs of concept.

<details>
<summary><b>Selected work</b></summary>
<br/>

- **AI platform observability (automotive):** a cognitive-agent assistant that combines live telemetry via Datadog MCP, Azure AI Search and engineering knowledge to speed up operational troubleshooting.
- **Enterprise RAG and conversational AI:** LangGraph assistants over Confluence, data dictionaries and architecture docs, with tool use, memory and versioned prompt catalogs in Langfuse.
- **Observability framework:** custom OTel connectors, service discovery and automated telemetry collection covering cloud resources, applications and vehicle telemetry, streamed into Grafana with cost controls.
- **Data platform metadata and lineage (media):** lineage across Snowflake, Airflow and Databricks built from query history and Delta Lake metadata, plus refresh and data-loss monitoring.
- **Serverless knowledge graph:** AWS AppSync, Amazon Neptune and ElastiCache/Valkey.
- **Release engineering for Seagate CORTX:** Jenkins shared libraries, GitOps, Kubernetes deployment testing and automated provisioning pipelines for an open-source object store.
- **Nonprofit cloud platform:** AWS infrastructure built from scratch, blue-green deploys and automated testing. Releases went from **weekly to daily**.

</details>

---

### Open source

| Project | Contribution |
|---|---|
| [**Seagate CORTX**](https://github.com/Seagate/cortx) | [70+ merged PRs](https://github.com/pulls?q=is%3Apr+author%3Agowchin+org%3ASeagate+is%3Amerged) to release engineering (`cortx-re`), `cortx-s3server` and `cortx-prvsnr`: CI/CD, mini-provisioner automation, multi-node deployment, stable-branch promotion |
| [**OpenTelemetry Collector Contrib**](https://github.com/open-telemetry/opentelemetry-collector-contrib) | Connector documentation: statefulness guidance for the Datadog ([#51624](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/51624), merged), span metrics, service graph and Grafana Cloud connectors |
| [**sandboxd**](https://github.com/tastyeffectco/sandboxd) | Reliability fixes for sandbox lifecycle and telemetry ([#121](https://github.com/tastyeffectco/sandboxd/pull/121), [#123](https://github.com/tastyeffectco/sandboxd/pull/123)) |

---

### Toolbox

**Languages & app frameworks**
<br/>
<img src="https://skillicons.dev/icons?i=python,java,go,ts,nodejs,react,nextjs,angular,spring,bash&theme=dark" alt="Languages"/>

**Cloud, containers & IaC**
<br/>
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,kubernetes,docker,terraform,ansible,linux&theme=dark" alt="Cloud"/>
<br/>
<img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black" alt="OpenTofu"/>
<img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD"/>
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
<img src="https://img.shields.io/badge/Vault-FFEC6E?style=for-the-badge&logo=vault&logoColor=black" alt="Vault"/>

**CI/CD & release**
<br/>
<img src="https://skillicons.dev/icons?i=githubactions,jenkins,gitlab,git&theme=dark" alt="CI/CD"/>

**Observability**
<br/>
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
<img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Datadog"/>
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" alt="Elasticsearch"/>
<img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge" alt="Langfuse"/>

**Data & MLOps**
<br/>
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks"/>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark"/>
<img src="https://img.shields.io/badge/SageMaker-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="SageMaker"/>
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis&theme=dark" alt="Databases"/>

**AI & agents**
<br/>
<img src="https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="Amazon Bedrock"/>
<img src="https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logoColor=white" alt="Azure OpenAI"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
<img src="https://img.shields.io/badge/AWS%20Strands-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Strands"/>
<img src="https://img.shields.io/badge/MCP-111827?style=for-the-badge" alt="MCP"/>
<img src="https://img.shields.io/badge/A2A-111827?style=for-the-badge" alt="A2A"/>
<img src="https://img.shields.io/badge/RAG-111827?style=for-the-badge" alt="RAG"/>

---

### How I work

> **Build platforms rather than tickets.** Ship reusable modules, golden paths and accelerators that other teams can pick up and use themselves.
>
> **Production or it didn't happen.** Every system gets CI/CD, security guardrails, telemetry and a rollback plan before it's called done.
>
> **Observe everything, pay for what matters.** Telemetry should answer questions, not just pile up storage costs.
>
> **AI is a platform concern.** Agents need the same evaluation, observability, cost control and governance as any other production workload.

---

<p align="center">
  <img src="https://streak-stats.demolab.com?user=gowchin&theme=transparent&hide_border=true&ring=2563EB&fire=3B82F6&currStreakLabel=2563EB" alt="GitHub streak" height="165"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:1e3a8a,100:0b1220&height=110&section=footer" width="100%" alt=""/>
</p>
