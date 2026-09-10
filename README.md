<div align="center">


# `JacksonWu`

### AI Application Engineer · Backend Systems Builder

`models are components. systems are the product.`

[![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)](https://www.python.org/)
[![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=ED8B00)](https://www.java.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-0d1117?style=flat-square&logo=langchain&logoColor=1C3C3C)](https://langchain-ai.github.io/langgraph/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=009688)](https://fastapi.tiangolo.com/)
[![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)](https://www.docker.com/)

</div>

```text
$ whoami
JacksonWu / 吴子杰

$ uptime
building applied AI systems with Python + Java

$ ps aux | grep focus
Agent orchestration | RAG | Tool Calling | IoT | backend reliability
```

## About Me

I am a backend developer focused on applied AI engineering.

I work on the layer where an LLM stops being a demo and becomes a product:
stateful Agent workflows, retrieval pipelines, business tools, real-time
transport, service boundaries, and deployment.

My main playground is the intersection of AI applications and connected
devices. I build with Python and Java, usually pairing FastAPI AI services
with Spring Boot business systems.

## What I Build

```yaml
agent:
  orchestration: LangGraph
  capabilities: [routing, memory, retrieval, tool-calling]

knowledge:
  pattern: RAG
  vector_store: Chroma
  inputs: [product_docs, device_faq, business_policy]

runtime:
  api: [FastAPI, Spring Boot]
  transport: [WebSocket, MQTT, RabbitMQ]
  state: [Redis, MySQL]
  delivery: [Docker, Kubernetes, AWS]
```

## Selected Systems

### `voice-agent/` · AI Voice Interaction Desktop Pet

LangGraph workflow for voice preprocessing, intent routing, RAG retrieval,
tool calls, response generation, and multi-turn state persistence.

`LangGraph` `RAG` `Tool Calling` `WebSocket` `Opus` `Redis` `RabbitMQ`

### `commerce-copilot/` · Cross-border E-commerce Customer Service

Python AI service plus Java business backend for product, order, logistics,
and after-sales conversations, with multilingual responses and human handoff.

`FastAPI` `Spring Boot` `LangChain` `Chroma` `Redis` `RabbitMQ`

### `distributed-rag/` · Knowledge Retrieval Platform

Full-stack document processing and Q&A system with semantic chunking,
vector retrieval, multi-turn conversation, citation-aware answers, and
Docker delivery.

`Python` `LangGraph` `Chroma` `FastAPI` `Spring Boot` `Docker`

## Open Source Log

### CrewAI · [PR #7341](https://github.com/crewAIInc/crewAI/pull/7341)

Working on memoization cache lifecycle and instance retention:

- scoped memoized values to the owning instance lifecycle
- prevented callback references from retaining discarded Crew instances
- added garbage-collection regression coverage

`status: open / under review`

### Merged · [distributed-traffic-control #13](https://github.com/yashdotdev13/distributed-traffic-control/pull/13)

Added Docker healthchecks for Redis and gateway services, including startup
ordering around Redis readiness.

### In Flight

[AgentStack #365](https://github.com/agentstack-ai/AgentStack/pull/365) ·
[respx #329](https://github.com/lundberg/respx/pull/329) ·
[LiteLLM #40233](https://github.com/BerriAI/litellm/pull/40233) ·
[LiteLLM #40230](https://github.com/BerriAI/litellm/pull/40230)

## Engineering Notes

```python
def ship(capability):
    system = compose(capability, knowledge, tools, state)
    verify(system, tests=True, metrics=True)
    deploy(system, reproducible=True)
    return iterate(system)
```

I care about the part after the demo: explicit boundaries, idempotent writes,
failure paths, observable behavior, and code that another engineer can run.

## Toolbox

`Python` `Java` `FastAPI` `Spring Boot` `LangChain` `LangGraph`
`RAG` `Chroma` `Redis` `RabbitMQ` `MySQL` `WebSocket` `MQTT`
`Docker` `Kubernetes` `AWS`

Open to conversations about AI applications, Agent engineering,
backend systems, and open-source collaboration.
