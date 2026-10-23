# NIM-AI

<p align="center">
  <b>Architecting specialized, efficient, and reasoning-driven frontier AI systems.</b><br>
  <i>Home of NIM 3 — Coder and specialized machine learning research pipelines.</i>
</p>

<p align="center">
  <a href="https://huggingface.co/NIM-AI"><img src="https://img.shields.io/badge/Hugging%20Face-NIM--AI-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat" alt="License" />
  <img src="https://img.shields.io/badge/Architecture-Sparse_MoE-8A2BE2?style=flat" alt="MoE Architecture" />
  <img src="https://img.shields.io/badge/Specialization-Systems_&_Reasoning-00C853?style=flat" alt="Focus" />
</p>

---

## ⚡ Mission

At **NIM-AI**, we engineer compact, accessible, and highly capable artificial intelligence models. Rather than relying solely on massive brute-force dense scaling, we combine **sparse dynamic routing (MoE)**, targeted **knowledge distillation**, and structured **Chain-of-Thought (CoT)** reasoning traces to deliver production-grade intelligence that runs smoothly across both cloud instances and constrained edge hardware.

---

## 🌟 Flagship Projects

### 🧠 [NIM 3 - Coder - 30B](https://github.com/NIM-AI/NIM-3-Coder-30B)
A state-of-the-art **30.5B-parameter Sparse Mixture-of-Experts (MoE)** model optimized for high-performance software engineering, low-level systems programming, and complex architecture planning.
* **Sparse Dynamic Activation:** Activates only **~3B parameters per token**, providing 30B-level comprehension at 3B-class inference latency.
* **Supervised Reasoning Traces:** Evaluates edge cases, race conditions, memory safety, and algorithmic complexity inside `<think>...</think>` tokens before generating verified, idiomatic code.
* **Native Formats:** Available in FP16, BF16, and **`q4_k_m` GGUF** for direct execution in Ollama, llama.cpp, and vLLM.

```bash
# Pull and run NIM 3 - Coder instantly via Ollama
ollama run hf.co/NIM-AI/NIM-3-Coder-30B-GGUF:Q4_K_M

🚀 Repositories at a Glance
NIM-3-Coder-30B: Full training notebooks, curated distillation datasets, LoRA integration, and deployment recipes for our flagship coding model.
nim-distill-toolkit: Reusable dataset generation tools, format converters, and validator scripts for structuring high-density <think> reasoning traces.
🌐 Community & Ecosystem
Hugging Face Hub: huggingface.co/NIM-AI (Weights, LoRA Adapters, and GGUF Quants)
Organization Inquiries: Open an issue in any public repository or reach out via our official communication channels.
Built by NIM-AI. Empowering developers with transparent, efficient, reasoning-first AI.
