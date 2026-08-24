---
title: "Cost Guardrails"
description: "Terraform modules and alarms that stop an AI workload from quietly turning into a five figure invoice."
weight: 30
draft: false
slug: "cost-guardrails"
status: "stable"
status_label: "Stable, low change rate"
category: "Cloud operations"
language: "HCL"
license: "Apache-2.0"
repo: "https://github.com/example/cost-guardrails"
tech: ["Terraform", "AWS Budgets", "CloudWatch", "EventBridge", "Lambda"]
maintainers: ["linda-mhmd"]
---

**Purpose.** Project page for the cost guardrails modules. For solution architects who need budget enforcement in an account before the team starts experimenting.

**Contains.**
- Module list: budget alarms, token spend meter, idle resource sweeper, kill switch
- Quickstart: apply to a sandbox account, trigger a test alarm
- Threshold guidance table by workload type, with defaults we use ourselves
- What happens when a cap is hit, including the manual override path
- Multi-account rollout notes for organisations
- Caveats: what these modules cannot see and where you still need FinOps review

**Primary CTA.** Apply the sandbox module to a test account this week.
**Links to.** /labs/terraform-guardrails-lab/, /stack/environments-and-cost/, /teardowns/multi-agent-orchestration/
