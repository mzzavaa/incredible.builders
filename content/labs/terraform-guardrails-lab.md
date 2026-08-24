---
title: "Guardrails Before Experiments"
description: "Apply budget alarms, spend meters, and a kill switch to a sandbox account before anyone starts building."
weight: 40
draft: false
slug: "terraform-guardrails-lab"
level: "foundation"
duration_min: 45
cloud: "AWS"
est_cost_eur: 1
prerequisites: ["AWS sandbox account", "Terraform 1.6", "Admin on the sandbox only"]
repo: "https://github.com/example/cost-guardrails"
---

**Purpose.** Short lab that every other lab assumes. For architects who need a defensible answer to "what stops this from costing us money".

**Contains.**
- Apply the sandbox guardrails module and read what it created
- Fire a synthetic spend event and watch the alarm path end to end
- Configure the token spend meter for a model workload
- Test the kill switch, then test the documented override
- Wire notifications into a channel people actually read
- Rollout notes for moving this from sandbox to an organisation

**Primary CTA.** Apply the module to your sandbox before the next experiment starts.
**Links to.** /projects/cost-guardrails/, /stack/environments-and-cost/, /labs/
