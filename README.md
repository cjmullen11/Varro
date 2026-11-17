# Varro

**Status:** Planned  
**Technologies:** Python · Docker · LLMs · MCP · HTTP APIs

## Overview

Varro is a self-hosted AI assistant that connects language models, long-term memory, external tools, and multiple user interfaces. I am building it to provide one extensible assistant while keeping individual services and hardware replaceable.

The name **Varro** references Marcus Terentius Varro, a Roman scholar known for work across many fields of knowledge.

## Key Design Choices

- **Modular system:** Maintain separate codebases for the orchestrator, mobile companion, and ESP32 voice device.
- **Central coordination:** Let the custom orchestrator own conversations, tool execution, memory retrieval, and agent scheduling.
- **Replaceable inference:** Configure local backends such as vLLM or Ollama, or compatible external APIs, without writing a new inference engine.
- **Multiple interfaces:** Support web and voice clients through defined service APIs.

## Roadmap

- [ ] Define service boundaries and shared API contracts.
- [ ] Establish deployment and inference configuration.
- [ ] Connect the orchestrator, memory, and initial MCP tools.
- [ ] Integrate a web client and the voice pipeline.
- [ ] Validate end-to-end operation and concurrent agent workflows.

## Usage

### Requirements

### Setup

### Configuration

### Operation
