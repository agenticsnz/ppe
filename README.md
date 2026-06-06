# Deterministic Porting & Agentic Engineering: Artifact Repository

## Overview
This repository contains a collection of presentations, infographics, and mind maps explaining Blair Nilsson's "Provable Porting Engine" developed to migrate legacy SAS databases and Excel spreadsheets at scale. The materials contrast "Agentic Engineering" with "vibe coding," illustrating how deterministic orchestration, strict LLM bounding, and mathematical testing can turn a multi-year migration project into a provably accurate, overnight automated run.

## Repository Contents

### 📊 Presentations (Slide Decks)
*   **The Comprehensive Explainer:** Covers the "Why, How, and What" of legacy software challenges, detailing how large codebases are sliced, verified, and reassembled.
*   **The Technical Deep Dive:** Focuses heavily on the system architecture, including anti-hallucination loops, dual-model verification, abstract syntax trees, and evolutionary fuzzing.
*   **The Executive / Business Pitch:** Highlights the organizational impact, contrasting traditional "Big Four" 10-year consulting quotes with agentic engine runs that cost a few dollars in AI tokens. 

### 🖼️ Visual Guides (Infographics & Mind Maps)
*   **The Anti-Hallucination Loop:** A structural breakdown of the forward pass (asking what the code does) and the backward pass (asking if the code matches the description) to trap AI hallucinations.
*   **The Context Evaporation Funnel:** Explains why simply dumping 200k zipped XML files into an LLM fails, and why code must be deterministically sliced into sub-100-line fragments.
*   **Dependency Graph Transformation:** Demonstrates how messy Excel R1C1 formulas are deterministically parsed into clean Mermaid node charts, which serve as the actual prompts for the AI.
*   **Traditional vs. Agentic Porting:** A visual comparison of manual human porting versus the cost, speed, and accuracy of AI agent porting.
*   **The Shifting Critical Path Timeline:** Illustrates how the core bottleneck has shifted away from writing the code itself, and toward downstream systems, environment setups, and organizational approvals.
