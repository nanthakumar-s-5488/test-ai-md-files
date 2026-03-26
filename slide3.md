# 🃏 Slide 3 — Markdown for AI Documentation & Model Cards

---

## 🤔 What Are AI Model Cards and Why They Matter?

A **Model Card** is a short document that provides key facts about an AI model, including:

- **Intended use** — what the model is designed for
- **Evaluation results** — how well the model performs and on what benchmarks
- **Limitations and biases** — known failure modes and fairness considerations
- **Ethical considerations** — potential misuse and societal impact

Model cards promote **transparency**, **accountability**, and **responsible AI** deployment.

> 📌 First introduced by Google researchers in the paper *"Model Cards for Model Reporting"* (Mitchell et al., 2019).

---

## 🤗 Using Markdown to Create Model Cards (Hugging Face)

Hugging Face hosts thousands of AI models — every one is documented with a **Markdown model card** in the repository's `README.md`:

```markdown
---
language: en
license: apache-2.0
tags:
  - text-classification
  - sentiment-analysis
datasets:
  - sst2
metrics:
  - accuracy
---

# My Sentiment Model 🎭

## Model Description
This model classifies text as **positive** or **negative** sentiment.

## Intended Uses & Limitations
- ✅ Suitable for English social media text
- ❌ Not suitable for medical or legal documents

## Training Data
Trained on the Stanford Sentiment Treebank (SST-2).

## Evaluation Results
| Metric   | Value |
|----------|-------|
| Accuracy | 94.2% |
| F1 Score | 93.8% |
```

---

## 📊 Documenting Datasets with Markdown (Datasheets for Datasets)

Inspired by *"Datasheets for Datasets"* (Gebru et al., 2018), Markdown is used to create thorough dataset documentation:

```markdown
# Dataset Card: MyTextDataset 📚

## Dataset Summary
A collection of 50,000 news articles labeled for topic classification.

## Dataset Structure
- **Size:** 50,000 samples
- **Languages:** English
- **Labels:** Politics, Sports, Technology, Health

## Source Data
Scraped from public news sites between 2020–2023.

## Considerations for Using the Data
- May contain reporting bias from specific outlets
- Not suitable for time-sensitive applications
```

---

## ✅ Best Practices for AI Project Documentation in MD Format

| Practice | Description |
|----------|-------------|
| 🗂️ Use clear headings | Organize with `#`, `##`, `###` for hierarchy |
| 📋 Include a quick-start section | Always show how to install and run in < 5 lines |
| 📊 Add performance tables | Compare metrics with baselines |
| 🔗 Link to related resources | Papers, datasets, demos, notebooks |
| ⚠️ Document limitations | Be transparent about what the model cannot do |
| 🔄 Keep docs up to date | Update the README with every new release |
| 🌍 Add a license section | Clearly state terms of use |

---

## 🧭 Navigation

| | | |
|---|---|---|
| [← Previous: Role in AI](slide2.md) | 🏠 [Home](index.md) | [Next: Tools & Platforms →](slide4.md) |
