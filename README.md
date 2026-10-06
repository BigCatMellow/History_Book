# History Book

A readable American history project focused on **how the United States became the country it is now**, not only what happened when.

The book is designed to:

- explain events in their historical context;
- distinguish fact, interpretation, assumption, dispute, and unknowns;
- trace important historical developments into modern institutions, political coalitions, laws, culture, and conflicts;
- avoid both patriotic mythology and reflexive anti-American counter-mythology;
- teach readers how to evaluate historical claims rather than merely memorize conclusions.

## Start here

- [Book Build System](docs/BOOK_BUILD_SYSTEM.md) — canonical method for researching, reasoning about, writing, teaching, reviewing, and completing each section.
- [Section Build Contract](templates/SECTION_BUILD_CONTRACT.md) — compact reusable template for a fresh researcher/writer.
- [Method Sources](docs/METHOD_SOURCES.md) — exact upstream MAPS_L, Rung, THINK, PLAN, philosophy, and Design Bible sources used by this project.
- [AGENTS.md](AGENTS.md) — repository-wide operating contract for agents working on this project.


## Book manuscript

- [Book index](book/README.md)
- [How America's Political Parties Changed](book/entries/how-americas-political-parties-changed.md) — first reader-facing entry; current status: `PUBLICATION DRAFT — READY_FOR_REVIEW`.
- [Party Realignment Source Package](research/party-realignment/SOURCE_PACKAGE.md)
- [Independent Review Request](research/party-realignment/REVIEW_REQUEST.md)

## Interactive textbook prototype

- [Party Realignment HTML](site/party-realignment.html) — mobile-first interactive textbook treatment of the first manuscript entry.
- [Interactive Design Brief](site/DESIGN.md) — exact Design Bible decisions, modal rules, mobile behavior, accessibility target, and anti-pattern checks.

The HTML is self-contained: CSS and JavaScript are embedded so it can be opened locally without a build step.

## Worked examples

### Party change and ideological realignment

First full test of the build system:

- [Build Record](examples/party-realignment/BUILD_RECORD.md) — THINK, PLAN, evidence states, claim-evidence matrix, causation checks, and review risk.
- [Reader-Facing Draft](examples/party-realignment/SECTION_DRAFT.md) — the actual section produced from that process.
- [Author Check](examples/party-realignment/AUTHOR_CHECK.md) — acceptance check and limitations before independent review.

This example remains `READY_FOR_REVIEW`, not `DONE`, because its required fresh independent review has not yet occurred.

## System in one view

```text
HISTORICAL QUESTION
        ↓
THINK
frame / decompose / expose assumptions / alternatives
        ↓
PLAN
determine what evidence can resolve the important questions
        ↓
MAPS_L
research / claims↔evidence / verification / independent review
        ↓
SYNTHESIS + WRITING
        ↓
RUNG
teach the mental model and test transfer
        ↓
DESIGN BIBLE
make the information readable, navigable, and memorable
        ↓
READER
```

## Core project maxim

```text
MAKE IT SIMPLE ENOUGH TO UNDERSTAND

MAKE IT ACCURATE ENOUGH TO TRUST

MAKE IT DEEP ENOUGH TO EXPLAIN THE PRESENT

TEACH THE READER HOW TO TEST THE STORY THEMSELVES
```

## Primary upstream methods

This project adapts mechanisms from the following exact sources. These remain upstream references; this repository owns the history-book-specific application.

### MAPS_L

- [Project Bootstrap](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/PROJECT_BOOTSTRAP.md)
- [Operator Request Compilation](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/REQUEST_COMPILATION.md)
- [Agent-Grade Instructions Standard](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/AGI_STANDARD.md)
- [Research Before Architecture](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md)
- [Checks and Balances](https://github.com/BigCatMellow/MAPS_Lean/blob/main/docs/CHECKS_AND_BALANCES.md)
- [Tenth Seat Review](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/TENTH_SEAT_REVIEW.md)

### Rung Teaching

- [Teaching Loop](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Teaching-Loop.md)
- [Assistance Ladder](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Assistance-Ladder.md)
- [Diagnosing Mistakes](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Diagnosing-Mistakes.md)
- [Mastery and Transfer](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Mastery-and-Transfer.md)
- [Research Foundations](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Research-Foundations.md)

### THINK

- [THINK Project](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/THINK_PROJECT.md)
- [THINK Evidence-Driven Improvement Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/03-THINK-CREATIVITY-AND-IDEA-ECOLOGY.md)
- [THINK Roadmap Map](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/think/README.md)

### PLAN

- [AI Planning and Orchestration Research](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-planning-and-orchestration/README.md)
- [PLAN Orchestration and Task Compilation Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/05-PLAN-ORCHESTRATION-AND-TASK-COMPILATION.md)
- [PLAN Roadmap Map](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/plan/README.md)

### Philosophy / epistemology

- [Philosophy Research Index](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/philosophy/README.md)
- [Philosophical Roadmap for Thinking and Creativity](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/PHILOSOPHICAL_ROADMAP.md)

### AI Design Bible

- [AI Design Bible](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/README.md)
- [Foundations](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/FOUNDATIONS.md)
- [Interaction and Information Design](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/INTERACTION-AND-INFORMATION.md)
- [Visual Systems](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/VISUAL-SYSTEMS.md)
- [Evaluation](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/EVALUATION.md)
- [Anti-Patterns](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/ANTI-PATTERNS.md)
