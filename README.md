# Abeera Amir

**AI/ML Engineer** — agentic systems, computer vision, and RAG pipelines that ship as working products, not notebooks.

📧 abeera.amir.edu@gmail.com &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/abeera-amir-476aa72b1/) &nbsp;·&nbsp; Islamabad, Pakistan

---

## About

I'm a Computer Science undergraduate at NUST building AI systems end-to-end — from model fine-tuning and RAG pipelines to containerized, deployed products with live demos. My work centers on three things: multi-agent orchestration (LangChain/LangGraph/MCP), computer vision and multimodal models (YOLO, VideoMAE, CLIP, Siamese networks), and systems that fail gracefully — every project below is designed with fallback logic rather than a single point of failure.

Previously a Research Assistant at NUST's Optical Networks Lab, benchmarking NETCONF client performance across five languages under varying concurrency.

## Core Focus

- **Agentic AI** — LangGraph state machines, MCP server/client tooling, conditional routing, human-in-the-loop interrupts
- **RAG & Retrieval** — chunking strategy, embedding quality, ChromaDB, citation-grounded generation
- **Computer Vision** — object detection and fine-tuning (YOLOv8/v11), action recognition (VideoMAE), similarity learning (Siamese networks, contrastive loss)
- **Production Engineering** — async FastAPI backends, Docker/Kubernetes, deployment on Railway/Vercel/Streamlit Cloud

## Selected Work

**[CivicAI](https://github.com/Abeera16/CivicAi)** — A multi-agent RAG assistant for Pakistani government services. Six specialized agents (supervisor, router, retrieval, clarification, citation, fallback) coordinate through LangGraph with conditional routing, backed by an MCP server exposing web search and RAG tools with retry logic. FastAPI + PostgreSQL + React, containerized with Docker Compose.

**[SigLens](https://github.com/Abeera16/SigLens-Tiled-YOLO-Signature-Detection)** — A fine-tuned YOLOv8 model that finds handwritten signatures in PDFs of any length. Solves the small-object problem by tiling pages into overlapping crops instead of downscaling, then merges duplicate detections with NMS. Streams pages via a generator so memory stays constant regardless of document size. [Live demo](https://siglens-tiled-yolo-signature-detection-production.up.railway.app/).

**[SigVerify](https://github.com/Abeera16/SigVerify-Signature-Verification)** — A Siamese network trained with contrastive loss to distinguish genuine from forged signatures, on a 179-writer, ~4,000-image dataset. Uses a writer-disjoint train/test split to prevent leakage and ensure the model is evaluated on truly unseen handwriting. [Live demo](https://sigverify-signature-verification-xsnrayspnzfxzptn8x2ohn.streamlit.app/).

**[CineMind AI](https://github.com/Abeera16/CineMind-AI-Multimodal-Movie-Scene-Understanding-Story-Generation)** — A multimodal video-understanding platform that fuses YOLOv11 object detection, VideoMAE action recognition, and Qwen2.5-VL captioning into a temporal scene graph, then uses an LLM to generate grounded stories and answer questions about the footage. Every heavy model has a deterministic fallback, so the system degrades instead of failing outright.

**[Multi-Agent Business Research Assistant](https://github.com/Abeera16/Multi-Agent-Business-Research-Assistant-)** — A four-agent research pipeline (Clarity, Research, Validator, Synthesis) built on LangGraph with confidence-based validation loops and human-in-the-loop interrupts for query clarification, plus live web search via Tavily.

**[Meeting-to-Action Pipeline](https://github.com/Abeera16/Meeting-to-Action-Pipeline-Workflow-Automation-Agent-)** — Converts raw meeting transcripts into structured action items, decisions, and escalations via function-calling, then auto-drafts Slack messages and emails for high-confidence output while routing ambiguous items to human review.

**[KisanBot](https://github.com/Abeera16/KisanBot_AI-Powered-Farming-Assistant)** — A multilingual agricultural assistant for Pakistani farmers with voice, text, and image input, sub-2-second responses, automatic failover across Groq/Gemini/Whisper, and plant disease detection from photos.

*Additional projects — explainable image similarity, NDVI-based crop classification, IoT monitoring, and coursework — are on my [repositories page](https://github.com/Abeera16?tab=repositories).*

## Technical Skills

`Python` `TypeScript` `Java` `C++` `SQL`
`FastAPI` `Flask` `Django` `Node.js`
`LangChain` `LangGraph` `MCP` `OpenAI API` `Hugging Face Transformers`
`PyTorch` `Scikit-learn` `YOLO` `VideoMAE` `CLIP`
`ChromaDB` `PostgreSQL` `MongoDB` `Redis`
`Docker` `Kubernetes` `Railway` `Vercel`

## Education

**National University of Sciences and Technology (NUST)** — BS Computer Science, 2023–2027
