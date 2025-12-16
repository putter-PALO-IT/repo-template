<!-- filepath: /Users/thamwattanavekin/Desktop/gen-e2-training-example/ai-rules/conception-phase.md -->

# Conception Phase (AI-Assisted)

## Purpose
Define how AI will assist during the **conception phase** and what **conception outputs** should be produced.

This document acts as the shared contract for:
- What information the requester must provide
- What the AI will generate and how
- What “done” looks like for conception

## When to use this phase
Use the conception phase when you:
- Have an idea but need to clarify scope, users, and success criteria
- Want to explore solution options and trade-offs before implementation
- Need a minimal, testable plan that can be handed to design/engineering

## AI role (what the AI does)
The AI acts as a *product + engineering copilot* to:
- Ask targeted questions to remove ambiguity
- Extract requirements, constraints, and assumptions
- Propose solution approaches and evaluate trade-offs
- Produce a structured conception output (see below)
- Identify risks, unknowns, and validation steps

## User role (what you provide)
Provide as much as possible, even if incomplete:
- Problem statement / motivation
- Intended users and primary use-cases
- Constraints (time, tech stack, budget, policy, privacy)
- Non-goals (what is explicitly out of scope)
- Any existing context (docs, links, current system behavior)

If you cannot provide these, the AI will prompt with questions.

## Process (workflow)
1. **Intake & clarification**
   - AI asks questions until scope and goals are coherent.
   - AI logs assumptions when answers are unavailable.

2. **Synthesis**
   - AI turns the conversation into structured requirements.
   - AI identifies implied requirements and edge cases.

3. **Optioning & recommendation**
   - AI proposes 1–3 approaches with trade-offs.
   - AI recommends one approach aligned to constraints.

4. **Conception output generation**
   - AI produces the conception output sections below.

5. **Review & iteration**
   - User confirms, edits, or rejects sections.
   - AI updates outputs accordingly.

## Conception Output (deliverables)
The AI should produce a single coherent “conception pack” containing:

### 1) One-sentence summary
- A crisp statement of what is being built and for whom.

### 2) Problem statement
- What pain exists today and why it matters.

### 3) Goals & non-goals
- **Goals**: measurable outcomes.
- **Non-goals**: explicitly excluded scope.

### 4) Users & use-cases
- Primary user personas (1–3)
- Top workflows / jobs-to-be-done

### 5) Requirements
Split into:
- **Functional requirements** (what the system must do)
- **Non-functional requirements** (performance, reliability, security, privacy, accessibility)

### 6) Assumptions & constraints
- Assumptions made due to missing info
- Constraints from business/tech/policy

### 7) Proposed solution (high level)
- System overview (components and responsibilities)
- Data flow (inputs → processing → outputs)
- Integrations (if any)

### 8) Alternatives considered
For each alternative:
- Pros
- Cons
- Why rejected (or why still viable)

### 9) Risks & mitigations
- Technical risks
- Product risks
- Delivery risks
- Mitigation plan + what must be validated early

### 10) Success metrics
- KPIs and how they will be measured

### 11) Open questions
- Items that block finalization
- Next questions to answer

### 12) Milestones (optional)
- Thin-slice v0
- v1
- Future enhancements

## Output format requirements
- Use clear headings and bullet lists.
- Prefer specific acceptance criteria over vague statements.
- Mark uncertain items explicitly as **Assumption**.
- Keep the scope minimal and testable.

## Prompting rubric (questions the AI should ask)
AI should ask only what is necessary, in this order:
1. **Who is the user and what is the top workflow?**
2. **What does success look like (metrics or concrete outcomes)?**
3. **What must NOT be built (non-goals)?**
4. **Constraints**: stack, timeline, budget, compliance, data sensitivity.
5. **Key edge cases** and failure modes.

## Conception Phase template (copy/paste)
> Fill this out with the AI during a session.

### Summary
-

### Problem
-

### Goals
-

### Non-goals
-

### Users & Use-cases
-

### Requirements
**Functional**
-

**Non-functional**
-

### Assumptions & Constraints
-

### Proposed Solution (High Level)
-

### Alternatives Considered
-

### Risks & Mitigations
-

### Success Metrics
-

### Open Questions
-

### Milestones (optional)
-
