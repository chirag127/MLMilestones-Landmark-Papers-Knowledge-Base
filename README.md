# MLMilestones-Landmark-Papers-Knowledge-Base

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base/ci.yml?style=flat-square&logo=github)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base?style=flat-square&logo=codecov)
![Python Version](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Linting](https://img.shields.io/badge/Ruff-Enabled-orange?style=flat-square&logo=ruff)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgray?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base?style=flat-square&logo=github)

## ⭐ Star this Repo ⭐

An AI-curated repository detailing landmark papers that shaped Machine Learning, covering foundational concepts, algorithms, and breakthroughs in AI research.

This knowledge base serves as an essential reference for understanding the historical trajectory and core advancements in artificial intelligence.

---

## 🌳 Architecture Overview

mermaid
graph TD
    A[User/Researcher] --> B(CLI Interface);
    B --> C{Orchestration Layer};
    C --> D[Paper Data Fetching];
    C --> E[AI Curation & Analysis];
    C --> F[Knowledge Graph Generation];
    D --> G(External APIs/Sources);
    E --> H[Vector Database/Storage];
    F --> I[Structured Knowledge Base];
    H --> C;
    I --> C;


---

## 📜 Table of Contents

*   [About](#about)
*   [Features](#features)
*   [Technology Stack](#technology-stack)
*   [Architecture](#architecture)
*   [Getting Started](#getting-started)
*   [Usage](#usage)
*   [Contributing](#contributing)
*   [License](#license)
*   [AI Agent Directives](#ai-agent-directives)

---

## 💡 About

This repository houses a curated collection of seminal research papers that have fundamentally influenced the field of Machine Learning. It leverages AI to analyze, categorize, and synthesize information from these papers, creating a dynamic and searchable knowledge base.

---

## 🚀 Features

*   **AI-Curated Content:** Automatically processes and extracts key information from ML landmark papers.
*   **Knowledge Synthesis:** Generates insights into foundational concepts, algorithms, and research breakthroughs.
*   **Structured Data:** Organizes paper information into a queryable format.
*   **Historical Context:** Provides a chronological and conceptual understanding of AI evolution.
*   **Command-Line Interface (CLI):** Easy-to-use interface for accessing and querying the knowledge base.

---

## 🛠️ Technology Stack

*   **Language:** Python 3.10+
*   **Package Management:** uv
*   **Linting & Formatting:** Ruff
*   **Testing:** Pytest
*   **AI Integration:** Placeholder for specific AI model APIs (e.g., OpenAI, Google Gemini)
*   **Data Storage:** Placeholder for vector database (e.g., ChromaDB, FAISS) and structured storage (e.g., SQLite, PostgreSQL).
*   **CLI Framework:** Placeholder (e.g., Click, Typer)

---

## 🏗️ Architecture

This project follows a **Modular Monolith** architectural pattern. Key components are designed as distinct modules with clear responsibilities, facilitating maintainability and scalability while remaining within a single deployable unit.

---

## 🚀 Getting Started

### Prerequisites

*   Python 3.10+ installed
*   uv installed (`pip install uv`)

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/MLMilestones-Landmark-Papers-Knowledge-Base.git
    cd MLMilestones-Landmark-Papers-Knowledge-Base
    

2.  **Create and activate a virtual environment (recommended):**
    bash
    uv venv
    source .venv/bin/activate # On Linux/macOS
    # .venv\Scripts\activate # On Windows
    

3.  **Install dependencies:**
    bash
    uv pip install -r requirements.txt
    

---

## 🕹️ Usage

*(This section will be populated with specific CLI commands once implemented.)*

Example:
bash
# python src/main.py --help


---

## 🤝 Contributing

Contributions are welcome! Please refer to the [CONTRIBUTING.md](.github/CONTRIBUTING.md) file for detailed guidelines.

---

## 📄 License

This project is licensed under the [CC BY-NC 4.0 License](LICENSE) - see the `LICENSE` file for details.

---

## 🤖 AI Agent Directives

<details>
<summary>Click to view AI Agent Directives</summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`pyproject.toml` for Python) and apply the corresponding **Apex Toolchain**. This repository, `MLMilestones-Landmark-Papers-Knowledge-Base`, is a Python-based AI knowledge base.

*   **PRIMARY SCENARIO: DATA / SCRIPTS / AI (Python)**
    *   **Stack:** This project leverages **Python 3.10+**. Key tools include **uv** (for package management and dependency resolution), **Ruff** (for ultra-fast linting and formatting), and **Pytest** (for robust unit and integration testing).
    *   **Architecture:** Adheres to a **Modular Monolith** pattern, ensuring clear separation of concerns for features like paper data fetching, AI analysis, and knowledge base generation, while maintaining a unified deployment.
    *   **AI Integration:** Design for deep integration with AI models for analysis and summarization. Prioritize modular design, clear API contracts, and robust error handling for all AI model interactions. Placeholder for specific model APIs and vector database integrations.
    *   **CLI Framework:** Uses `Click` or similar for a powerful and intuitive command-line interface.

*   **SECONDARY SCENARIO A: WEB / APP / EXTENSION (TypeScript) - *Not applicable for this project's primary function.***
    *   **Stack:** TypeScript 6.x (Strict), Vite 7 (Rolldown), Tauri v2.x (Native), WXT (Extensions).
    *   **State:** Signals (Standardized).

---

### 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
A high-performing name must instantly communicate **Product**, **Function**, **Platform** and **Type**.

**Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
**Format:** `Title-Case-With-Hyphens` (e.g., `MLMilestones-Landmark-Papers-Knowledge-Base`).

---

### 5. VERIFICATION COMMANDS

*   **Linting & Formatting:**
    bash
    uv pip install ruff
    ruff check .
    ruff format .
    
*   **Testing:**
    bash
    uv pip install pytest
    pytest
    
*   **Package Management:**
    bash
    uv sync requirements.txt
    

---

### 6. ARCHITECTURAL PRINCIPLES
*   **SOLID:** Ensure **S**ingle Responsibility, **O**pen/Closed, **L**iskov Substitution, **I**nterface Segregation, and **D**ependency Inversion principles are applied.
*   **DRY:** Don't Repeat Yourself. Maximize code reuse.
*   **YAGNI:** You Ain't Gonna Need It. Avoid over-engineering.

</details>
