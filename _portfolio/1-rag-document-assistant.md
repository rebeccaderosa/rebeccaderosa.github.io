---
title: "RAG system for document-based work"
excerpt: "An OCR and retrieval-augmented generation pipeline that helps university employees find and use information in scanned documents. University of Southern Denmark, 2026 to present."
collection: portfolio
---

**University of Southern Denmark (SDU), Jul 2026 to present. Role: main developer of the LLM components.**

I designed the workflow and implemented a retrieval-augmented generation (RAG) pipeline that supports university employees in a document-based process.

Scanned documents are first processed with OCR (PaddleOCR) and converted into structured JSON files. The extracted content is split into chunks, using a chunking method adapted to the type of text (tables or paragraphs), and the chunks are turned into semantic embeddings stored in a vector database. Each user query is embedded and matched against the database, and an LLM generates the final answer from the retrieved content.

I also built an interface where users can review the answers and see the source passages highlighted in the original scanned document, so every answer can be checked against its source.

**Tools:** Python, PaddleOCR, embeddings and vector database, LLMs
