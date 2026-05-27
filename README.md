# OpenMOSS

[OpenMOSS](https://github.com/OpenMOSS) presents a collection of our research on Large Language Models and Multimodal Foundation Models, supported by [Shanghai Innovation Institute (SII)](https://www.sii.edu.cn/), Fudan University, and MOSI.AI.

> 📌 This page is a curated overview. For the complete and most recent list of repositories, visit the [OpenMOSS organization](https://github.com/OpenMOSS).
>
> _Last updated: 2026-05-27 — 2 new repo(s) pending review: OurClaw,Ultra-Innerthought_

---

# Projects

## MOSS-LLM
Foundation language models and training infrastructure.

| Project | Description |
|---|---|
| [MOSS](https://github.com/OpenMOSS/MOSS) | An open-source tool-augmented conversational language model from Fudan University — the founding project of the OpenMOSS series. |
| [CoLLiE](https://github.com/OpenMOSS/CoLLiE) | A library for collaborative training of large language models in an efficient way. |

## MOSS-VL
Multimodal models for visual and video understanding.

| Project | Description |
|---|---|
| [MOSS-VL](https://github.com/OpenMOSS/MOSS-VL) | Core multimodal model series within the OpenMOSS ecosystem, dedicated to visual understanding. Includes the XRoPE architecture and a fully open training stack. |
| [MOSS-Video-Preview](https://github.com/OpenMOSS/MOSS-Video-Preview) | A real-time video understanding foundation model built on Llama-3.2-Vision, with comprehensively extended video processing and multimodal reasoning capabilities. |

## MOSS-Audio
End-to-end models for audio understanding and generation — speech, sound, music.

| Project | Description |
|---|---|
| [MOSS-TTS-Nano](https://github.com/OpenMOSS/MOSS-TTS-Nano) | A 0.1B-parameter open-source multilingual TTS model — runs in real time on CPU without a GPU, designed for local demos, web serving, and lightweight product integration. |
| [MOSS-TTS](https://github.com/OpenMOSS/MOSS-TTS) | Open-source TTS family covering stable long-form speech, multi-speaker dialogue, voice/character design, environmental sound effects, and real-time streaming TTS. |
| [MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) · [🤗 HF](https://huggingface.co/fnlp/MOSS-TTSD-v0.5) | Spoken dialogue generation model with expressive multi-speaker synthesis, long-context modeling, flexible speaker control, multilingual support, and zero-shot voice cloning. |
| [MOSS-Audio](https://github.com/OpenMOSS/MOSS-Audio) | Open-source foundation model for unified audio understanding — speech, sound, music, captioning, QA, and reasoning in real-world scenarios. |
| [MOSS-Audio-Tokenizer](https://github.com/OpenMOSS/MOSS-Audio-Tokenizer) | Causal Transformer-based audio tokenizer built on the CAT architecture. Trained on 3M hours of audio, supports streaming and variable bitrates, delivers SOTA reconstruction. |
| [MOSS-Speech](https://github.com/OpenMOSS/MOSS-Speech) | A true speech-to-speech large language model without text guidance. |
| [MOSS-Music](https://github.com/OpenMOSS/MOSS-Music) | Music understanding model for captioning, lyrics ASR, structural analysis, chord/key/tempo reasoning, and long-form musical QA. |
| [SpeechGPT-2.0-preview](https://github.com/OpenMOSS/SpeechGPT-2.0-preview) | GPT-4o-level, real-time spoken dialogue system. |

## MOSS-Omni
Unified multimodal generation across modalities.

| Project | Description |
|---|---|
| [AnyGPT](https://github.com/OpenMOSS/AnyGPT) | Unified multimodal LLM with discrete sequence modeling. |
| [MOVA](https://github.com/OpenMOSS/MOVA) | Towards scalable and synchronized video–audio generation. |

## MOSS-Robot
Embodied AI: humanoid control, robotic manipulation, and embodied planning.

| Project | Description |
|---|---|
| [FRoM-W1](https://github.com/OpenMOSS/FRoM-W1) | Towards general humanoid whole-body control with language instructions (arXiv 2026). Supports Unitree H1/G1 and FFTAI humanoid robots. |
| [RoboOmni](https://github.com/OpenMOSS/RoboOmni) | Proactive robot manipulation in omni-modal context. |
| [Embodied-Planner-R1](https://github.com/OpenMOSS/Embodied-Planner-R1) · [arXiv](https://arxiv.org/abs/2506.23127v1) | A reinforcement learning framework that enables LLMs to acquire embodied planning capabilities through autonomous exploration with sparse rewards. |
| [RoboJuDo](https://github.com/OpenMOSS/RoboJuDo) | Deployment framework for the FRoM-W1 humanoid project. |
| [VehicleWorld](https://github.com/OpenMOSS/VehicleWorld) | First comprehensive multi-device environment for intelligent vehicle interaction, modeling complex interconnected systems in modern cockpits. |

## MOSS-Aiology
Mechanistic interpretability of large language models.

| Project | Description |
|---|---|
| [Llamascopium](https://github.com/OpenMOSS/Llamascopium) · [🤗 HF](https://huggingface.co/fnlp/Llama-Scope) · [Neuronpedia](https://www.neuronpedia.org/llama-scope) | _(formerly Language-Model-SAEs)_ A performant, fully-distributed framework for training, analyzing, and visualizing Sparse Autoencoders (SAEs) and frontier variants, empowering scalable and systematic mechanistic interpretability research. |
| [Lorsa](https://github.com/OpenMOSS/Lorsa) | Low-rank sparse attention for interpretability. |

---

# Research

## Embodied-AI
The Embodied AI Team empowers large models to execute real-world tasks, aiming to automate tedious chores and unlock superhuman intelligence through environmental interaction. We believe true AI emerges from engaging with the physical world.

| Project | Venue | Description |
|---|---|---|
| **VLABench** · [arXiv](https://arxiv.org/abs/2412.18194) · [GitHub](https://github.com/OpenMOSS/VLABench) | ICCV 2025 | The first large-scale robot manipulation benchmark designed to fairly evaluate the multi-dimensional ability of general-purpose Vision-Language-Action models. |
| **D2PO** · [arXiv](https://arxiv.org/abs/2503.10480) · [GitHub](https://github.com/sinwang20/D2PO) | ACL 2025 | A unified learning framework that empowers embodied agents with stronger world modeling and embodied planning ability via dual preference optimization. |
| **World-Aware-Planning** · [arXiv](https://arxiv.org/pdf/2506.21230) · [GitHub](https://github.com/sii-research/World-Aware-Planning) | — | World-aware narrative enhancement bridging high-level task instructions and nuanced real-world environment details. |
| **Embodied-Planner-R1** · [arXiv](https://arxiv.org/abs/2506.23127v1) · [GitHub](https://github.com/OpenMOSS/Embodied-Planner-R1) | — | RL framework enabling LLMs to acquire embodied planning capabilities through autonomous exploration with sparse rewards. |
| **Awesome-WAM** · [GitHub](https://github.com/OpenMOSS/Awesome-WAM) | — | A curated, continuously updated reading list, paper blogs, and resources for World Action Models in embodied AI. |

## NewArch
The SII-OpenMOSS New Architecture Team explores new architectures and paradigms of LLMs, particularly from the perspective of long-context capability and efficiency.

| Project | Venue | Description |
|---|---|---|
| **ReAttention** · [arXiv](https://arxiv.org/abs/2407.15176) · [GitHub](https://github.com/OpenMOSS/ReAttention) | ICLR 2025 | Training-free approach that enables LLMs to support infinite context length extrapolation with finite attention scope. |
| **LongLLaDA** · [arXiv](https://arxiv.org/abs/2506.14429) · [GitHub](https://github.com/OpenMOSS/LongLLaDA) | AAAI 2026 | First systematic investigation comparing long-context performance of diffusion LLMs and traditional auto-regressive LLMs. |
| **RoPE++** · [GitHub](https://github.com/OpenMOSS/rope_pp) | ICLR 2026 | Beyond Real: imaginary extension of Rotary Position Embeddings for long-context LLMs. |
| **Sparse-dLLM** · [GitHub](https://github.com/OpenMOSS/Sparse-dLLM) | — | Sparse diffusion-based large language models. |
| **FourierAttention** · [arXiv](https://arxiv.org/abs/2506.11886) | — | Training-free framework that exploits the heterogeneous roles of transformer head dimensions. |
| **Thus Spake Long-Context LLM** · [arXiv](https://arxiv.org/abs/2502.17129) · [GitHub](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM) | — | A survey on the lifecycle of long-context LLMs from four perspectives: architecture, infrastructure, training, and evaluation. |

## Multimodal Evaluation

| Project | Venue | Description |
|---|---|---|
| **GAOKAO-MM** · [GitHub](https://github.com/OpenMOSS/GAOKAO-MM) | ACL 2024 Findings | A Chinese human-level benchmark for multimodal model evaluation. |

## Alignment & Safety

| Project | Venue | Description |
|---|---|---|
| **HalluQA** · [GitHub](https://github.com/OpenMOSS/HalluQA) | — | Dataset and evaluation script for evaluating hallucinations in Chinese large language models. |
| **Say-I-Don't-Know** · [GitHub](https://github.com/OpenMOSS/Say-I-Dont-Know) | ICML 2024 | Can AI assistants know what they don't know? |
| **LongSafety** · [GitHub](https://github.com/OpenMOSS/LongSafety) | — | Safety evaluation for long-context LLMs. |

## Tool Use & Agents

| Project | Description |
|---|---|
| **UnifiedToolHub** · [GitHub](https://github.com/OpenMOSS/UnifiedToolHub) | A comprehensive project supporting LLM-based tool use — unifies dataset formats and provides training, annotation, and evaluation functionalities. |
| **ABC-Bench** · [GitHub](https://github.com/OpenMOSS/ABC-Bench) | A benchmark for agentic backend coding — evaluates whether code agents can explore repos, edit code, configure environments, deploy services, and pass external end-to-end API tests. |

---

## Contact

For collaborations, internships, or general inquiries: **[openmoss@sii.edu.cn](mailto:openmoss@sii.edu.cn)**
