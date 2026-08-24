---
title: "Teardown: The Retrieval Layer"
description: "Chunking, indexing, filtering, and ranking pulled apart, with the evaluation numbers that justified each choice."
weight: 30
draft: false
slug: "retrieval-layer"
system_type: "Retrieval"
cloud: "Portable"
scale_band: "Low millions of chunks"
components: ["Ingest", "Chunker", "Index", "Filter", "Ranker", "Evaluator"]
---

**Purpose.** Teardown of a retrieval layer that survived contact with messy enterprise documents. For teams whose demo scored well and whose pilot did not.

**Contains.**
- Corpus reality check: what the documents actually looked like
- Chunking comparison with recall numbers per strategy
- Index choice and the operational cost of each option
- Metadata filtering: the part that fixed more than the embedding model did
- Reranking: measured gain against added latency and spend
- Evaluation harness: how the question set was built and kept honest
- Failure modes we still have not solved

**Primary CTA.** Build the evaluation set before you tune anything else.
**Links to.** /labs/serverless-rag-pipeline/, /teardowns/, /stack/toolchain/
