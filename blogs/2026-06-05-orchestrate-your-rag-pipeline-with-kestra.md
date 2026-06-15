---
title: "Orchestrate your RAG Pipeline with Kestra"
url: "https://kestra.io/blogs/orchestrate-rag-pipeline-kestra/"
date: "2026-06-05"
author: "Will Russell"
feed_url: "https://kestra.io/rss.xml"
---
This tutorial demonstrates building a complete retrieval-augmented generation (RAG) workflow using Kestra's declarative YAML format, covering the full pipeline from document ingestion and chunking through embedding generation to vector storage and grounded query responses. The approach splits RAG into two distinct workflows: an indexing pipeline and a retrieval pipeline, with production readiness requiring scheduling, retry logic, and comprehensive logging. The guide scales from using Kestra's built-in key-value store as the vector store for learning scenarios up to dedicated vector databases like Qdrant or PGVector for larger deployments.
