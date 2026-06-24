# Agentic AI — Project 1

> **Category:** Agentic AI &nbsp;·&nbsp; **Type:** Jupyter notebook project

## Overview

### **Background Story**

In the rapidly evolving world of finance and technology, investors are constantly seeking ways to make smarter decisions by combining traditional financial analysis with emerging technological insights. While stock market trends provide a numerical perspective on growth, an organization’s initiatives in cutting-edge fields like Artificial Intelligence (AI) reveal its future readiness and innovation potential. However, analyzing both dimensions - quantitative financial performance and qualitative AI initiatives - requires sifting through multiple, diverse data sources: stock data from platforms like Yahoo Finance, reports in PDFs, and contextual reasoning using Large Language Models (LLMs).

This is where **DualLens Analytics** comes in. By applying a dual-lens approach, the project leverages **Retrieval-Augmented Generation (RAG)** to merge **financial growth data** with **strategic insights from organizational reports**. Stock data provides evidence of stability and momentum, while AI initiative documents reveal forward-looking innovation. Together, they form a richer, more holistic picture of organizational potential.

With DualLens Analytics, investors no longer need to choose between numbers and narratives—they gain a unified, AI-driven perspective that ranks organizations by both financial strength and innovation readiness, enabling smarter, future-focused investment strategies.

### **Problem Statement**

Traditional investment analysis often focuses on financial metrics alone (e.g., stock growth, revenue, market cap), missing the qualitative dimension of how prepared a company is for the future. On the other hand, qualitative documents like strategy PDFs contain valuable insights about innovation and AI initiatives, but they are difficult to structure, query, and integrate with numeric financial data.

This leads to three core challenges:

  1. **Fragmented Data Sources:** Financial data (stock prices) and strategic insights (PDFs) exist in silos.

  2. **Limited Analytical Scope:** Manual analysis of growth trends and PDF reports is time-consuming and error-prone.

  3. **Decisional Blind Spots:** Without integrating both quantitative (growth trends) and qualitative (AI initiatives) signals, investors may miss out on high-potential organizations.

### **Solution Approach**

To address this challenge, we set out to build a **Retrieval-Augmented Generation (RAG)** powered system that blends financial trends with AI-related strategic insights, helping investors rank organizations based on growth trajectory and innovation capacity.

## Project deep dive

This repository contains a complete, end-to-end notebook for **Agentic AI**.
It walks through the full workflow — from framing the problem and exploring the
data, through modeling and evaluation, to the conclusions and recommendations.

- **46 code steps** of analysis and modeling
- Full outputs, tables, and visualizations preserved in the rendered HTML
- A runnable `notebook.ipynb` so you can re-execute and extend the work

## Tech stack

`langchain`, `langchain-community`, `langchain-openai`, `matplotlib`, `pandas`, `yfinance`, `zipfile`

## What's in this repo

| File | Description |
|------|-------------|
| [`notebook.ipynb`](notebook.ipynb) | The runnable notebook (code recovered from the original export) |
| [`agentic-ai-project-1.html`](agentic-ai-project-1.html) | Full rendered notebook with **all outputs & plots** preserved |
| `requirements.txt` | Python dependencies inferred from the notebook |

## View the notebook

GitHub renders `.ipynb` files inline — just open [`notebook.ipynb`](notebook.ipynb).
For the fully-rendered version with every saved output and figure:

- **Rendered notebook (nbviewer):** https://nbviewer.org/github/Porche22/agentic-ai-project-1/blob/main/notebook.ipynb
- **Rendered HTML export:** https://htmlpreview.github.io/?https://github.com/Porche22/agentic-ai-project-1/blob/main/agentic-ai-project-1.html

> Replace `Porche22` with your GitHub username after pushing.

## Run it locally

```bash
git clone https://github.com/Porche22/agentic-ai-project-1.git
cd agentic-ai-project-1
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

---

<sub>Notebook reconstructed from an nbconvert HTML export; code cells recovered
faithfully, rich outputs are preserved in the accompanying `.html`.</sub>
