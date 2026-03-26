# 🛠️ Slide 4 — Tools & Platforms Using Markdown in AI

---

## 🐙 GitHub & GitHub Pages for AI Projects

**GitHub** is the #1 platform for open-source AI — and Markdown is at the heart of it:

- Every repository has a `README.md` rendered as the project's landing page
- **Issues and Pull Requests** support full Markdown formatting
- **GitHub Pages** turns Markdown files into static websites using Jekyll:

```yaml
# _config.yml
theme: jekyll-theme-cayman
title: "My AI Project"
description: "A powerful open-source ML library"
```

- Projects like **TensorFlow**, **PyTorch**, **Hugging Face Transformers**, and **scikit-learn** all rely heavily on Markdown documentation hosted on GitHub Pages.

---

## 📓 Jupyter Notebooks (Markdown Cells)

Jupyter Notebooks are the gold standard for interactive AI research:

- **Markdown cells** let researchers annotate code with rich text, images, and math
- Supports **LaTeX** for mathematical notation:

```markdown
## Model Architecture

The attention mechanism is computed as:

$$\text{Attention}(Q, K, V) = \text{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V$$
```

- Notebooks can be **exported to HTML or PDF**, with Markdown rendered beautifully
- Platforms: **Jupyter Lab**, **Google Colab**, **Kaggle Notebooks**, **VS Code Notebooks**

---

## 🤗 Hugging Face (Model Cards in MD)

Hugging Face has standardized Markdown as the format for all AI model and dataset cards:

- Every model on [huggingface.co](https://huggingface.co) has a `README.md` model card
- YAML front matter provides structured metadata parsed by the platform:

```yaml
---
language: en
license: mit
pipeline_tag: text-generation
---
```

- The **Hub** renders Markdown with syntax highlighting, tables, and math
- Supports **dataset cards**, **space cards**, and **collection README files**
- Powers discoverability of **500,000+ models** and **100,000+ datasets**

---

## 📚 MkDocs / Docusaurus for AI Documentation Sites

For larger AI projects needing full documentation websites:

### MkDocs
```yaml
# mkdocs.yml
site_name: My AI Library
nav:
  - Home: index.md
  - Getting Started: getting-started.md
  - API Reference: api.md
theme:
  name: material
```

### Docusaurus
```bash
npx create-docusaurus@latest my-ai-docs classic
# Write all docs in Markdown (.md / .mdx)
```

- Popular themes: **Material for MkDocs**, **ReadTheDocs**
- Used by: **LangChain**, **FastAI**, **ONNX Runtime**

---

## 💻 VS Code Markdown Extensions for AI Developers

VS Code is the most popular editor for AI developers — with great Markdown support:

| Extension | Purpose |
|-----------|---------|
| **Markdown All in One** | Shortcuts, preview, TOC generation |
| **Markdown Preview Enhanced** | Advanced rendering with math & diagrams |
| **Mermaid Markdown** | Create flowcharts and diagrams in MD |
| **Markdown PDF** | Export Markdown to PDF |
| **Jupyter** | Edit notebooks with rich Markdown cells |
| **GitHub Copilot** | AI-powered Markdown writing assistance |

---

## 🧭 Navigation

| | | |
|---|---|---|
| [← Previous: Model Cards](slide3.md) | 🏠 [Home](index.md) | [Next: Future of Markdown →](slide5.md) |
