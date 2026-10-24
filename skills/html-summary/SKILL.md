---
name: html-summary
description: Create a standalone HTML summary when the user requests one.
---

# HTML summary

When running in T3 Code, delegate summary text to GPT models, in parallel when useful, and frontend design and implementation to Claude models. Prefer the newest available model in the chosen family.

Treat explicitly requested HTML files as standalone deliverables rather than content embedded in the conversation.

Add supporting information and concepts where needed to explain the subject.

Use the frontend-design skill for the frontend work when available. GPT models must not make visual design decisions. If Claude delegation is unavailable and the user has not supplied a design or approved reference, ask the user for the design.
