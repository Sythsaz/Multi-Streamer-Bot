# Developer Guide

This document provides technical details for contributors working on the Multi-Streaming Bot.

## Architecture

The bot is designed as a single-file C# script (`Multi-Streaming-Bot.cs`) to ensure compatibility with Streamer.bot's
import system. However, for development, we use a service-based architecture to maintain separation of concerns.

### Core Components

1. **CPHInline**: The entry point required by Streamer.bot. containing the `Execute()` method.
2. **MultiStreamingService**: The main service orchestrator.
3. **ChatForwarder**: Handles logic for forwarding messages between platforms.
4. **ChatFilter**: Implements validation logic (Entropy, Account Age) to block bots.

## Development Constraints

As noted in `CONTRIBUTING.md`, we are restricted to **C# 7.3** and **.NET Framework 4.8**.

- No `var` pattern matching (e.g., `not null`).
- No target-typed `new()`.
- No top-level statements.

## Building and Testing

1. Open the folder in VS Code or Visual Studio.
2. Ensure you have the required references (Newtonsoft.Json) available if testing locally.
3. Use the `_tests` folder to run unit tests (if applicable).

## Release Process

See `CONTRIBUTING.md` for the full release workflow involving `auto-release.ps1`.
