# Steve Lerner's GitHub: Cloud, AI, OpenTelmetry, Observability, OpenAPI, DevOps, Network Engineering, Infra-As-Code

A collection of hands-on demonstrations and training materials focused on modern cloud-native technologies, observability, distributed systems, and AI/ML engineering.

**Quick Overview:**
- [inferencerouter](https://github.com/stevelerner/inferencerouter): OpenAI-compatible gateway that auto-routes requests between on-prem models and Claude based on data sensitivity and task complexity
- [tinyolly](https://tinyolly.github.io/tinyolly/): The World's First Desktop Observability Platform! 100% OpenTelemetry Native
- [edot](https://github.com/stevelerner/edot): Elastic Distro of OpenTelemetry demo with TinyOlly visualization
- [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training): Agentic AI with ReAct patterns, tool calling, and model training fundamentals
- [agentic-ai](https://github.com/stevelerner/agentic-ai): Simple agentic AI demo with ReAct loop and observability
- [kafka](https://github.com/stevelerner/kafka): Distributed streaming platform with producers, consumers, and real-time web UI
- [openapi](https://github.com/stevelerner/openapi): Microservices platform with API Gateway and interactive OpenAPI documentation
- [terraform](https://github.com/stevelerner/terraform): Infrastructure as Code demonstration with Docker orchestration
- [networkdemo](https://github.com/stevelerner/networkdemo): Advanced Docker networking with VLANs, routing, DNS, and interactive visualizations
- [otelworkshop-original](https://github.com/stevelerner/otelworkshop-original): OpenTelemetry workshops and observability training *(fork, authored by me)*

<div align="center">
  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stevelerner/)
[![GitHub followers](https://img.shields.io/github/followers/stevelerner?style=for-the-badge&logo=github)](https://github.com/stevelerner)

</div>

## Tech Stack

<div align="center">

![AI](https://img.shields.io/badge/AI-FF6F00?style=for-the-badge&logo=brain&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

</div>

## Featured Projects

### [inferencerouter](https://github.com/stevelerner/inferencerouter)
- A ~200-line OpenAI-compatible gateway that auto-routes each request between an on-prem model and Claude on two deterministic axes: data sensitivity and task complexity
- Sensitive data and simple tasks stay local; non-sensitive, complex queries route to Claude
- Live operations console, editor integrations (Zed, VS Code), and safe fallback to local inference if the cloud API is unavailable
- Built with Python, Ollama (on-prem), and the Anthropic Claude API

### [tinyolly](https://tinyolly.github.io/tinyolly/)
- **The World's First Desktop Observability Platform** - lightweight OpenTelemetry-native observability platform for local dev of OpenTelemetry logs/metrics/traces in your apps
- **AI Agents Tab**: GenAI observability with LLM call tracking (prompts, responses, token usage, latency) via OpenTelemetry GenAI semantic conventions
- **OpAMP Configuration**: Remote OpenTelemetry Collector configuration management via OpAMP protocol with real-time validation
- **Cardinality Explorer & Protection**: Deep-dive into metric attributes with label analysis, raw series view, PromQL export, and visual warnings
- Service catalog with RED metrics, interactive service dependency map, distributed trace waterfall, and real-time metrics - all with full OTLP support

### [edot](https://github.com/stevelerner/edot)
- Elastic Distribution of OpenTelemetry (EDOT) Collector demo, paired with TinyOlly for local visualization
- Demo apps generate real traffic/telemetry through the full pipeline

### [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training)
- **Sherlock Holmes Agentic AI Demo**: Teaches Llama 3.1 to become a consulting detective
- **True Fine-Tuning**: Apple's **MLX** framework for LoRA training on Mac GPUs
- **Key Concepts**: ReAct pattern, Tool Calling, LoRA, Token Efficiency
- Built with Python, Flask, MLX, and Ollama

### [agentic-ai](https://github.com/stevelerner/agentic-ai)
- Simple agentic AI demo: ReAct (Reason → Act → Observe) loop with full observability
- Per-step token/timing metrics, tool intelligence, and a clean web UI
- Designed for macOS with Docker Desktop

### [kafka](https://github.com/stevelerner/kafka)
- Apache Kafka streaming platform: multiple producers, consumers, topics, real-time web UI
- Consumer groups, partitioning, message delivery guarantees
- Built with Python, Docker Compose, and Kafka 3.6

### [nextjs-weather-chat for Vercel](https://github.com/stevelerner/nextjs-weather-chat)
- Next.js 15 demo comparing rendering strategies (SSG, SSR, ISR, Edge)
- Real-time weather data and OpenAI-powered chatbot, deployed on Vercel's edge network

### [terraform](https://github.com/stevelerner/terraform)
- Infrastructure as Code demo: Terraform-provisioned Flask + PostgreSQL + Nginx stack on Docker
- Idempotent deployment via automated scripts and Makefile

### [openapi](https://github.com/stevelerner/openapi)
- Microservices platform with API Gateway and interactive OpenAPI 3.0 documentation
- Products, Users, and Orders APIs with unified catalog and health monitoring
- Built with FastAPI and Docker

### [networkdemo](https://github.com/stevelerner/networkdemo)
- Advanced Docker networking: multi-VLAN routing, DNS, DHCP, HTTPS, NAT/firewall
- Interactive webapp for exploring network topologies
- Built with Docker Compose, Python Flask, and Makefile automation

### [devops-technique](https://github.com/stevelerner/devops-technique)
- Battle-tested DevOps techniques, scripts, and best practices for real-world infra/ops

### [retropie](https://github.com/stevelerner/retropie)
- RetroPie setup for an X-Arcade Tankstick Max on Raspberry Pi (bookworm)
- Documents hardware fixes for input drivers, XRDP, and audio routing

### [tinyolly-redis-archive](https://github.com/stevelerner/tinyolly-redis-archive)
- Archived Redis-backed version of TinyOlly, superseded by the current build

## Workshop & Training

I've authored comprehensive observability training workshops used by engineering teams:

### [otelworkshop-original](https://github.com/stevelerner/otelworkshop-original) *(fork, authored by me)*
- OpenTelemetry workshops originally created at SignalFx
- Hands-on labs: instrumentation, exporters, collectors, tracing, metrics

### [cxworkshops](https://github.com/stevelerner/cxworkshops) *(fork, authored by me)*
- Coralogix observability workshops: log aggregation, metrics, APM, alerting, tracing

These workshops help teams transition to modern observability practices.

## Forks I Maintain

- [Xarcade2Jstick](https://github.com/stevelerner/Xarcade2Jstick) *(fork, authored by me)*: Patched user-space driver mapping the X-Arcade Tankstick to two gamepads
- [bitdrift-public](https://github.com/stevelerner/bitdrift-public) *(fork, authored by me)*: bitdrift Solution Architects public repository

## Connect

- **LinkedIn**: [linkedin.com/in/stevelerner](https://www.linkedin.com/in/stevelerner/)
- **GitHub**: [@stevelerner](https://github.com/stevelerner)
