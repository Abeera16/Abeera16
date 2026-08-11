<p align="center">
  📧 <a href="mailto:abeeraamir347@gmail.com"><b>abeeraamir347@gmail.com</b></a> &nbsp;|&nbsp;
 
</p>

<h1 align="center">Hi, I'm Abeera 👋</h1>
<h3 align="center">AI/ML Engineer — Computer Vision, LLM Agentic Systems & RAG</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=Multi-Agent+Systems+(LangGraph+%2B+MCP);Computer+Vision+%2B+YOLO+%2F+VideoMAE+%2F+CLIP;RAG+%2B+Vector+Search+(ChromaDB);Model+Fine-Tuning+(PyTorch+%2B+LoRA)" alt="Typing SVG" />
</p>

---

### 🧠 About Me

- 🎓 Computer Science undergraduate at **NUST**, building production-grade AI systems end-to-end — not theoretical exercises
- 🔭 Focused on **agentic LLM systems** (LangChain, LangGraph, MCP) and **computer vision** (YOLO, VideoMAE, CLIP, Siamese Networks)
- 🧪 Ship real, working products: model fine-tuning → containerized deployment (Docker, Railway, Streamlit Cloud) → live public demos
- 🧩 Every AI pipeline I build is designed with **graceful degradation** — deterministic fallbacks when a model or API isn't available, not crashes
- 🔬 Past research: benchmarked NETCONF clients across 5 languages for Software-Defined Optical Networks at NUST's ONT Lab

---

### ⚙️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**AI/LLM & Agentic Systems:** LangChain · LangGraph (state graphs, tools, memory, conditional routing) · MCP (server & client) · OpenAI · Groq · Gemini · Hugging Face Transformers · function/tool calling
**Computer Vision & Multimodal AI:** YOLOv8/YOLOv11 · VideoMAE · CLIP · Siamese Networks · Qwen2.5-VL · scene-graph construction · image captioning (LSTM, GPT-2)
**RAG & Vector Search:** Chunking strategies · embeddings · ChromaDB · retrieval-quality tuning · citation-grounded generation
**Model Fine-Tuning:** PyTorch · Scikit-learn · LoRA / prefix-tuning · transfer learning · GPU-accelerated training

---

### 🚀 Featured AI/ML Projects

**🏛️ [CivicAI — Pakistan Citizen Services Assistant](https://github.com/Abeera16/CivicAi)**
`Python · FastAPI · LangChain · LangGraph · MCP · ChromaDB`
Production multi-agent LangGraph workflow (supervisor, router, retrieval, clarification, citation, fallback agents) with conditional routing and human-in-the-loop clarification. Built an MCP server/client exposing web search, API lookups, and ChromaDB RAG search as unified tools, with a full chunking → embedding → retrieval pipeline grounded in a live-scraped knowledge base.

**🖋️ [SigLens — Tiled YOLO Signature Detection](https://github.com/Abeera16/SigLens-Tiled-YOLO-Signature-Detection)** · [Live Demo](https://siglens-tiled-yolo-signature-detection-production.up.railway.app/)
`YOLOv8 · PyTorch · Computer Vision`
Fine-tuned YOLOv8 detector that tiles PDF pages into overlapping crops so small handwritten signatures stay above the model's detectable resolution, merging duplicate hits via NMS. Generator-based PDF streaming keeps memory flat regardless of document length.

**✅ [SigVerify — Signature Verification](https://github.com/Abeera16/SigVerify-Signature-Verification)** · [Live Demo](https://sigverify-signature-verification-xsnrayspnzfxzptn8x2ohn.streamlit.app/)
`Siamese Networks · Contrastive Loss · PyTorch`
Siamese Neural Network embedding genuine/forged signatures into a discriminative space via contrastive loss, trained on a 179-writer, ~4,000-image dataset with a writer-disjoint train/val/test split to prevent data leakage — reports precision/recall/F1 with tuned similarity thresholds.

**🎬 [CineMind AI — Multimodal Movie Scene Understanding](https://github.com/Abeera16/CineMind-AI-Multimodal-Movie-Scene-Understanding-Story-Generation)**
`YOLOv11 · VideoMAE · Qwen2.5-VL · Qwen2.5-7B`
Fuses YOLOv11 object detection, VideoMAE action recognition, and Qwen2.5-VL captioning into a unified temporal scene graph, then uses an LLM to generate grounded stories and answer questions about video content — every heavy model backed by a deterministic heuristic fallback.

**🌾 [KisanBot — AI-Powered Agricultural Assistant](https://github.com/Abeera16/KisanBot_AI-Powered-Farming-Assistant)**
`Groq · Gemini · Whisper`
Multilingual voice/text/image assistant for farmers with multi-provider LLM failover and bidirectional translation across six regional languages, plus plant disease detection from images — sub-2-second response times.

**🔎 [Multi-Agent Business Research Assistant](https://github.com/Abeera16/Multi-Agent-Business-Research-Assistant-)**
`LangGraph · LangChain · Tavily · OpenAI`
Clarity/Research/Validator/Synthesis agent pipeline with conditional routing, confidence-based validation loops, human-in-the-loop interrupts, and cost-aware LLM usage tracking.

**📝 [Meeting-to-Action Pipeline](https://github.com/Abeera16/Meeting-to-Action-Pipeline-Workflow-Automation-Agent-)**
`NLP · Slack API · Function Calling`
Converts meeting transcripts into structured action items/decisions/escalations via tool-calling, with a confidence-scored pipeline routing ambiguous items to human review and deterministic parsing as a fallback.

**🖼️ [SimSense — Explainable Image Similarity](https://github.com/Abeera16/SimSense-Explainable-Image-Similarity)**
`CLIP · GPT-2 · Prefix-Tuning`
Fuses CLIP embeddings with a GPT-2 decoder via a custom prefix-tuning network to explain *why* images are similar, not just that they are — evaluated with BLEU/ROUGE/METEOR/CIDEr/BERTScore/CLIPScore.

**🌍 [NDVI Crop Classification (Rice & Cotton)](https://github.com/Abeera16/NDVI-Based-Crop-Classification-for-Rice-and-Cotton-Using-Machine-Learning)**
`Random Forest · SVM · XGBoost · K-Means`
Classifies crops from multi-year NDVI time-series using supervised and unsupervised models, with an interactive dashboard comparing results across train/test split strategies.

---

### 📊 GitHub Stats
<p align="center"> <img height="165" src="https://github-readme-stats.vercel.app/api?username=Abeera16&show_icons=true&theme=tokyonight&hide_border=true" /> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abeera16&layout=compact&theme=tokyonight&hide_border=true" /> </p> <p align="center"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abeera16&theme=tokyonight&hide_border=true" alt="GitHub Streak" /> </p> <p align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Abeera16&theme=react-dark&hide_border=true" alt="Contribution Graph" /> </p>
