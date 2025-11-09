## <img alt="Waldiez Logo" style="width: 48px; height: auto;" loading="lazy" src="https://waldiez.github.io/icons/logo.svg"> Waldiez

### Make AG2 Agents Collaborate: Drag, Drop, and Orchestrate with Waldiez 


Waldiez is an innovative platform that enables seamless collaboration among AG2 AI agents through an intuitive drag-and-drop interface. It allows users to design, orchestrate, and execute complex workflows by integrating various AI models and tools effortlessly. [Learn more](https://docs.waldiez.io/)

## 🔥 Key Features

- **🤖 Runs over [AG2](https://github.com/ag2ai/ag2)**: Supporting the AG2 communication patterns for building agentic workflows.
- **🔬 JupyterLab Extension**: Integrates Waldiez functionalities directly into JupyterLab, enabling users to create, convert, and execute workflows within their notebooks. [Read more](https://docs.waldiez.io/usage/index.html)
- **🖥️ Visual Studio Code Extension**: Provides a dedicated extension for Visual Studio Code, allowing users to design and manage Waldiez flows within the editor. [Download](https://marketplace.visualstudio.com/items?itemName=Waldiez.waldiez-vscode)
- **🎬 Waldiez Studio**: A FastAPI-based application that facilitates the conversion and execution of Waldiez flows, offering a user-friendly web interface for managing workflows. [Repository](https://github.com/waldiez/waldiez)
- **🚀 Rapid Prototyping**: Accelerates the prototyping process by exporting and importing existing models, tools/skills, agents, workflows.
- **🧠 Multi-LLM Suport**: Supports several LLMs offered by OpenAI, Anthropic, Google, NVIDIA NIM, local hosted models (Ollama) and several others.
- **🐳 Docker Support**: Offers pre-configured Docker images for easy deployment of Waldiez components, including the core package, JupyterLab extension, and Waldiez Studio. [Check it out](https://hub.docker.com/u/waldiez)

## 📂 Repository Overview

Waldiez hosts several projects that collectively enhance the platform's capabilities:

- **🏛️ [waldiez](https://github.com/waldiez/waldiez)** - The central repository that includes a React application designed to generate Waldiez flows, offering a graphical interface for workflow creation, tools and scripts to run and convert Waldiez flows into Python scripts or Jupyter notebooks, facilitating integration with Python-based projects and the documentation for the usage of waldiez. Feel free to upload examples of usage in the blogs section.
- **🔬 [jupyter](https://github.com/waldiez/jupyter)** - A JupyterLab extension that integrates Waldiez into the Jupyter environment, enabling users to work with workflows directly within notebooks.
- **🖥️ [vscode](https://github.com/waldiez/vscode)** - An extension for Visual Studio Code that allows users to design and manage Waldiez flows within the editor.
- **🎬 [studio](https://github.com/waldiez/studio)** - A FastAPI-based application providing a web interface for converting and running Waldiez flows, enhancing user experience.
- **🏃 [runner](https://github.com/waldiez/runner)**: Responsible for queuing and running waldiez flows in isolated environments and stream logs/input/output via Redis.

These repositories collectively contribute to the robustness and versatility of the Waldiez platform, enabling users to create, manage, and execute AI-driven workflows across different environments and applications.
