---
layout: page
title: MedAgent-Verify
description: Trustworthy agentic AI for medical question answering
img:
importance: 1
category: research
---

A multi-step medical question-answering agent built around an explicit **verification layer** that detects hallucinated claims and triggers **safe abstention** rather than answering confidently when evidence is insufficient.

The project explores a central question in agentic AI: how do we make a language-model agent reliable enough for high-stakes domains? Instead of trusting a single generation pass, each intermediate reasoning step is checked against retrieved evidence, and the agent is allowed to say "I don't know."

**Stack:** Python, LLM APIs, retrieval-augmented verification

[View on GitHub](https://github.com/Rashiin/medagent-verify)
