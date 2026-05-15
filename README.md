# promt-engineering-notes
# 🧠 Prompt Engineering: Unlock Your LLM's Full Potential

> A structured reference for developers, marketers, and power users — distilled from prompt engineering best practices.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-orange.svg)

---

## 📖 Table of Contents

- [What Is Prompt Engineering?](#what-is-prompt-engineering)
- [How LLMs Think](#how-llms-think)
- [Core Techniques](#core-techniques)
  - [Be Specific](#1-be-specific--set-the-scene)
  - [Few-Shot Prompting](#2-few-shot-prompting)
  - [Chain-of-Thought (CoT)](#3-chain-of-thought-cot)
  - [Structured Output](#4-structured-output)
  - [Constraints & Negative Instructions](#5-constraints--negative-instructions)
  - [Iterative Refinement](#6-iterative-refinement)
  - [Interview-Style Prompting](#7-interview-style-prompting)
- [Advanced Strategies](#advanced-strategies)
- [Common Mistakes](#common-mistakes)
- [Real-World Examples](#real-world-examples)
- [Resources](#resources)

---

## What Is Prompt Engineering?

Programming in **natural language** — you define the task, role, format, and constraints instead of writing code.

> ⚡ *"Most people are leaving 80% of an LLM's capability on the table."*

| Who Benefits | How |
|---|---|
| 👩‍💻 Developers | Code generation, debugging, refactors |
| 📣 Marketers | Copy, ads, emails, social |
| 🔬 Researchers | Summarization, brainstorming |
| 🙋 Everyday Users | Writing, planning, learning |

---

## How LLMs Think

- Models predict the **next token** based on everything in the current context.
- **No memory** between sessions — include all relevant info in your prompt.
- More context + clearer structure → more consistent, relevant output.

### Commanding vs. Steering

```text
