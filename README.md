<div align="center">

# Hi! I'm Víctor

*Junior AI Engineer at NTT DATA Spain · BSc Intelligent Systems Engineering (UIE) · MSc AI Research (AEPIA/UIMP, alongside full-time) · Formula 1 analytics*

</div>

<p align="center">
  <img src="assets/banner/banner.png" alt="Banner" width="900"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VforVitorio&show_icons=true&theme=radical&hide_border=true" alt="GitHub stats" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=VforVitorio&theme=radical&hide_border=true" alt="GitHub streak" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VforVitorio&layout=compact&theme=radical&hide_border=true&langs_count=8" alt="Top languages" height="160"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VforVitorio/VforVitorio/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VforVitorio/VforVitorio/output/github-snake.svg"/>
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/VforVitorio/VforVitorio/output/github-snake.svg" width="820"/>
  </picture>
</p>

I work mostly on AI applied to Formula 1: strategy systems, telemetry analysis, computer vision over race footage and a few side experiments outside motorsport. Junior AI Engineer at NTT DATA Spain (A Coruña), working across many areas of AI, from computer vision research to research into LLM behavior, agentic AI solutions and tooling such as Model Context Protocol (MCP) servers. Now pursuing a Master's Degree in Artificial Intelligence Research (AEPIA / UIMP) alongside his full-time role. Alumnus of the Cambridge Engineering Summer Programme (2023, Girton College).

---

## Featured projects

### F1-StratLab — multi-agent F1 strategy system

<p align="center">
  <a href="https://vforvitorio.github.io/f1stratlab-web/">
    <img src="assets/f1-stratlab/f1_stratlab_logo.png" alt="F1 StratLab" width="380"/>
  </a>
  <br/>
  <img src="assets/f1-stratlab/f1stratlab-arcade-demo.gif" alt="F1 StratLab arcade demo" width="680"/>
</p>

Final Degree Project. Seven ML models (XGBoost, TCN + MC Dropout, LightGBM, RoBERTa, SetFit, BERT-large, Whisper) plus a LangGraph multi-agent orchestrator and a 2D race replay UI. RAG over FIA regulations on Qdrant.

[github.com/VforVitorio/F1-StratLab](https://github.com/VforVitorio/F1-StratLab) · [Landing](https://vforvitorio.github.io/f1stratlab-web/) · [DeepWiki](https://deepwiki.com/VforVitorio/F1-StratLab)

### F1 AC Digital Twin — Assetto Corsa behavioral RL

Formula 1 digital twin trained with behavioral cloning and reinforcement learning over Assetto Corsa, with a Grafana / InfluxDB / Apache Kafka monitoring stack.

[github.com/VforVitorio/F1_AC_Digital_Twin](https://github.com/VforVitorio/F1_AC_Digital_Twin)

### F1 AI Team Detection — YOLOv12 over race footage

<p align="center">
  <img src="assets/team-detection/team-detection-demo.gif" alt="Team detection demo" width="540"/>
</p>

Detection and classification of F1 teams from race images and videos, with a derived feature that draws car-to-car gap in metres and seconds.

[github.com/VforVitorio/F1_AI_team_detection](https://github.com/VforVitorio/F1_AI_team_detection)

### F1 Telemetry Manager — multimodal telemetry analysis

<p align="center">
  <img src="assets/telemetry/telemetry-demo.gif" alt="F1 Telemetry Manager demo" width="600"/>
</p>

Streamlit + FastAPI tool for telemetry inspection, multimodal input and automatic reports. Vendored as a git submodule inside F1-StratLab.

[github.com/VforVitorio/F1_Telemetry_Manager](https://github.com/VforVitorio/F1_Telemetry_Manager)

### LexFlow — graph-based AI agent framework

<p align="center">
  <a href="https://github.com/VforVitorio/LexFlow">
    <img src="assets/lexflow/lexflow-banner.png" alt="LexFlow" width="476"/>
  </a>
</p>

Open-source framework for building graph-based AI agent systems on FastAPI and MCP tools. Chat-driven workflows, tool calling and a visual graph interface for debugging and orchestration. Powers my legalize-es legislation corpus.

[github.com/VforVitorio/LexFlow](https://github.com/VforVitorio/LexFlow)

### marginalia — handwritten notes to Obsidian Markdown

<p align="center">
  <img src="assets/marginalia/marginalia-demo.gif" alt="marginalia demo: a handwritten Kindle Scribe page transcribed to Markdown and exported to an Obsidian vault" width="476"/>
</p>

Turns Kindle Scribe handwritten notebooks into Obsidian Markdown. Import a Scribe PDF, OCR the handwriting (even math, as KaTeX), review it side by side, then export to your vault.

[github.com/VforVitorio/marginalia](https://github.com/VforVitorio/marginalia)

### lmcode — local coding agent CLI on LM Studio

A small CLI coding agent that runs entirely against a local LM Studio server. No cloud, no telemetry. Personal sandbox to explore tool-using agents on consumer hardware.

[github.com/VforVitorio/lmcode](https://github.com/VforVitorio/lmcode)

### variational_quantum_classifier — quantum ML on Rigetti

Variational quantum classifier built with PyQuil over Rigetti's NISQ infrastructure, applied to spiral dataset separation. Side experiment outside motorsport.

[github.com/VforVitorio/variational_quantum_classifier](https://github.com/VforVitorio/variational_quantum_classifier)

---

## Tech I use day to day

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" height="28" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" height="28" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" height="28" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" height="28" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" height="28" alt="NumPy"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" height="28" alt="pandas"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" height="28" alt="Plotly"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" height="28" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" height="28" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" height="28" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" height="28" alt="Model Context Protocol"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" height="28" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" height="28" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" height="28" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" height="28" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" height="28" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" height="28" alt="Git"/>
</p>

---

## Education and certifications

- Master's Degree in Artificial Intelligence Research — AEPIA / UIMP (in progress)
- Bachelor's in Intelligent Systems Engineering — UIE Coruña · **graduated with a 9.0/10 average and 4 Distinctions (Matrícula de Honor)** · thesis awarded Distinction (Matrícula de Honor) and recommended for conversion into a research paper
- Engineering Summer Programme 2023 — Girton College, Cambridge University
- Deep Learning Specialization — DeepLearning.AI
- PyTorch for Deep Learning Professional Certificate — Coursera
- IBM Deep Learning with PyTorch, Keras and TensorFlow — Coursera
- DeepLearning.AI Data Analytics Professional Certificate — Coursera

---

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/victorvegasobral/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="34" alt="LinkedIn"/></a>
  &nbsp;
  <a href="https://www.victorvegasobral.com"><img src="https://img.shields.io/badge/Portfolio-6c5ce7?style=for-the-badge&logo=googlechrome&logoColor=white" height="34" alt="Portfolio"/></a>
  &nbsp;
  <a href="https://medium.com/@VforVitorio/"><img src="https://img.shields.io/badge/Medium-111111?style=for-the-badge&logo=medium&logoColor=white" height="34" alt="Medium"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=VforVitorio&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views"/>
</p>
