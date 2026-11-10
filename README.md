# Awesome Open-Source AI Models [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for open-source AI models, open-weight foundational LLMs, Mixture-of-Experts (MoE) architectures, multimodal vision-language models, reasoning engines, and self-hosted inference runtimes.

Open-source and open-weight artificial intelligence models provide researchers, developers, and enterprise architects with full transparency, self-hosting privacy, and fine-tuning control. By releasing model weights under permissive licenses, the global AI community enables local deployment across consumer GPUs, edge devices, and cloud clusters. This list is intended for machine learning engineers, AI researchers, LLM application developers, and cloud infrastructure leads.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Large Language Models (LLMs) & MoE Architecture](#large-language-models-llms--moe-architecture)
- [Reasoning & Agentic Coding Models](#reasoning--agentic-coding-models)
- [Multimodal Vision & Audio Models](#multimodal-vision--audio-models)
- [Inference Engines & Local Runtimes](#inference-engines--local-runtimes)
  - [Local GPU & CPU Runtimes](#local-gpu--cpu-runtimes)
  - [High-Throughput Server Engines](#high-throughput-server-engines)
- [Fine-Tuning & Evaluation Toolkits](#fine-tuning--evaluation-toolkits)
- [Related Awesome Lists](#related-awesome-lists)

## Large Language Models (LLMs) & MoE Architecture

Open-weight foundational language models, sparse Mixture-of-Experts (MoE), and dense architectures.

- [Llama 3.3 70B](https://github.com/meta-llama/llama3) — Meta's flagship dense foundation model offering state-of-the-art multilingual comprehension and reasoning capabilities under the Llama Community License.
- [DeepSeek-V4-Flash](https://github.com/deepseek-ai) — High-efficiency sparse Mixture-of-Experts (MoE) model featuring Multi-head Latent Attention (MLA) and native 1M context support under MIT license.
- [Qwen3.5 Series](https://github.com/QwenLM/Qwen) — Alibaba's open-weight model family spanning compact dense models and massive MoE architectures optimized for multilingual tasks.
- [Mistral Large 4](https://github.com/mistralai) — Open-weight multimodal MoE model engineered for high-throughput enterprise reasoning and long-context analysis.
- [gRPC / gpt-oss-120b](https://github.com/openai/gpt-oss) — OpenAI's open-weight reasoning model designed to execute efficiently on single 80GB GPU instances under the Apache-2.0 license.

## Reasoning & Agentic Coding Models

Models post-trained for step-by-step mathematical reasoning, autonomous coding agents, and terminal interaction.

- [GLM-5.3](https://github.com/THUDM) — Zhipu AI's permissive MIT open-weight model tailored for complex repository-scale coding and long-horizon agent workflows.
- [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) — Open-weight reasoning model utilizing reinforcement learning to generate chain-of-thought solutions for complex logic tasks.
- [Devstral Small](https://github.com/mistralai) — Lightweight Apache-2.0 coding model optimized for autonomous software development and SWE-bench tasks.
- [QwQ-32B](https://github.com/QwenLM/Qwen) — Alibaba's dedicated open reasoning model designed to match proprietary reasoning benchmarks in a compact 32B footprint.

## Multimodal Vision & Audio Models

Models processing combined text, image, video, and audio inputs for vision-language and perceptual tasks.

- [InternVL 3](https://github.com/OpenGVLab/InternVL) — Open-source multimodal vision-language model delivering state-of-the-art performance on visual document comprehension and zero-shot tasks.
- [Nemotron 3.5 Super-VL](https://github.com/NVIDIA/NeMo) — NVIDIA's open-weight multimodal model combining Transformer and Mamba-2 architectures for long-context vision analysis.
- [MiniCPM-V](https://github.com/OpenBMB/MiniCPM-V) — Efficient vision-language model series optimized for edge deployment, optical character recognition (OCR), and mobile execution.
- [OpenCLIP](https://github.com/mlfoundations/open_clip) — Open-source implementation of Contrastive Language-Image Pre-training (CLIP) for multi-modal text-image representation.

## Inference Engines & Local Runtimes

Execution engines, quantizers, and server infrastructure for hosting open-weight models efficiently.

### Local GPU & CPU Runtimes

- [Ollama](https://github.com/ollama/ollama) — Open-source framework for running, customizing, and managing local LLMs on macOS, Linux, and Windows.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — High-performance C/C++ inference engine enabling LLM execution on consumer hardware with GGUF quantization.
- [LM Studio](https://lmstudio.ai/) — Cross-platform desktop application for discovering, downloading, and running local open-weight LLMs offline.

### High-Throughput Server Engines

- [vLLM](https://github.com/vllm-project/vllm) — High-throughput and memory-efficient LLM serving engine featuring PagedAttention and dynamic batching.
- [TGI (Text Generation Inference)](https://github.com/huggingface/text-generation-inference) — Hugging Face's production-ready engine for deploying popular open-source LLMs with Tensor Parallelism.
- [SGLang](https://github.com/sgl-project/sglang) — Fast execution engine for complex LLM programs, multi-turn interactions, and structured JSON decoding.

## Fine-Tuning & Evaluation Toolkits

Frameworks for parameter-efficient fine-tuning (PEFT), model alignment, and systematic bench evaluation.

- [Unsloth](https://github.com/unslothai/unsloth) — Optimized open-source framework for fine-tuning LLMs up to 5x faster with 80% less memory usage.
- [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) — Streamlined tool for fine-tuning language models supporting LoRA, QLoRA, DeepSpeed, and FSDP configurations.
- [TRL (Transformer Reinforcement Learning)](https://github.com/huggingface/trl) — Full-stack library for training transformer models using SFT, DPO, PPO, and GRPO techniques.
- [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) — EleutherAI's standard framework for zero-shot and few-shot evaluation of open language models.

## Related Awesome Lists

- [Awesome AI Hardware](https://github.com/brandonhimpfen/awesome-ai-hardware) — Accelerators, NPUs, TPUs, kernel optimization, and open-source EDA design toolchains.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.
- [Awesome Python](https://github.com/brandonhimpfen/awesome-python) — Data science libraries, machine learning frameworks, and scientific computing packages.
- [Awesome Infrastructure Monitoring](https://github.com/brandonhimpfen/awesome-infrastructure-monitoring) — Telemetry collection engines, metrics pipelines, and GPU cluster monitoring tools.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
