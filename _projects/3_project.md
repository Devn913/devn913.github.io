---
layout: page
title: Paper2Code
description: Automating code generation from scientific ML papers using LLMs
img: assets/img/7.jpg
importance: 3
category: ai
github: devn913/Paper2Code
---

**Paper2Code** automates the process of converting machine learning research papers into runnable code — bridging the gap between theory and reproducibility.

## Motivation

ML research reproducibility is a known challenge. Paper2Code reduces the barrier by automatically extracting algorithms and experimental setups from papers and generating corresponding implementation code via LLMs.

## Approach

- Parse scientific paper structure (abstract, methods, experiments)
- Extract algorithmic pseudocode and architecture descriptions
- Generate runnable Python/PyTorch implementations via LLM prompting
- Validate against paper-reported results where possible

## Tech Stack

`Python` · `LLMs` · `PDF Parsing` · `PyTorch` · `LangChain`
