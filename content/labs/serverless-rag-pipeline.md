---
title: "Serverless RAG Pipeline"
description: "Stand up ingestion, chunking, embedding, and retrieval as a serverless pipeline you can actually evaluate."
weight: 30
draft: false
slug: "serverless-rag-pipeline"
level: "intermediate"
duration_min: 180
cloud: "AWS"
est_cost_eur: 8
prerequisites: ["AWS account", "Python 3.11", "Terraform 1.6", "A sample document set"]
repo: "https://github.com/example/agent-scaffold"
---

**Purpose.** Lab for teams whose first retrieval prototype worked in a notebook and fell apart in production. Ends with a measurable pipeline.

**Contains.**
- Ingest: S3 event to queue to worker, with poison message handling
- Chunking strategies compared on the same corpus, with the numbers
- Embedding and index write, including reindex without downtime
- Retrieval endpoint with a filter layer and a hard latency budget
- Evaluation set: build twenty questions, score recall, record the baseline
- Cost breakdown per thousand documents
- Destroy step and index cleanup

**Primary CTA.** Record your baseline score and post it in the build log thread.
**Links to.** /teardowns/retrieval-layer/, /build-logs/, /stack/reference-architectures/
