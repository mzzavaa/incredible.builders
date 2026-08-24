---
title: "Log: Cutting Agent Run Cost by Two Thirds"
description: "Four weeks of tuning model routing, tool calls, and context size on a production multi-agent workload."
weight: 20
draft: false
slug: "agent-cost-tuning"
entry_type: "log"
project: "agent-scaffold"
date_range: "Four week sprint"
author: "linda-mhmd"
---

**Purpose.** A worked example of cost tuning on a live agent system. For teams whose agent works but whose invoice does not.

**Contains.**
- Starting baseline: cost per run, token split by agent, latency percentiles
- Change one: routing cheap steps to a smaller model, with the quality delta
- Change two: trimming context, and the retrieval regression it caused
- Change three: caching tool results, and the staleness bug that followed
- The change that did not work and why we reverted it
- Final numbers table against the baseline
- What we would do first next time

**Primary CTA.** Compare your own baseline against the table and post your numbers.
**Links to.** /projects/agent-scaffold/, /teardowns/multi-agent-orchestration/, /stack/environments-and-cost/
