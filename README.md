# Vigilstate

Vigilstate is an AI-powered Project Operations Assistant designed to help project managers delegate up to 80% of routine coordination work.

Built from scratch in 3 months using AI-assisted development workflows (Claude Code), the system integrates structured PM logic with modern LLM capabilities to surface risks early and accelerate decisions.

Live product: https://www.vigilstate.com/

---

## 🎯 Problem

Project managers spend excessive time on:
- Status tracking
- Risk monitoring
- Stakeholder communication
- Documentation & coordination

This reduces strategic focus and increases operational friction.

---

## 🚀 Solution

Vigilstate adds an AI operations layer that:

- Analyzes structured project data
- Detects risks early
- Suggests mitigation strategies
- Structures stakeholder communication
- Reduces routine workload

---
## 🏗 Architecture Overview

            ┌──────────────────────────────┐
            │          End User            │
            │  (Project Manager / Team)    │
            └──────────────┬───────────────┘
                           │
                           ▼
            ┌──────────────────────────────┐
            │      Frontend (React)        │
            │  UI • Forms • Dashboards     │
            └──────────────┬───────────────┘
                           │
                           ▼
            ┌──────────────────────────────┐
            │       API Layer (Node)       │
            │  Routing • Auth • Validation │
            └──────────────┬───────────────┘
                           │
                           ▼
            ┌──────────────────────────────┐
            │        AI Engine Layer       │
            │   LLM Integration (Claude)   │
            │  Prompt Logic • Context Mgmt │
            └──────────────┬───────────────┘
                           │
                           ▼
            ┌──────────────────────────────┐
            │     Process Logic Engine     │
            │  PMBOK-based Process Model   │
            │  Risk Analysis • Automation  │
            └──────────────┬───────────────┘
                           │
                           ▼
            ┌──────────────────────────────┐
            │        Data Layer (DB)       │
            │  Projects • Tasks • Risks    │
            └──────────────────────────────┘
The system is structured as a layered architecture separating UI, API, AI reasoning, and process logic to ensure scalability, maintainability, and responsible AI integration.


Layered architecture separates UI, API, AI reasoning, and business logic to ensure maintainability and responsible AI integration.

---

## 🤖 Example AI Workflow (Risk Detection)

1. User submits project update (budget, schedule, resources).
2. API validates & structures context.
3. AI Engine receives:
   - Project state
   - Historical data
   - Risk categories
4. LLM generates:
   - Identified risks
   - Impact estimation
   - Suggested actions
5. Process logic validates output before surfacing to user.

Result: Faster risk visibility and decision support.

---

## 🛠 AI-Assisted Development

- Built using Claude Code for structured scaffolding & refactoring
- Human-in-the-loop validation
- Secure prompt design
- System decomposition before code generation
- Iterative architecture refinement

Core production codebase remains private.


