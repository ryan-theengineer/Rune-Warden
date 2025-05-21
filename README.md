# Rune-Warden
RuneWarden is a ritualized, LLM-powered log parser and report generator that transforms raw red team findings into narrative-driven executive reports. Built for clarity, privacy, and power.

## 🛤️ RuneWarden Roadmap

*A disciplined path from idea to impact. This project will be built with intention, transparency, and purpose—line by line, rune by rune.*

---

### 🔹 v0.1 – The Spark (Foundations)
> *Goal: Prove the concept. Start the fire.*

- [x] Create public GitHub repo  
- [x] Choose license (MIT recommended)  
- [x] Establish initial README and core vision  
- [x] Build first working Nmap parser (`parser_nmap.py`)  
- [ ] Create standard log input format (JSON/dict schema)  
- [ ] Structure project folders (`parsers/`, `reports/`, `engines/`, `core/`)

---

### 🔹 v0.2 – The Prompt Engine (LLM Integration Begins)
> *Goal: Convert logs into meaningful prompts for natural language generation.*

- [ ] Build `prompt_engine.py` with template for vulnerability narration  
- [ ] Add support for client context (`target_type`, `data_sensitivity`)  
- [ ] Create default prompt style (`executive`, `mythic`, `minimalist`)  
- [ ] Implement basic CLI prompt preview system

---

### 🔹 v0.3 – LLM Core (Narrative Intelligence)
> *Goal: Generate actual summaries using local or fallback LLM.*

- [ ] Add `llm_runner.py`  
- [ ] Support local LLMs via `llama.cpp` / `Ollama`  
- [ ] Add OpenAI fallback support (optional)  
- [ ] Prompt → LLM → Summary output system  
- [ ] Privacy config flags for local-only mode

---

### 🔹 v0.4 – Renderer (The Ritual of Reporting)
> *Goal: Export the output in clean, stylized formats.*

- [ ] Build `report_generator.py`  
- [ ] Support Markdown and PDF exports  
- [ ] Add style templates: Mythic, Executive, Cyberpunk  
- [ ] Auto-generate TOC, timestamps, impact matrix

---

### 🔹 v0.5 – Red Team MVP
> *Goal: Complete working pipeline from log → report.*

- [ ] Nmap + Manual note ingestion  
- [ ] Context addition  
- [ ] LLM-based summary  
- [ ] Stylized PDF export  
- [ ] CLI interface for whole flow  
- [ ] Sample red team test case

---

### 🔹 v0.6 – Burp Parser + Enhancements
> *Goal: Expand log support beyond Nmap.*

- [ ] `parser_burp.py`  
- [ ] Additional output schema for multiple targets  
- [ ] Command chaining  
- [ ] More robust error handling

---

### 🔹 v0.7 – Contextual Intelligence
> *Goal: Deepen awareness of real-world business impact.*

- [ ] Add `context_enricher.py` (e.g., known risks, compliance tags)  
- [ ] Risk matrix auto-scoring  
- [ ] Custom tagging system

---

### 🔹 v0.8 – Modular Plugins
> *Goal: Allow community to extend.*

- [ ] Plugin framework for new parsers  
- [ ] Hook system for pre/post-processing  
- [ ] Configuration via YAML or TOML

---

### 🔹 v0.9 – UI Portal (Optional Flask GUI)
> *Goal: Provide optional web-based access for teams.*

- [ ] Flask or FastAPI interface  
- [ ] Upload logs, select report format, download result  
- [ ] Multi-user access control

---

### 🔹 v1.0 – Public Launch
> *Goal: Ship RuneWarden with pride.*

- [ ] Polish docs, examples, templates  
- [ ] Release on GitHub with badge, demo report  
- [ ] Begin outreach to red teams, CTF orgs, pentest firms  
- [ ] Build showcase page or launch site

---

**🗡️ Status:** _This roadmap is actively being forged in code. Contributions, feedback, and followers of the flame are welcome._
