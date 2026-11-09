---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV as PDF]({{ base_path }}/files/Rebecca_De_Rosa_CV.pdf)

Education
======
* **MSc in Cybersecurity**, Politecnico di Torino, 2024–2026 (graduated March 2026)
  * Master's thesis carried out at the University of Southern Denmark (SDU) as an international exchange student, 2025–2026
  * Thesis: *A Hybrid Multi-Agent Architecture for Enhancing CodeQL Static Analysis with Large Language Models*
* **BSc in Computer Engineering**, Politecnico di Torino, 2020–2024

Research experience
======
* **LLM Developer, Internal Project**, University of Southern Denmark, Jul 2026 – present
  * Designed and implemented an OCR and RAG pipeline that supports university employees in a document-based process
* **Research Assistant**, University of Southern Denmark, Jan – Jun 2026
  * Co-developed, with two software companies, an AI system in which LLM agents find, explain and fix security vulnerabilities in source code

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
* Private tutor in Physics, Mathematics, Chemistry and Computer Science, Turin, 2020–2024

Skills
======
* **LLMs & agents:** LangChain, LangGraph, single- and multi-agent design, closed and open-source models (GPT, Claude, DeepSeek, Qwen), RAG architectures, prompt engineering
* **Machine learning:** PyTorch
* **Security:** static analysis (CodeQL), vulnerability detection
* **Programming:** Python, Java, C, C++, PHP (Laravel); Linux

Languages
======
* Italian (native), English (advanced, C1)
