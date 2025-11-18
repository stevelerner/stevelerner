# Steve Lerner's GitHub: Cloud, AI, Observability, OpenAPI, DevOps, Network Engineering, Infra-As-Code

A collection of hands-on demonstrations and training materials focused on modern cloud-native technologies, distributed systems, and AI/ML engineering.

**Quick Overview:**
- [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training): Agentic AI with ReAct patterns, tool calling, and model training fundamentals
- [agentic-ai](https://github.com/stevelerner/agentic-ai): Simple, practical agentic AI demonstration with web UI and observability
- [tinyotel](https://github.com/stevelerner/tinyotel): TinyOTel (OpenTelemetry demo) + TinyOlly (custom observability backend with histogram visualization)
- [kafka](https://github.com/stevelerner/kafka): Distributed streaming platform with producers, consumers, and real-time web UI
- [openapi](https://github.com/stevelerner/openapi): Microservices platform with API Gateway and interactive OpenAPI documentation
- [terraform](https://github.com/stevelerner/terraform): Infrastructure as Code demonstration with Docker orchestration
- [networkdemo](https://github.com/stevelerner/networkdemo): Advanced Docker networking with VLANs, routing, DNS, and interactive visualizations
- [otelworkshop-original](https://github.com/stevelerner/otelworkshop-original): Comprehensive OpenTelemetry workshops and observability training (workshop author)

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

### [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training)
- Minimal demonstration of agentic AI and model training using Alice in Wonderland
- Features ReAct pattern (Reason → Act → Observe), tool calling, and model switching
- Comprehensive model comparison with standard NLP evaluation metrics (ROUGE, BLEU, Jaccard)
- Token consumption tracking and character-specific fine-tuning
- Trains custom "mad-hatter" model via Ollama Modelfile
- Built with Python, Flask, Docker, and Ollama
- Perfect for learning both agentic AI patterns and model training fundamentals

### [agentic-ai](https://github.com/stevelerner/agentic-ai)
- Simple, practical demonstration of core agentic AI principles
- Features ReAct pattern (Reason → Act → Observe)
- Showcases tool use, function calling, and LLM integration
- Enhanced observability including token metrics and conversation history
- Built with Python and local Ollama LLM
- Designed for macOS with Docker Desktop
- Perfect for learning agentic AI fundamentals with a clean web UI

### [tinyotel](https://github.com/stevelerner/tinyotel)
- Two tiny implementations for learning observability: TinyOTel + TinyOlly
- **TinyOTel**: Minimal OpenTelemetry demo with instrumented Flask app, collector, and OTLP pipeline
- **TinyOlly**: Custom observability backend built from scratch (~1,840 lines)
  - Receives and stores logs, metrics, and traces via OTLP
  - Web UI with trace waterfall visualization, log correlation, and real-time metric charts
  - Advanced histogram visualization with min/max/avg stats and bucket distribution bar charts
  - Built without Grafana/Jaeger/Prometheus - just Flask, Redis, and Chart.js
- Complete observability pipeline: App → OTel Collector → OTLP Receiver → Redis → Web UI
- Structured JSON logs with trace/span correlation and bidirectional navigation
- Built with Python, Docker Compose, OpenTelemetry, and Chart.js
- Perfect for learning how observability systems work internally with readable, educational code

### [kafka](https://github.com/stevelerner/kafka)
- Comprehensive Apache Kafka streaming platform demonstration
- Multiple producers, consumers, topics, and real-time web UI
- Event-driven architecture, log aggregation, metrics collection
- Consumer groups, partitioning, and message delivery guarantees
- Built with Python, Docker Compose, and Kafka 3.6
- Interactive demos and comprehensive documentation
- Perfect for learning distributed streaming and event-driven systems

### [nextjs-weather-chat for Vercel](https://github.com/stevelerner/nextjs-weather-chat)
- Interactive Next.js 15 demonstration comparing rendering strategies (SSG, SSR, ISR, Edge)
- Real-time weather data and OpenAI-powered chatbot
- API design, performance optimization, and modern deployment patterns
- Deployed on Vercel's edge network

### [terraform](https://github.com/stevelerner/terraform)
- Infrastructure as Code demonstration using Terraform
- Provisions Docker containers locally
- Complete web application stack with Flask, PostgreSQL, and Nginx reverse proxy
- Declarative configuration, dependency management, state management
- Idempotent infrastructure deployment
- Automated deployment scripts and comprehensive Makefile
- Perfect for learning Terraform fundamentals with practical examples

### [openapi](https://github.com/stevelerner/openapi)
- Comprehensive OpenAPI demonstration platform
- Multiple microservices, API Gateway, and interactive documentation
- Built with FastAPI and Docker
- RESTful API design, OpenAPI 3.0 specifications, service discovery
- Products, Users, and Orders APIs with unified API catalog
- Health monitoring and modern web UI for browsing and testing endpoints
- Perfect for learning API development best practices and microservices patterns

### [networkdemo](https://github.com/stevelerner/networkdemo)
- Advanced Docker networking demonstration
- Multi-VLAN routing, DNS, DHCP, and HTTPS
- Interactive visualization webapp for exploring network topologies
- Inter-VLAN routing, NAT, and firewall configurations
- Built with Docker Compose, Python Flask, and comprehensive automation via Makefile

### [devops-technique](https://github.com/stevelerner/devops-technique)
- Collection of battle-tested DevOps techniques, scripts, and best practices
- Practical solutions to real-world infrastructure and operations challenges

### [opentelemetry](https://github.com/stevelerner/opentelemetry)
- Distributed tracing and observability implementations using OpenTelemetry
- Examples, patterns, and learning resources
- Instrumenting applications and infrastructure

### [mobiledemoapps](https://github.com/stevelerner/mobiledemoapps)
- Mobile application demos built with Kotlin
- Exploring mobile development patterns and integrations

## Workshop & Training

I've authored comprehensive observability training workshops used by engineering teams:

### [otelworkshop-original](https://github.com/stevelerner/otelworkshop-original)
- **Author of OpenTelemetry workshops** originally created at SignalFx
- Comprehensive hands-on labs covering instrumentation, exporters, collectors
- Auto-instrumentation, manual tracing, metrics, and collector configuration
- Observability best practices

### [cxworkshops](https://github.com/stevelerner/cxworkshops)
- **Author of Coralogix observability workshops**
- Training materials and hands-on exercises
- End-to-end observability including log aggregation, metric collection, APM, and alert configuration
- Distributed tracing integrations

These workshops help teams transition to modern observability practices with distributed tracing and telemetry standards.

## Connect

- **LinkedIn**: [linkedin.com/in/stevelerner](https://www.linkedin.com/in/stevelerner/)
- **GitHub**: [@stevelerner](https://github.com/stevelerner)