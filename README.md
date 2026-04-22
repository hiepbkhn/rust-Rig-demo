# Rig Agent Demo

A minimal Rust project demonstrating the Rig framework with OpenAI's GPT-4o model. This demo shows how to set up an agent with a custom preamble and interact with it using the Rig library.

## Description

This project creates a simple AI agent configured to behave as a comedian, using OpenAI's GPT-4o model through the Rig framework. It demonstrates the complete flow of provider initialization, agent configuration, and prompt execution.

## Prerequisites

- Rust (edition 2024)
- OpenAI API key (set as `OPENAI_API_KEY` environment variable)

## Installation

1. Clone the repository
2. Install Rust dependencies:

```bash
cargo build
```

## Usage

1. Set your OpenAI API key:

```bash
export OPENAI_API_KEY=your_api_key_here
```

2. Run the demo:

```bash
cargo run
```

The agent will respond with humor and jokes based on the configured preamble.

## Project Structure

- `src/main.rs` - Main application entry point
- `Cargo.toml` - Rust manifest with dependencies (rig-core, tokio, anyhow)

## Dependencies

- `rig-core` (0.35.0) - Framework for building AI agents
- `tokio` (1.x) - Async runtime
- `anyhow` (1.x) - Error handling

## License

MIT
