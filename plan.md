# Mentored Team Project Guide  
**Using GitHub Projects for Real-World Software Development**


## Purpose of This Project

This guide defines a **mentored, real-world project framework** designed to complement a coding bootcamp curriculum by teaching **how software is actually built in teams**.

The focus is not just writing code, but learning:
- How requirements are discovered and clarified
- How work is planned and delivered iteratively
- How developers collaborate using GitHub
- How to communicate progress, trade-offs, and outcomes

This mirrors how small, effective engineering teams operate in startups and internal product groups.


## High-Level Goals

By the end of this project, mentees should be able to:

1. Translate a vague idea into clear, testable requirements
2. Break work into user stories with acceptance criteria
3. Deliver features in small, reviewable increments
4. Collaborate through GitHub Issues, Projects, and Pull Requests
5. Explain technical decisions to non-technical stakeholders
6. Ship a working product under constraints


## Roles & Responsibilities

### Mentor (Product Owner / Reviewer)
- Acts as a non-technical stakeholder
- Clarifies goals, not implementation
- Reviews pull requests and demos
- Provides feedback on process and communication

### Mentee(s) (Developer)
- Owns implementation decisions
- Asks clarifying questions
- Plans and delivers work via GitHub Projects
- Demonstrates completed features


## Tooling

**Primary Tools**
- GitHub Repository
- GitHub Issues
- GitHub Projects (Board View)
- Pull Requests

**Optional**
- Markdown files for documentation
- Local dev environment
- Simple deployment platform (optional)


## Project Structure

### Repository
/
├── README.md
├── docs/
│ ├── problem-statement.md
│ ├── decisions.md
│ └── retrospectives.md
└── src/


### GitHub Project Board Columns
- Backlog
- Sprint Backlog
- In Progress
- In Review
- Done


## Phase 0 — Project Framing

**Goal:** Establish shared understanding before writing code.

### Activities
- Define the problem being solved
- Identify the target user
- Define success criteria
- Explicitly list non-goals

### Deliverables
- `docs/problem-statement.md`

### Outcomes
- Mentee learns that requirements are discovered, not handed down
- Scope is intentionally limited


## Phase 1 — Requirements & Backlog Creation

**Goal:** Convert ideas into actionable work items.

### Activities
- Write user stories (not technical tasks)
- Add acceptance criteria to each story
- Prioritize stories (Must / Should / Could)

### Deliverables
- 6–10 GitHub Issues labeled as `feature`
- Each issue includes acceptance criteria

### Outcomes
- Mentee learns to think in user behavior, not implementation
- Clear definition of “done”


## Phase 2 — Sprint Planning

**Goal:** Teach focus and realistic planning.

### Activities
- Select 2–3 issues for the sprint
- Move them to “Sprint Backlog”
- Define sprint duration (3–7 days)

### Definition of Done
- Code merged to `main`
- Feature meets acceptance criteria
- Basic documentation updated

### Outcomes
- Mentee experiences constrained delivery
- Learns to commit to achievable scope


## Phase 3 — Sprint Execution

**Goal:** Simulate real development flow.

### Rules
- All work happens in branches
- Every change goes through a Pull Request
- Small, frequent commits

### Pull Request Requirements
- Clear description of changes
- Linked issue (`Fixes #123`)
- Instructions to test

### Outcomes
- Mentee learns professional Git workflows
- Emphasis on clarity and reviewability


## Phase 4 — Review & Demo

**Goal:** Reinforce feedback loops.

### Demo
- Mentee demonstrates functionality to mentor
- Focus on user experience, not code internals

### Review Questions
- Does this solve the stated problem?
- What assumptions were made?
- What would break first?

### Outcomes
- Mentee practices explaining work clearly
- Learns to accept and integrate feedback


## Phase 5 — Retrospective

**Goal:** Build reflective habits.

### Retrospective Topics
- What went well
- What was unclear
- What slowed progress
- What to improve next sprint

### Deliverables
- Notes in `docs/retrospectives.md` or a GitHub Issue

### Outcomes
- Mentee develops self-improvement mindset
- Process awareness increases


## Optional Real-World Enhancements

Use sparingly:
- Introduce a late requirement change
- Add a performance or usability constraint
- Log and triage a bug
- Require a README for non-technical users


## Success Criteria

A project is considered successful if:
- A working application is delivered
- The mentee can explain the **why**, not just the **how**
- GitHub history shows clear collaboration and iteration
- The mentee can discuss this project confidently in interviews


## What This Project Teaches (That Bootcamps Often Miss)

- Requirement clarification
- Scope control
- Agile delivery in practice
- Professional Git usage
- Stakeholder communication
- Trade-offs and prioritization


## Final Notes

This project is intentionally small but **process-rich**.  
The goal is not to impress with complexity, but to demonstrate **sound engineering habits** that scale.

When done well, this becomes:
- A portfolio case study
- A real interview talking point
- A foundation for future team work

