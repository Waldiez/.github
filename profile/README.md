## <img alt="Waldiez Logo" style="width: 48px; height: auto;" loading="lazy" src="https://waldiez.github.io/icons/logo.svg"> Waldiez

### Orchestrate AI Agents Built for the Physical World

Waldiez builds open-source frameworks for designing, orchestrating, and deploying AI agents — from visual workflow design to resilient actors running on edge devices. Our tools span the full spectrum of agentic AI: drag-and-drop orchestration for general-purpose multi-agent workflows, and an actor-model runtime for agents that live, adapt, and coordinate in the real world, 24/7.

Two complementary frameworks, one mission — make it easy to build AI agents that work together, whether they're reasoning in a notebook or detecting people on a Raspberry Pi.

## 🧩 Our Frameworks

### <img alt="Waldiez Logo" style="width: 20px; height: auto;" loading="lazy" src="https://waldiez.github.io/icons/logo.svg"> Waldiez — Drag, Drop, and Orchestrate

An innovative platform that enables seamless collaboration among [AG2](https://github.com/ag2ai/ag2) AI agents through an intuitive drag-and-drop interface. Design, orchestrate, and execute complex workflows by integrating various AI models and tools effortlessly. [Learn more](https://docs.waldiez.io/)

**Key features**

- **🤖 Runs over AG2**: Supports AG2 communication patterns for building agentic workflows.
- **🔬 JupyterLab Extension**: Create, convert, and execute workflows directly within notebooks. [Read more](https://docs.waldiez.io/usage/index.html)
- **🖥️ Visual Studio Code Extension**: Design and manage Waldiez flows inside VS Code. [Download](https://marketplace.visualstudio.com/items?itemName=Waldiez.waldiez-vscode)
- **🎬 Waldiez Studio**: A FastAPI-based web app for converting and executing Waldiez flows.
- **🚀 Rapid Prototyping**: Export and import models, tools, agents, and workflows to accelerate iteration.
- **🧠 Multi-LLM Support**: OpenAI, Anthropic, Google, NVIDIA NIM, Ollama, and several others.
- **🐳 Docker Support**: Pre-configured images for the core package, JupyterLab extension, and Waldiez Studio. [Check it out](https://hub.docker.com/u/waldiez)

### 🎭 Wactorz — Spawn Agents on the Fly

An actor-model multi-agent framework built from scratch in Python for agents that run 24/7 on the edge. Describe what you want in natural language, and the LLM writes the code, wraps it in a `<spawn>` block, and a new live agent appears on the fly — no restarts, no handwritten infrastructure. Designed as part of the SYNAPSE project funded by dAIEDGE.

**Key features**

- **🎭 Actor Model at the Core**: Agents are isolated actors spawned at runtime from natural-language descriptions. No prescribed paradigm — mix reinforcement learning, rule-based, Bayesian inference, active inference, LLM-driven, or plain deterministic logic in the same system.
- **📡 MQTT-Native Coordination**: Agents communicate via MQTT — the real nervous system of IoT — alongside direct actor messaging.
- **🏠 Edge-First Design**: Runs on modest hardware, fully offline. Spawn agents on a new node (e.g., Raspberry Pi) over SSH with a single command.
- **🔁 Crash-Resilient**: Agents survive crashes and restore state automatically, with rolling conversation summarization so context is never lost.
- **🏗️ PlannerAgent**: Decomposes complex tasks into dependency graphs and fans them out in parallel across actors.
- **🌐 Reactive Pipelines**: "If a person is detected, turn on the lights" — pipelines are built and wired automatically, integrating with tools like Ultralytics YOLO and Home Assistant.
- **🧠 Multi-LLM Support with Cost Tracking**: Works across Anthropic Claude, OpenAI GPT, Google Gemini, Ollama, and NVIDIA NIM, with per-agent LLM cost tracking built in.
- **💬 Multi-Platform Interfaces**: Discord, Telegram, WhatsApp, REST, or CLI — whatever fits your workflow.

## 📂 Repository Overview

### Waldiez ecosystem

- **🏛️ [waldiez](https://github.com/waldiez/waldiez)** — The central repository, including the React application for generating Waldiez flows, tools to convert flows into Python scripts or Jupyter notebooks, and the documentation.
- **🔬 [jupyter](https://github.com/waldiez/jupyter)** — JupyterLab extension for working with workflows inside notebooks.
- **🖥️ [vscode](https://github.com/waldiez/vscode)** — VS Code extension for designing and managing Waldiez flows.
- **🎬 [studio](https://github.com/waldiez/studio)** — FastAPI-based web interface for converting and running flows.
- **🏃 [runner](https://github.com/waldiez/runner)** — Queues and runs Waldiez flows in isolated environments, streaming logs, input, and output via Redis.

### Wactorz

- **🎭 [wactorz](https://github.com/waldiez/wactorz)** — The actor runtime, MQTT coordination layer, PlannerAgent, spawn protocol, state persistence, and integrations with sensors, actuators, and home automation platforms.

Together, these projects cover both ends of the agentic spectrum: collaborative workflow design for general-purpose AI agents, and resilient, edge-deployable actors for the physical world.
