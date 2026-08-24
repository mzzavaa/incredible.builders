---
title: "Your First Agent in an Hour"
description: "Build, trace, and cost-cap a working single-agent system on Bedrock in about sixty minutes."
weight: 10
draft: false
slug: "first-agent-in-an-hour"
level: "foundation"
duration_min: 60
cloud: "AWS"
est_cost_eur: 2
prerequisites: ["AWS account with Bedrock access", "Python 3.11", "AWS CLI v2"]
repo: "https://github.com/example/agent-scaffold"
---

**Purpose.** Entry lab for engineers who have read about agents but never shipped one. Ends with a traced, budget-capped agent running in their own account.

**Contains.**
- Step zero: enable model access and set a hard budget alarm before writing code
- Step one: run the scaffold sample and read the trace
- Step two: replace the sample tool with a real API call
- Step three: add one eval case and make it fail, then make it pass
- Step four: destroy everything and confirm the bill is closed
- Troubleshooting table for the five errors people actually hit
- Checkpoint files so a stuck reader can jump forward

**Primary CTA.** Complete the lab, then submit the result to the showcase.
**Links to.** /projects/agent-scaffold/, /showcase/submit/, /labs/
