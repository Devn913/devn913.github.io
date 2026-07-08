---
layout: page
title: SimpleRAG
description: RAG-based web app for interactive PDF querying using LangChain, Gemini AI, and FAISS
img: assets/img/11.jpg
importance: 2
category: ai
github: devn913/rag-docqa-endee
---

A production-ready **Retrieval-Augmented Generation (RAG)** web application that enables users to interactively query PDF documents using natural language — powered by Google Gemini AI.

## Architecture

```
PDF Upload → Text Extraction → Recursive Chunking
     → FAISS Vector Index → Query → Gemini AI → Answer
```

## Features

- **Interactive PDF querying** via natural language
- **Google Gemini AI** for contextually accurate, grounded responses
- **FAISS vector storage** for high-performance similarity search
- **Recursive text chunking** to preserve context across document sections
- Django-based backend with clean UI

## Tech Stack

`Python` · `LangChain` · `Gemini AI` · `FAISS` · `Django`
