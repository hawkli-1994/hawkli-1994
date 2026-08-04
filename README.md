# Hawkli

**AI Infrastructure Engineer**

Multi-Agent Systems · LLM Inference & Optimization · GPU Systems & Monitoring

Building systems, not demos.

---

## Focus

I build infrastructure for agentic and inference workloads: GPU telemetry, model runtime testing, Kubernetes scheduling surfaces, MCP control planes, and long-horizon agent systems.

My current technical direction is an **AI Agent Infrastructure Stack**:

- **Agent runtime:** multi-agent orchestration, tool control planes, and human-in-the-loop workflows
- **Inference systems:** vLLM service testing, model routing, latency tracking, and baseline comparison
- **GPU infrastructure:** GPU utilization monitoring, sensor parsing, vendor-aware runtime signals, and scheduling inputs
- **Technical writing:** source-level notes on agent frameworks, AI engineering, and cloud-native systems

---

## Flagship Direction

### AI Inference Control Plane

A system that connects agent routing decisions with model runtime telemetry and GPU capacity signals.

Core problems I am working on:

- Route simple and complex tasks across different model tiers
- Use latency, throughput, and GPU utilization as scheduling signals
- Expose control-plane APIs for agents, operators, and inference services
- Benchmark dynamic routing against static model selection baselines

This direction combines my existing work across GPU monitoring, Kubernetes operators, MCP servers, vLLM testing, and agent orchestration.

---

## Project Map

| Layer | Repositories | Signal |
| --- | --- | --- |
| **Core Agent System** | [SwarmMind](https://github.com/rongxinzy/SwarmMind), [deer-flow](https://github.com/hawkli-1994/deer-flow) | Multi-agent systems, long-horizon task orchestration, agent teams |
| **Inference Infrastructure** | [rinference-operator](https://github.com/hawkli-1994/rinference-operator), [vllm_test_tool](https://github.com/hawkli-1994/vllm_test_tool) | Kubernetes inference workloads, vLLM lifecycle testing, runtime automation |
| **GPU Systems** | [go-radeontop](https://github.com/hawkli-1994/go-radeontop), [gpu_tools](https://github.com/hawkli-1994/gpu_tools), [go-sensors-parser](https://github.com/hawkli-1994/go-sensors-parser), [k8s-gpu-hotremove](https://github.com/hawkli-1994/k8s-gpu-hotremove) | GPU telemetry, hardware signals, monitoring libraries, scheduling inputs |
| **Agent Control Plane** | [mcp4meme](https://github.com/hawkli-1994/mcp4meme) | MCP servers, agent-tool interfaces, external system control |
| **Knowledge Output** | [deerflow-book](https://github.com/hawkli-1994/deerflow-book), [kata-container-skill](https://github.com/hawkli-1994/kata-container-skill), [k8s-operator-skills](https://github.com/hawkli-1994/k8s-operator-skills) | Deep technical writing, source-code study, AI/cloud-native education |

---

## Selected Work

### [deerflow-book](https://github.com/hawkli-1994/deerflow-book)

Source-level writing on DeerFlow 2.0 and agent system development. This is my strongest public knowledge asset and the clearest proof of technical communication depth.

### [rinference-operator](https://github.com/hawkli-1994/rinference-operator)

A Kubernetes operator for deploying and managing AI inference workloads across multiple GPU vendors and inference frameworks.

### [vllm_test_tool](https://github.com/hawkli-1994/vllm_test_tool)

Automation for repeated vLLM service lifecycle testing: container startup, monitoring, log collection, shutdown, and stability validation.

### [go-radeontop](https://github.com/hawkli-1994/go-radeontop)

GPU monitoring library for AI inference systems. Useful for tracking GPU utilization, investigating runtime bottlenecks, and feeding scheduling decisions.

## Stack

**Languages:** Go, Python, TypeScript, Rust, C

**Infrastructure:** Kubernetes, Docker, Linux, GPU runtimes, cloud-native systems

**AI Systems:** vLLM, MCP, agent orchestration, inference lifecycle automation

**Systems Topics:** distributed systems, schedulers, observability, performance testing, control planes

---

## Next Build

I am consolidating these pieces into an `ai-infra-playground`:

- GPU telemetry collector
- model routing layer
- inference benchmark runner
- agent control-plane API
- comparison dashboard for latency, throughput, and utilization

The goal is to make the system behavior measurable: lower latency, higher throughput, better GPU utilization, and clearer routing decisions.

---

## Background

M.S. Student in Computer Science at Northern Arizona University.

Research and engineering interests:

- AI infrastructure
- GPU systems
- distributed systems
- cloud-native inference platforms
- agent runtime architecture
