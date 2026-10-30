TRADER SOTOY R8 — NEXT GEN

Next Generation Lean Architecture — n8n Orchestrated Python Stock Analysis Engine

1. Project Overview

TRADER SOTOY R8 Next Gen is a clean rebuild of the R8 stock analysis system, designed with a lean, modular, and reliable architecture.

The system combines Python-based financial analysis, n8n workflow orchestration, and PostgreSQL as its authoritative data store.

The primary objective is to build a reliable analytical engine without unnecessary architectural complexity.

2. Architecture

R8 uses three core components:

n8n — Workflow Orchestrator

- Workflow scheduling and execution
- Job orchestration
- Workflow-level retry handling
- Monitoring and notifications
- Operational automation

R8 Python — Domain Engine

- Market data acquisition
- Data normalization and validation
- Technical analysis
- Market Intelligence
- Core Score, setup, decision, and risk/reward calculations
- Canonical data management

PostgreSQL — Authoritative Data Store

- Canonical market observations
- Technical analysis results
- Market Intelligence data
- Scoring and decision records
- Job states and audit events

3. Core Architecture Principles

- Single Backbone
- Single Canonical Writer
- Single Source of Truth
- Idempotent Operations
- Fail-Closed Validation
- Deterministic Analysis
- Traceable Operations
- Recoverable Workflows
- Separation of Concerns
- Transactional Data Integrity

4. Technology Stack

Component| Technology
Domain Engine| Python
Orchestration| n8n
Database| PostgreSQL
Deployment| Docker Compose
API| Python-based REST API
Runtime| VPS / Linux

5. Development Philosophy

R8 Next Gen is a clean rebuild.

The legacy R8 system serves as a behavioral and analytical reference, not as an architecture that must be copied.

Verified analytical formulas and business rules will be preserved through independent implementation and regression testing.

Initial development focuses on the canonical backbone. Replay and backtesting are outside the initial core scope.

6. Development Roadmap

- [ ] Foundation and architecture documentation
- [ ] PostgreSQL schema design
- [ ] R8 Core Engine
- [ ] Market Data Backbone
- [ ] R8 API
- [ ] n8n Integration
- [ ] Reliability and Regression Testing
- [ ] Deployment and Release Validation

7. Project Status

Current Phase: Foundation Preparation

Architecture Decision: ADR-R8-001 — Accepted

Architecture Version: R8 Lean Architecture V1.0

This project is under active development. Components are not considered production-ready until they pass their respective validation and release gates.

---

TRADER SOTOY R8 — Built Lean. Built Reliable.