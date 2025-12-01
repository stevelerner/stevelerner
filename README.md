# Steve Lerner's GitHub: Cloud, AI, Observability, OpenAPI, DevOps, Network Engineering, Infra-As-Code

A collection of hands-on demonstrations and training materials focused on modern cloud-native technologies, observability, distributed systems, and AI/ML engineering.

**Quick Overview:**
- [tinyolly](https://github.com/stevelerner/tinyolly): Lightweight observability platform for OpenTelemetry based on Flask, Redis, and Chart.js - no 3rd party tools used
- [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training): Agentic AI with ReAct patterns, tool calling, and model training fundamentals
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

### [tinyolly](https://github.com/stevelerner/tinyolly)
- Lightweight observability platform for OpenTelemetry based on Flask, Redis, and Chart.js
- Receives, stores, and visualizes logs, metrics, and traces without and 3rd party tools
- Interactive trace waterfall with time axis, clickable spans, and distributed tracing visualization
- Real-time metric charts with histogram distributions (min/max/avg/count/buckets)
- Log correlation with bidirectional navigation between logs and traces
- **Log Search**: Filter logs by message content, service name, or trace/span IDs
- **Log JSON View**: Click any log row to view, copy, or download the full JSON log entry
- Uses standard OpenTelemetry protocol - send otel metrics/logs/traces and TinyOlly will visualize and correlate
- Built and tested for Docker Desktop and Minikube on macOS

### [agentic-ai-training](https://github.com/stevelerner/agentic-ai-training)
- **Sherlock Holmes Agentic AI Demo**: Teaches Llama 3.1 to become a consulting detective
- **True Fine-Tuning**: Uses Apple's **MLX** framework for efficient LoRA training on Mac GPUs
- **Synthetic Data**: Generates "Golden Data" mysteries to teach tool use and persona
- **Educational UI**: Side-by-side comparison of Base Model vs. Trained Agent with real-time metrics
- **Key Concepts**: ReAct pattern, Tool Calling, Low-Rank Adaptation (LoRA), Token Efficiency
- Built with Python, Flask, MLX, and Ollama

### [kafka](https://github.com/stevelerner/kafka)
- Comprehensive Apache Kafka streaming platform demonstration
- Multiple producers, consumers, topics, and real-time web UI
- Event-driven architecture, log aggregation, metrics collection
- Consumer groups, partitioning, and message delivery guarantees
- Built with Python, Docker Compose, and Kafka 3.6
- Interactive demos and comprehensive documentation
- Built and tested for Docker Desktop on macOS

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
- Built and tested for Docker Desktop on macOS

### [openapi](https://github.com/stevelerner/openapi)
- Comprehensive OpenAPI demonstration platform
- Multiple microservices, API Gateway, and interactive documentation
- Built with FastAPI and Docker
- RESTful API design, OpenAPI 3.0 specifications, service discovery
- Products, Users, and Orders APIs with unified API catalog
- Health monitoring and modern web UI for browsing and testing endpoints
- Built and tested for Docker Desktop on macOS

### [networkdemo](https://github.com/stevelerner/networkdemo)
- Advanced Docker networking demonstration
- Multi-VLAN routing, DNS, DHCP, and HTTPS
- Interactive visualization webapp for exploring network topologies
- Inter-VLAN routing, NAT, and firewall configurations
- Built with Docker Compose, Python Flask, and comprehensive automation via Makefile
- Built and tested for Docker Desktop on macOS

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