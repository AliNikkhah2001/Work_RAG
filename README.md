# 🧠 RAG Agent Platform - Orchestrator

This repository orchestrates all RAG platform components using Git submodules.

## Components

### RAG Agents (Versions)
- **v1**: Work_Credit-RAG_Phase1 - Original stable version
- **v2**: Coming soon
- **v3**: Coming soon

### Infrastructure
- **Server Setup**: Work_RAG-Server-Setup - Server configuration and deployment

### Future Components
- Guardrails (coming soon)
- Vector DB (coming soon)
- Deployment Configs (coming soon)

## Quick Start

`ash
# Clone with all submodules
git clone --recurse-submodules https://github.com/your-org/rag-platform.git
cd rag-platform

# Initialize all submodules
git submodule update --init --recursive

# Deploy v1
make deploy-v1

