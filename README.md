# local-llm-web

Web JavaScript SDK for local LLM inference with WebGPU.

`local-llm-web` is an open source SDK for running large language models in web applications with on-device inference, WebGPU acceleration, streaming generation, and local-first execution.

## What It Is

- Web SDK for local LLM inference
- JavaScript and TypeScript API for chat, generation, and model loading
- High-level package built on `local-llm-web-core`
- Local-first alternative to cloud-only LLM APIs

## Planned Capabilities

- Load quantized LLMs in web applications
- Run chat and text generation fully on-device
- Stream tokens with web-friendly APIs
- Use Web Workers for non-blocking inference
- Keep model execution private and local

## Use Cases

- Web AI applications
- Private on-device chat interfaces
- Local AI copilots
- Offline-capable LLM apps
- WebGPU-powered client-side inference

## Status

Active development. This repository is the public SDK layer for the web package family.

The lower-level runtime core lives in [`local-llm-web-core`](https://github.com/hilum-labs/local-llm-web-core).

## Package Direction

```bash
npm install local-llm-web
```

## Related Repositories

- [`local-llm-web-core`](https://github.com/hilum-labs/local-llm-web-core): WebGPU runtime core
- [`local-llm`](https://github.com/hilum-labs/local-llm): Node.js local LLM runtime
- [`hilum-local-llm-engine`](https://github.com/hilum-labs/hilum-local-llm-engine): native C/C++ inference engine
