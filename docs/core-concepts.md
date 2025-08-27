---
title: Core Concepts
---

# Core Concepts

Understanding a few core concepts will help you unlock the full power of `genai-agentos`.

### Agent

An `Agent` is the fundamental building block. It's an autonomous entity that can perform tasks, communicate, and make decisions. In code, you create an agent by defining a class that inherits from our base `Agent` class. You give it a name, a description (its "prompt" or "constitution"), and logic for how it handles messages.

### Message

Agents communicate using `Message` objects. A message is a simple data structure that contains the content (text), the sender, and the recipient. Our protocol ensures these messages can be reliably sent between agents, whether they are running on the same machine or across the internet.

### Backend

The `Backend` is the engine that powers the agents. It manages the agent lifecycle, message queuing, and state. When you use the `run()` function, you are starting a simple, local backend. For more complex applications, you can run a persistent backend server that manages multiple agents.

### Protocol (A2A)

The Agent-to-Agent (A2A) protocol is the set of rules that governs how agents communicate. It defines how messages are formatted, addressed, and routed. You don't usually need to interact with the protocol directly, but it's what enables the powerful multi-agent systems you can build with `genai-agentos`.