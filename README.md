# local-llm-browser

Browser JavaScript SDK for local LLM inference with WebGPU.

`local-llm-browser` is an open source SDK for running large language models directly in the browser with on-device inference, WebGPU acceleration, streaming generation, and local-first execution.

## What It Is

- Browser SDK for local LLM inference
- WebGPU-based runtime for in-browser AI
- JavaScript and TypeScript API for chat, generation, and model loading
- Local-first alternative to cloud-only LLM APIs

## Planned Capabilities

- Load quantized LLMs in the browser
- Run chat and text generation fully on-device
- Stream tokens with browser-friendly APIs
- Use Web Workers for non-blocking inference
- Keep model execution private and local

## Use Cases

- Browser AI applications
- Private on-device chat interfaces
- Local AI copilots
- Offline-capable LLM apps
- WebGPU experiments for client-side inference

## Status

Active development. This repository is the public SDK layer for the browser package family.

The lower-level execution engine lives in [`local-llm-browser-engine`](https://github.com/hilum-labs/local-llm-browser-engine).

## Package Direction

```bash
npm install local-llm-browser
```

## Related Repositories

- [`local-llm-browser-engine`](https://github.com/hilum-labs/local-llm-browser-engine): WebGPU browser inference engine
- [`local-llm`](https://github.com/hilum-labs/local-llm): Node.js local LLM runtime
- [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine): native C/C++ inference engine

## Keywords

Local LLM, browser LLM, WebGPU LLM, on-device AI, client-side inference, browser AI SDK, JavaScript LLM runtime.
