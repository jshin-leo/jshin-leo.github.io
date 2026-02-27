---
title: "Domain-Aware Question Answering for Alzheimer’s Care using RAG and Fine-Tuned Llama 8B"
excerpt: "Local Healthcare RAG Pipeline, June-August 2025"  
collection: portfolio
---

### Domain-Aware Question Answering for Alzheimer’s Care using RAG and Fine-Tuned Llama 8B  

**Lab:** Security and Intelligence Lab, UTEP  
**Supervisor:** Dr. Aritran Piplai  
**Project Period:** June-August 2025  

**Overview**  
This project implements a local Retrieval-Augmented Generation (RAG) pipeline tailored for healthcare content, with a focus on Alzheimer’s disease, related dementias, and caregiving.  

The system extracts transcripts from YouTube videos and web articles, filters potentially sensitive medical statements, chunks the content, builds a FAISS vector store, and enables domain-aware question answering using a fine-tuned Llama 8B model.  

**Official Lab Repository:**  
<a href="https://github.com/LeonG19/llm-healthcare" target="_blank" rel="noopener noreferrer">https://github.com/LeonG19/llm-healthcare</a>  

**My Implementation Repository:**  
<a href="https://github.com/jshin-leo/LLM_Healthcare_RAG" target="_blank" rel="noopener noreferrer">https://github.com/jshin-leo/LLM_Healthcare_RAG</a>  

**My Contribution**  
My GitHub repository serves as an independent implementation to deepen understanding of Retrieval-Augmented Generation pipelines. I developed most system components as a standalone project, including full pipeline orchestration and local deployment.  
<img src="/images/LLM for Healthcare.png" alt="LLM for Healthcare RAG Pipeline" style="width:100%; max-width:800px; margin:20px 0;" />  
Web crawling for data collection was completed by Arman, and Q&A dataset collection was contributed by Emilia.  

**Key Contributions**  
- Implemented YouTube crawling and transcript extraction pipeline.  
- Integrated Whisper-based audio transcription for healthcare content processing.  
- Designed diagnosis and prescription filtering to reduce sensitive medical outputs.  
- Developed sentence-level semantic chunking with similarity-based filtering.  
- Built a FAISS-based vector index for efficient semantic retrieval.  
- Integrated local RAG querying using a fine-tuned Llama 8B model.  
- Orchestrated end-to-end system integration for domain-aware healthcare question answering.  

**Technical Stack**  
Python, FAISS, Llama 8B, Hugging Face, Sentence Transformers, Local LLM Inference  
