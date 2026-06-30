# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

This repository contains course material for **"Beginners' Intro to AI Engineering"** — a 4-week live course targeting learners aged 13 and up. Each week has a 1.5-hour live session (8:00–9:30 PM). It includes the course itinerary and all code examples used in teaching.

## Course Structure

### Module 1 — Python & Software Engineering Basics
Foundational Python concepts introduced to complete beginners.

### Module 2 — AI Engineering Concepts
Covers prompt engineering, RAG (Retrieval-Augmented Generation), and tool use via the Anthropic cloud API.

### Module 3 — Claude Code
Focuses on the VS Code plugin as the primary interface. Topics:
- The `CLAUDE.md` init file
- The explore → plan → execute → test workflow
- Skills and agents
- Context management

## Repository Layout (Planned)

```
itinerary/          # Weekly session plans and learning objectives
examples/
  module1/          # Python fundamentals code examples
  module2/          # Prompt engineering, RAG, tool use examples
  module3/          # Claude Code demos and walkthroughs
```

## Development Notes

- Code examples should be written in Python
- Module 2 examples use the Anthropic API — a `.env` file with `ANTHROPIC_API_KEY` is expected locally and must never be committed.
- Module 3 examples are meant to be run inside VS Code with the Claude Code extension active.
