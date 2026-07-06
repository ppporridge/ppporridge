# Hi, I'm Jialei Zhou (周佳蕾) 👋

🎓 Incoming Direct-entry Ph.D. student at **Peking University**, Class of 2026

🔭 **Research Interests**: Diffusion Transformers · Text-to-Image Generation · Generative Compression · Multimodal Understanding and Generation

💡 My recent work builds self-verifying, self-correcting mechanisms into generative models — from entropy-driven adaptive decoding to inference-time consistency checks that feed semantic residuals back into generation. Broadly interested in self-improving / iterative-refinement paradigms for large models.

🌱 Currently open to **New ideas** and **Free Talks**

📫 Reach me: jialeizzzhou@163.com · [Hugging Face](https://huggingface.co/ppporridge)

---

## 📌 Selected Work

### 🗂️ CATCH — Dataset 
**A conversational portrait video dataset for explicit hand–face dynamics**

Built to address the lack of hand-motion data support in Generative Face Video Compression (GFVC) under real communication scenarios, using a structured prompt taxonomy to explicitly cover hand dynamics and hand–face interaction.

### 🧭 Semantic Compass
**Understanding-Enhanced Generation Framework for Unified Diffusion MLLMs**

Unified multimodal diffusion models often lose prompt fidelity in text-to-image generation. **Semantic Compass** is a training-free, inference-time self-checking framework: it parses structured semantic attributes from both the original prompt and intermediate generations, runs a consistency check between them, and converts detected inconsistencies into semantic residuals that are injected back into subsequent generation steps — a self-verifying, self-correcting generation loop.

### 🧩 Swordsman — *ICML 2026*
**Entropy-Driven Adaptive Block Partitioning for Diffusion Language Model Decoding**

Diffusion language models typically decode with fixed block partitions, which breaks semantic structure across block boundaries. **Swordsman** adaptively locates semantic boundaries by tracking entropy shifts between adjacent tokens, and dynamically adjusts the unmasking threshold based on in-block decoding state — improving inference efficiency, stability, and generation quality without additional training.

### 📄 DiT-ST — *NeurIPS 2025*
**Enhancing Text-to-Image Diffusion Transformer via Split-Text Conditioning**


Diffusion Transformers (DiTs) struggle to fully comprehend complex, complete-text captions, often overlooking details or causing semantic confusion (e.g. attribute misbinding). **DiT-ST** addresses this by decomposing a complete-text caption into a *split-text caption* — a set of simplified sentences that explicitly express individual semantic primitives — and injecting them hierarchically and incrementally across different denoising stages of the DiT.


---

## 📊 GitHub Stats

![Jialei's GitHub stats](https://github-readme-stats.vercel.app/api?username=ppporridge&show_icons=true&theme=default)

> Research-driven. Detail-oriented. Always learning.
