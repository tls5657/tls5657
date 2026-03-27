# Hi, I'm Yuseong Joo

AI Engineer focused on production LLM/VLM systems, document intelligence, OCR, retrieval, and local inference serving.

- building real-world AI workflows for industrial safety and document automation
- working across backend APIs, async job pipelines, local model serving, and structured extraction
- interested in inference systems, multimodal pipelines, and practical reasoning control

## Current Role

**WESOLUTION Inc.**  
AI Engineer, Internship -> Full-time  
2025.07 - Present

Current work includes:

- production-oriented LLM/RAG services
- multimodal document analysis and OCR workflows
- work-standard and risk-assessment automation pipelines
- local `llama.cpp` / `llama-server` deployment and debugging

## Focus Areas

- Production LLM/VLM Systems
- Document Intelligence / OCR
- Retrieval-Augmented Generation
- Structured Extraction Pipelines
- FastAPI + Celery + Redis Backends
- Local GGUF Inference with `llama.cpp`

## Selected Work

### 1. Safety RAG & Document Intelligence Platform

Repository: [Safety_RAG_LLM](https://github.com/tls5657/Safety_RAG_LLM)

Built and evolved a production-oriented AI system for:

- legal and safety QA
- KRAS-style risk assessment assistance
- work-standard extraction from PDFs and images
- OCR / VLM-based structured document processing
- TBM audio transcription and summarization

Key engineering themes:

- multimodal inference pipelines
- asynchronous AI job processing
- retrieval and reranking integration
- structured generation for downstream workflows

### 2. Progressive Reasoning Control for `llama.cpp`

Repository: [think-control](https://github.com/tls5657/think-control)

Built a small `llama.cpp` patchset for progressive `</think>` logit-bias control:

- per-request `think_control` JSON
- server-side validation and token resolution
- sampler-chain integration
- staged reasoning-length control for local inference workloads

### 3. Object Detection Research

Repository: [Object-Detection-Research](https://github.com/tls5657/Object-Detection-Research)

Research-oriented work around object detection model improvement and experimentation.

### 4. Voice Assistant

Repository: [voice-assistant](https://github.com/tls5657/voice-assistant)

Built a local voice-assistant system combining speech, language, and application control flows.

## Technical Highlights

- designed API and worker flows with `FastAPI`, `Celery`, and `Redis`
- deployed local GGUF models with `llama-server`
- handled multimodal OCR/VLM pipelines in real document workflows
- built staged extraction flows for industrial work-standard documents
- tuned inference behavior for reliability under structured-output workloads
- extended `llama.cpp` with a custom sampler-level reasoning control patch

## Education

**Dong-A University**  
B.S. in Artificial Intelligence  
2020 - 2026

## Contact

- Email: cyd1642@naver.com
- GitHub: https://github.com/tls5657
