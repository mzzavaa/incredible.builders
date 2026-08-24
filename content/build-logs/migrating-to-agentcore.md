---
title: "Log: Moving a Crew onto a Managed Agent Runtime"
description: "What actually changed when we lifted a self-hosted agent crew onto a managed runtime, including the parts that got worse."
weight: 30
draft: false
slug: "migrating-to-agentcore"
entry_type: "log"
project: "agent-scaffold"
date_range: "Six week migration"
author: "linda-mhmd"
---

**Purpose.** A migration log written during the move, not after. For architects weighing a managed agent runtime against their own containers.

**Contains.**
- Why we moved: the three operational costs that pushed the decision
- What ported cleanly and what needed a rewrite
- Observability gap we hit in week two and the workaround
- Cold start and concurrency numbers before and after
- Lock-in assessment: what would it take to move back
- Rollback plan we kept ready and never used
- Open questions we still have

**Primary CTA.** Read the teardown before you plan your own migration.
**Links to.** /teardowns/multi-agent-orchestration/, /projects/agent-scaffold/, /build-logs/
