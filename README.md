# Li Tianming

**AI Agent & Systems Engineer** · Agent Engineering · AI Infrastructure · Embodied AI

M.S. candidate in Mechanical Engineering at Shanghai Jiao Tong University, with a B.S. in Artificial Intelligence from Chengdu University of Technology.

I build reliable LLM agents and performance-aware AI systems for real-world workflows. My current industry work focuses on an automotive compliance Agent; my public projects cover agent orchestration, evaluation, reproducible AI engineering, and Triton kernel optimization.

**Open to internships in AI Agent Engineering, AI Infrastructure, and Embodied AI Systems.**

[Personal site](https://determine123.github.io/determine/) · [Email](mailto:determine@sjtu.edu.cn) · [GitHub](https://github.com/determine123)

---

## Focus

| Priority | Direction | What I want to build |
|---|---|---|
| **Primary** | **AI Agent Engineering** | Tool-using agents, RAG, memory, workflow orchestration, evaluation, reliability, and production APIs |
| **Secondary** | **AI Infrastructure** | Inference performance, model serving, Triton/CUDA kernels, benchmarking, deployment, and cost-aware systems |
| **Long term** | **Embodied AI** | Reinforcement learning, robot decision systems, perception-action loops, and safety constraints |

## Featured engineering work

### [Multi-tool ReAct Agent](https://github.com/determine123/react-agent)

A modular Agent system with ReAct reasoning, tool calling, RAG, two-tier memory, LangGraph workflows, FastAPI, Gradio, evaluation, and Docker deployment.

- Registered 10 task-oriented tools behind a unified dispatch layer.
- Built document ingestion, retrieval, source return, and configurable embedding support.
- Added bounded execution, error fallback, API endpoints, a Web UI, and repeatable evaluation flows.
- Kept configuration and secrets outside the codebase for reproducible local deployment.

`Python` `LangGraph` `RAG` `ChromaDB` `FastAPI` `Gradio` `Docker`

### [DeepSeek-V3 Decode GEMM Optimization](https://github.com/determine123/flagos-s2-track1)

A multi-backend Triton optimization project for the tiny-M GEMM used by fused QKV-A down projection.

- Improved platform compatibility from 5/8 to 8/8 accelerator backends.
- Recorded a 2.50× platform-average speedup and Task 66 rank No. 8 in the published platform snapshot.
- Preserved an independent FP32 oracle, test coverage, deterministic packaging, hashes, and experiment provenance.
- Clearly separated platform-transcribed results from locally reproducible measurements.

`Python` `PyTorch` `Triton` `GEMM` `Benchmarking` `AI Infra`

### [R&D Daily Report Assistant](https://github.com/determine123/rd-efficiency-daily-assistant)

An evidence-first pipeline that turns Git activity and technical news into structured engineering reports without inventing progress or impact.

- Binds engineering claims to commit IDs and news items to sources or URLs.
- Uses deterministic generation by default, with an optional OpenAI-compatible LLM and safe fallback.
- Provides validation rules, unit tests, RSS/Git ingestion, FastAPI endpoints, and a LangGraph-compatible workflow.
- Includes only synthetic examples and documents data-safety boundaries.

`Python` `LangGraph` `FastAPI` `Git` `RSS` `Testing`

### Automotive Compliance Agent — industry internship, private

Building an LLM-assisted workflow for automotive material-compliance analysis. The production code, business rules, data, customer information, and internal architecture are confidential and are not published here.

The public portfolio will contain only independently recreated, synthetic examples after confidentiality review.

`Agent Workflow` `Structured Output` `Rule Checking` `Evaluation` `Data Safety`

## Selected project experience

These projects are not yet presented as public repositories. I list them as experience, not as open-source deliverables.

| Project | Engineering scope | Public status |
|---|---|---|
| **Drone obstacle avoidance with deep RL** | PPO/SAC comparison, Gym-PyBullet-Drones simulation, safety projection, and repeated experiments | Reproducibility package under cleanup |
| **BERT compression and edge deployment** | Knowledge distillation, ONNX/TensorRT optimization, and Jetson AGX Orin deployment | Code and benchmarks under cleanup |
| **Solar power forecasting** | Spatial downscaling, random-forest regression, time-series features, and research evaluation | Paper-related materials; release subject to author agreement |

## Technical stack

**Languages:** Python · C/C++ · TypeScript · SQL

**Agent and LLM systems:** ReAct · LangGraph · Function Calling · MCP · RAG · ChromaDB · RAGAS · Prompt and tool evaluation

**AI infrastructure and deployment:** PyTorch · Triton · CUDA performance analysis · ONNX · TensorRT · FastAPI · Docker · Jetson AGX Orin · Linux

**Reinforcement learning and robotics:** PPO · SAC · Gym-PyBullet-Drones · reward design · safety constraints · simulation-based evaluation

## Engineering principles

- **Evaluation before presentation:** define datasets, baselines, failure cases, and metrics before calling a system complete.
- **Evidence over claims:** keep results traceable to code, test output, experiment records, or platform snapshots.
- **Reproducibility by default:** document environments, commands, contracts, and known limitations.
- **Confidentiality by design:** never publish employer code, internal data, customer information, credentials, or reconstructed proprietary rules.

## Current work

- Hardening the public ReAct Agent with stronger task-level evaluation and observability.
- Learning inference systems through kernels, benchmarks, and reproducible experiments rather than notes alone.
- Preparing a public embodied-AI project with simulation, baselines, safety constraints, and video evidence.

## Technical notes

- [AI Infra Study](https://github.com/determine123/AI-Infra-study) — structured notes and experiments from foundations to inference and platform engineering.
- [Personal site](https://determine123.github.io/determine/) — education, projects, and longer-form technical material.

## Contact

- Email: [determine@sjtu.edu.cn](mailto:determine@sjtu.edu.cn)
- GitHub: [github.com/determine123](https://github.com/determine123)
- Location: Shanghai, China
