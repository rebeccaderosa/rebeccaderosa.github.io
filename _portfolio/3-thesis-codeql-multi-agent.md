---
title: "Master's thesis: a multi-agent LLM system to improve CodeQL"
excerpt: "Three LLM agents that check the results of the static analysis tool CodeQL, find gaps in its rules and draft new ones. Politecnico di Torino and University of Southern Denmark, 2026."
collection: portfolio
---

**Master's thesis, Politecnico di Torino, carried out at the University of Southern Denmark (SDU). Completed March 2026.**
**Supervisors:** Prof. Adam Alami (SDU), Prof. Danilo Giordano and Prof. Matteo Boffa (Politecnico di Torino).

Static analysis tools such as CodeQL find vulnerabilities with hand-written rules, which are reliable but miss many issues and are slow to update. Instead of replacing them with an LLM, my thesis uses LLM agents to *augment* CodeQL:

* The **Analyzer** agent reasons about the source code to check CodeQL's results.
* The **Suggestor** agent studies what CodeQL missed and proposes which parts of its rules need improving.
* The **Creator** agent drafts new CodeQL rules based on those proposals.

On real-world Python files from the CVEfixes dataset, the Analyzer detected the correct vulnerability in far more files than CodeQL alone. I compared two models (GPT-5.2 and GPT-4o-mini) under identical settings and evaluated the generated proposals and rules with an LLM-as-a-judge protocol. The drafted rules are a useful starting point but still need expert review, which keeps a person in the loop.

**Tools:** Python, LangChain, LangGraph, CodeQL, OpenAI models
