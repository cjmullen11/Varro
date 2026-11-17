# Varro

**Status:** Planned  
**Technologies:** Python · Docker · HTTP APIs · MCP · LLM inference

## Overview

Varro is a self-hosted AI assistant that connects language models, persistent memory, external tools, and multiple user interfaces. I am building it as a unified assistant whose application logic, speech services, clients, and inference infrastructure can evolve independently.

The name **Varro** honors Marcus Terentius Varro, a Roman scholar known for collecting and organizing knowledge across many disciplines.

## Key Design Choices

- **Modular architecture:** Separate the custom orchestrator, mobile app, voice server, and two embedded voice devices into independently maintained codebases.
- **Central ownership:** Keep conversations, memory, tool execution, and agent coordination in the orchestrator rather than in individual clients.
- **Interchangeable inference:** Configure local engines such as vLLM or Ollama, or compatible external APIs, without creating a custom inference engine.
- **Multiple interfaces:** Support browser, mobile, and voice interactions through defined service interfaces.

## Roadmap

- [ ] Define service boundaries and shared API contracts.
- [ ] Establish deployment and inference configurations.
- [ ] Integrate the orchestrator, memory, and initial MCP tools.
- [ ] Connect mobile and voice interfaces through the speech pipeline.
- [ ] Validate end-to-end interaction and concurrent agent workflows.

## Usage

### Requirements

### Setup

### Configuration

### Operation
