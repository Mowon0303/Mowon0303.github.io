---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

### University of Southern California
M.S. in Computer Science, May 2026

### University of California, Davis
B.S. in Computer Science, Fall 2023

## Research experience

### Research Assistant, SIAS Lab, University of Southern California
Fall 2025 to present

- Built a market simulator on New York City trip records that compares structured controllers, hybrid LLM interfaces, and full LLM agents under fleet and pricing constraints.
- Designed component-matched attribution experiments that isolate where language models help or hurt operational decisions.
- Implemented local LLM controller workflows, audit scripts, and a regression test suite for the simulator.

### Social Interaction Proxy Project
Team of 10

- Developed a virtual environment for human-to-human interaction studies, with data collection, data transformation, and analysis tools for researchers.

## Publications

{% for post in site.publications reversed %}
  {% include publication-item.html %}
{% endfor %}

## Skills

- **Programming:** Python, C, C++, Java, Go, C#, TypeScript, SQL
- **Machine learning:** PyTorch, TensorFlow, scikit-learn, LLM evaluation, local inference with Ollama, LoRA fine-tuning
- **Languages:** English, Mandarin, Cantonese

## Honors

- Honor Student List, UC Davis
- Course Awards, UC Davis
