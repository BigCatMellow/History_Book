# American History Book — Build System

- Record role: `PROJECT METHOD`
- Status: `ACTIVE`
- Canonical owner for: how History Book sections are researched, reasoned about, written, taught, reviewed, and completed
- Repository contract: [../AGENTS.md](../AGENTS.md)
- Compact execution template: [../templates/SECTION_BUILD_CONTRACT.md](../templates/SECTION_BUILD_CONTRACT.md)
- Annotated upstream source map: [METHOD_SOURCES.md](METHOD_SOURCES.md)

This system applies MAPS_L-style project shaping and evidence discipline to American history writing, with Rung for teaching, THINK for framing/alternative explanations, PLAN for bounded investigation, and the Pilot AI Design Bible for information design.

The goal is not to import those projects wholesale. Use the **smallest useful mechanism** from each.

---

# 1. Parent outcome

## Goal

Create a readable history of the United States that explains:

- what happened;
- why it happened;
- what people at the time believed they were doing;
- what major competing explanations exist;
- who benefited and who bore costs;
- how later Americans remembered or reinterpreted the event;
- what institutions, political ideas, social structures, laws, conflicts, or assumptions survived into modern America.

The book should teach the reader **how to understand historical claims**, not merely which conclusions to memorize.

### Upstream method

This parent-outcome pattern is adapted from MAPS_L:
[Project Bootstrap](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/PROJECT_BOOTSTRAP.md).

---

# 2. Definition of DONE

The book is complete when:

1. the major historical arc from pre-colonial America through the modern United States is coherent;
2. major claims are traceable to evidence;
3. fact, inference, interpretation, and uncertainty are distinguishable;
4. important competing explanations are represented fairly and tested against evidence;
5. major groups affected by events are not systematically omitted;
6. present-day connections are causal and evidenced rather than rhetorical;
7. chapters work for a reader without substantial prior historical knowledge;
8. the book has received independent historical/evidence review;
9. representative readers can explain major causal relationships without relying on the book's wording;
10. no unresolved high-consequence factual failure remains.

The project is not DONE because every planned chapter exists. DONE requires **proof that the book is accurate, coherent, teachable, and reviewable**.

### Upstream methods

- [MAPS_L Project Bootstrap](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/PROJECT_BOOTSTRAP.md)
- [MAPS_L Checks and Balances](https://github.com/BigCatMellow/MAPS_Lean/blob/main/docs/CHECKS_AND_BALANCES.md)
- [Rung Mastery and Transfer](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Mastery-and-Transfer.md)

---

# 3. Governing principles

## Evidence outranks narrative

Never keep a cleaner story merely because it reads better.

If evidence complicates the narrative, change the narrative.

This follows MAPS_L's evidence-first operating rule and
[Research Before Architecture](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md).

---

## Do not guess across material uncertainty

Use these states when useful:

```text
VERIFIED
Strong evidence directly supports the claim.

REPORTED
A source/person makes the claim, but the project is not independently establishing it.

INTERPRETATION
An evidence-based explanation of established facts.

ASSUMED
Currently being treated as true for investigation but not established.

DISPUTED
Credible competing interpretations remain.

UNKNOWN
Available evidence does not justify resolution.
```

Not every sentence needs a visible label in the final book.

The research record should preserve the distinction.

This adapts the evidence-state handling in:
[MAPS_L Request Compilation](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/REQUEST_COMPILATION.md) and
[AGI Standard](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/AGI_STANDARD.md).

---

## Primary evidence first where practical

Preferred research order:

```text
primary sources
↓
high-quality institutional collections
↓
specialist historical scholarship
↓
broader scholarly synthesis
↓
popular secondary history
```

Primary sources are evidence of what people said, believed, recorded, or did.

They are **not automatically accurate descriptions of reality**.

A political speech can strongly establish what argument was publicly made. It may be weak evidence of whether every factual assertion in the speech was true or whether the public rationale was the actor's sole private motive.

Reference:
[MAPS_L Research](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md).

---

## Preserve disagreement

When serious sources disagree:

```text
DO NOT
average them into a vague compromise.

DO
identify the disagreement;
determine what evidence each interpretation relies upon;
evaluate source quality;
look for discriminating evidence;
preserve unresolved uncertainty when necessary.
```

Reference:
[MAPS_L Research](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md).

---

## No predetermined national verdict

The project does not begin with:

```text
America was uniquely good.
```

or:

```text
America was uniquely bad.
```

Historical actors and institutions should be evaluated from evidence and context rather than forced into either narrative.

Contradictory facts may coexist.

A policy may have produced prosperity and dispossession.

A political movement may have expanded liberty for one population while denying it to another.

A war may involve legitimate security interests and serious abuses.

The job is to explain the whole historical relationship.

Relevant Pilot frame/epistemology references:

- [Philosophy Research Index](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/philosophy/README.md)
- [Philosophical Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/PHILOSOPHICAL_ROADMAP.md)

---

# 4. Book-level production loop

Use this operating pattern:

```text
INSPECT REALITY
↓
DEFINE THE HISTORICAL QUESTION
↓
THINK
frame / decompose / expose assumptions / alternatives
↓
PLAN
determine what evidence would resolve the important questions
↓
RESEARCH
claim ↔ source ↔ evidence
↓
SYNTHESIZE
construct the best-supported explanation
↓
CHALLENGE
look for missing evidence and credible alternative explanations
↓
WRITE
reader-facing narrative
↓
RUNG PASS
does this teach the mental model?
↓
DESIGN PASS
does information hierarchy support understanding?
↓
INDEPENDENT REVIEW
↓
CORRECT / RESEARCH / REFRAME IF NEEDED
↓
SECTION DONE
```

Complexity is proportional.

A straightforward factual passage does not need a research bureaucracy.

A consequential disputed historical claim does.

### Exact upstream owners

**Project shaping / evidence / review**

- [MAPS_L Project Bootstrap](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/PROJECT_BOOTSTRAP.md)
- [MAPS_L Request Compilation](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/REQUEST_COMPILATION.md)
- [MAPS_L AGI Standard](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/AGI_STANDARD.md)
- [MAPS_L Research](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md)
- [MAPS_L Checks and Balances](https://github.com/BigCatMellow/MAPS_Lean/blob/main/docs/CHECKS_AND_BALANCES.md)

**Historical framing**

- [THINK Project](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/THINK_PROJECT.md)
- [THINK Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/03-THINK-CREATIVITY-AND-IDEA-ECOLOGY.md)

**Investigation planning**

- [PLAN Research](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-planning-and-orchestration/README.md)
- [PLAN Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/05-PLAN-ORCHESTRATION-AND-TASK-COMPILATION.md)

**Teaching**

- [Rung Teaching Loop](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Teaching-Loop.md)
- [Rung Assistance Ladder](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Assistance-Ladder.md)
- [Rung Mastery and Transfer](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Mastery-and-Transfer.md)

**Information design**

- [AI Design Bible](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/README.md)
- [Foundations](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/FOUNDATIONS.md)
- [Interaction and Information](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/INTERACTION-AND-INFORMATION.md)
- [Visual Systems](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/VISUAL-SYSTEMS.md)

---

# 5. Standard section contract

Every major section begins with a compact execution contract.

Use:
[Section Build Contract](../templates/SECTION_BUILD_CONTRACT.md).

At minimum record:

```text
SECTION
<working title>

HISTORICAL PERIOD
<dates / era>

PARENT CHAPTER
<chapter>

GOAL
<observable reader understanding>

CENTRAL QUESTION
<question this section answers>

SOURCE OF TRUTH
<evidence package / authoritative sources>

BOUNDARY
<what this section is and is not trying to establish>

ACCEPTANCE
<observable pass/fail>

VERIFICATION / REVIEW
<how claims and teaching quality will be checked>

RECOVERY
<when to research, re-plan, reframe, preserve unknown, cut, or escalate>
```

This follows:

- [MAPS_L Request Compilation](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/REQUEST_COMPILATION.md)
- [MAPS_L AGI Standard](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/AGI_STANDARD.md)

The goal is **fresh-agent executability without consequential guessing**, not maximum documentation.

---

# 6. GOAL

State what the reader should understand when the section is finished.

Weak:

> Explain Reconstruction.

Better:

> Explain what Reconstruction attempted, why the federal government intervened in Southern political society after the Civil War, what changed for formerly enslaved Americans, why those gains faced organized resistance, why federal commitment weakened, and how Reconstruction's successes and failures shaped later American government and civil rights.

A good goal is observable in reader understanding.

---

# 7. READER STARTING POINT

Assume an intelligent reader with little specialized historical knowledge.

Record likely prerequisite knowledge.

Example:

```text
Reader should already understand:

- Civil War ended slavery.
- Confederate states had left the Union.
- Lincoln was assassinated.

Reader should NOT be assumed to understand:

- federalism;
- 13th/14th/15th Amendments;
- Black Codes;
- Radical Republicans;
- sharecropping;
- Redemption;
- Reconstruction governments.
```

This drives the Rung teaching structure.

Relevant Rung sources:

- [Teaching Loop](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Teaching-Loop.md)
- [Assistance Ladder](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Assistance-Ladder.md)
- [Diagnosing Mistakes](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Diagnosing-Mistakes.md)

---

# 8. CENTRAL QUESTION

Every section should answer at least one meaningful historical question.

Examples:

```text
Why did the American colonies revolt?

Why did slavery expand while American democracy expanded?

Why did the party system collapse in the 1850s?

Why did Reconstruction fail to produce durable political equality?

Why did industrialization create both enormous prosperity and major labor conflict?

Why did the United States become a global power?

Why did the New Deal permanently change Americans' relationship with the federal government?
```

A section should not exist merely because chronological coverage says an event happened.

The question should help determine what evidence matters.

---

# 9. CURRENT REALITY / EXISTING KNOWLEDGE

Before drafting, record:

## VERIFIED

What is already strongly established.

## REPORTED

What a source/person says but the project is not independently establishing.

## INTERPRETATION

Evidence-based explanatory claims.

## ASSUMED

What the working interpretation currently assumes.

## UNKNOWN

What materially affects the section but has not been resolved.

## DISPUTED

Where serious interpretations differ.

This is the MAPS_L **inspect reality before planning** step.

References:

- [Project Bootstrap](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/PROJECT_BOOTSTRAP.md)
- [AGI Standard](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/AGI_STANDARD.md)

---

# 10. THINK PASS

Use THINK proportionally.

The current THINK project's evidence-backed structured baseline emphasizes:

- decomposition;
- assumption mapping;
- first principles;
- counterexample search.

References:

- [THINK Project](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-creativity-and-ideation/THINK_PROJECT.md)
- [THINK Evidence-Driven Improvement Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/03-THINK-CREATIVITY-AND-IDEA-ECOLOGY.md)
- [THINK Roadmap Map](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/think/README.md)

Do not assume richer search, branching, or Idea Ecology should run by default simply because those ideas exist in the research. Escalate reasoning only when the historical problem warrants it.

## Decomposition

Break the central question into components/causes.

Example:

```text
Why did Reconstruction collapse?

political commitment
Southern resistance
racial ideology
economic structure
federalism
Supreme Court decisions
Northern elections
violence
economic depression
party politics
```

## Assumption mapping

Ask:

```text
What are we already assuming?

Which assumptions are necessary for our explanation?

Which would materially change the story if false?
```

## First principles

Ask:

```text
What actually needs explaining?

What evidence would exist if this explanation were correct?

What are contemporary actors actually deciding or reacting to?
```

## Counterexample search

Ask:

```text
What evidence would make our preferred explanation weaker?

Are there cases where the proposed cause exists but the predicted result does not?

Are there contemporary documents contradicting the interpretation?
```

## THINK output

Preserve:

```text
central frame
working hypotheses
important alternatives
assumptions
important unknowns
potential counterexamples
evidence that could discriminate among explanations
reopening / reconsideration conditions
```

PLAN should receive this structure rather than a flattened task like “research X.”

---

# 11. PLAN PASS

PLAN converts historical questions into bounded research.

References:

- [AI Planning and Orchestration Research](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-planning-and-orchestration/README.md)
- [PLAN Orchestration and Task Compilation Roadmap](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/05-PLAN-ORCHESTRATION-AND-TASK-COMPILATION.md)
- [PLAN Roadmap Map](https://github.com/BigCatMellow/Pilot_Projects/blob/main/complete-ai-work-system/roadmaps/plan/README.md)

The most useful PLAN ideas for this project are:

- proportional / diagnosis-gated decomposition;
- expected evidence / discrepancy;
- smallest-correction reconciliation;
- value-of-information thinking;
- acquire information only when it can materially affect the conclusion;
- preserve important THINK assumptions/alternatives through the research plan.

For every material hypothesis:

```text
CLAIM / HYPOTHESIS

WHY IT MATTERS

EXPECTED EVIDENCE

BEST SOURCE TYPES

WHAT WOULD WE EXPECT IF IT WERE WRONG?

DEPENDENCIES

STOP CONDITION
Enough evidence exists to support, reject, narrow,
or preserve uncertainty.
```

Prefer the smallest research action capable of changing the conclusion.

Do not collect sources merely because more sources feel safer.

### Example

Question:

> Why did Southern states secede?

THINK may produce:

```text
A. slavery and its expansion;
B. state sovereignty / federalism;
C. economic conflict;
D. Lincoln's election / Republican control;
E. interaction among several mechanisms.
```

PLAN then asks which evidence can actually distinguish these:

- declarations of secession;
- secession convention debates;
- Confederate constitutional changes;
- speeches and correspondence;
- platform documents;
- tariff/economic data where relevant;
- chronology of election/secession;
- evidence of federal-power demands by Southern politicians.

That is more useful than five separate open-ended research tasks.

---

# 12. RESEARCH BRIEF

For every major disputed or consequential question, use a bounded research brief.

Reference:
[MAPS_L Research Before Architecture](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/RESEARCH.md).

## Question

Specific and answerable.

## Evidence standard

What evidence would justify an answer?

## Claim-evidence table

| Claim | Source | Source type | Evidence | Status | Open issue |
| --- | --- | --- | --- | --- | --- |
| `<claim>` | `<exact locator>` | primary / secondary | `<support>` | VERIFIED / etc. | `<issue>` |

Record exact source locations.

Where applicable include:

- document title;
- author/institution;
- date;
- URL/repository/archive;
- page;
- section;
- chapter;
- table;
- archival identifier;
- retrieval date when freshness matters.

Do not retain an important claim whose source cannot be recovered.

---

# 13. SOURCE DIVERSITY CHECK

For major events, deliberately check whether relevant evidence exists from:

- government/institutional records;
- political supporters;
- political opponents;
- people directly affected;
- marginalized populations where relevant;
- economic/data records;
- foreign observers where useful;
- later historians from materially different interpretive traditions.

This is **not a quota**.

Include a perspective because it changes understanding, supplies missing evidence, or tests the narrative—not merely to manufacture symmetry.

A source's identity is context for evaluation, not a reason to automatically believe or dismiss it.

---

# 14. CONTEXT PASS

Before judging an action, reconstruct the world in which it occurred.

Explain when relevant:

```text
What did people know?

What did they not know?

What institutions existed?

What laws existed?

What choices appeared available?

What economic incentives existed?

What cultural assumptions were common?

What threats did people perceive?

What vocabulary did they use differently from us?
```

Context explains behavior.

It does not automatically excuse behavior.

This distinction is central to avoiding both presentism and apologetics.

---

# 15. CAUSATION PASS

Avoid:

```text
X happened.
Then Y happened.
Therefore X caused Y.
```

For major causal claims ask:

1. Did the proposed cause precede the outcome?
2. Is there evidence actors responded to it?
3. Is there a plausible mechanism connecting them?
4. Are competing explanations stronger?
5. Does the explanation survive relevant counterexamples?
6. What evidence would falsify or narrow it?
7. Is this a **cause**, **contributing factor**, **trigger**, **justification**, or **consequence**?

Use those words carefully.

The book should teach readers that historical causation is usually layered rather than a single magic cause.

---

# 16. NARRATIVE BUILD

The reader-facing section should normally follow this structure when the pieces materially fit.

## A. The Question

Why are we examining this?

## B. The Simple Story

Give the reader the basic model first.

Usually 1–5 paragraphs.

## C. The World They Lived In

Give only the context required to understand what follows.

## D. What Happened

Readable chronological narrative.

## E. Why It Happened

Causation and motivations.

## F. Look Closer

Where does the simple version become incomplete?

## G. Competing Explanations

Present serious alternatives where they materially matter.

## H. The Evidence

Show especially revealing primary evidence, statistics, maps, laws, votes, quotations, or records.

## I. Different Experiences

Where important, show how the event looked different depending on someone's position.

## J. What Changed

Immediate consequences.

## K. What Didn't Change

Continuities are often as important as changes.

## L. Memory and Myth

How later generations simplified, celebrated, condemned, or repurposed the event.

## M. How This Became Modern America

Trace specific surviving effects.

## N. Transfer

Give the reader a different claim or example to reason through using the concept they just learned.

Not every section needs all fourteen parts. Use them because they help the reader, not because the template exists.

---

# 17. THE SIMPLE STORY RULE

Every major subject begins with a model simple enough for a novice to hold.

Example:

> Political parties are coalitions. The names can survive even while the voters, factions, and ideas inside them change.

Then complexity is added **only where the simple model fails**.

Do not begin with every exception.

This is strongly aligned with Rung's assistance/guidance model:

- [Teaching Loop](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Teaching-Loop.md)
- [Assistance Ladder](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Assistance-Ladder.md)
- [Research Foundations](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Research-Foundations.md)

The reader needs a usable mental structure before receiving every nuance.

---

# 18. MODERN CONNECTION RULE

A present-day connection requires a causal bridge.

Do not write:

> This is why politics is divided today.

Instead demonstrate:

```text
historical event
↓
institution / movement / demographic change
↓
later transformation
↓
surviving structure or conflict
↓
modern manifestation
```

If the bridge cannot be established, describe the similarity without claiming causation.

### Example pattern

```text
Reconstruction Amendments
↓
constitutional federal protection of citizenship / voting / equal protection
↓
later judicial interpretation and enforcement conflicts
↓
20th-century civil-rights litigation and legislation
↓
modern constitutional/voting-rights disputes
```

The exact bridge still needs evidence. The diagram is only the structure of the claim.

---

# 18.5. EXPLANATORY POSTURE RULE

The prose should sound like it is **explaining a historical problem**, not answering an opponent.

Avoid rhetorical habits that make the reader feel they have entered an argument:

- repeated negation-first framing (`this is not...`, `what people get wrong...`);
- debate language (`the mistake is...`, `this proves...`, `the truth is...`);
- verdict language before the evidence is shown (`all of that is true`, `obviously`, `clearly`);
- imagined partisan opponents unless the historical dispute itself requires them;
- second-person correction (`do not think...`, `you should understand...`) when a descriptive explanation will work;
- loaded transitions such as `actually`, `really did`, `of course`, or `even` when they imply surprise or prior disbelief.

Prefer:

```text
The 1960 platforms show...
The coalition contained...
The evidence supports...
This change occurred over several decades...
One interpretation emphasizes...
The available evidence does not establish...
```

Strong conclusions are allowed when evidence supports them. The neutrality requirement is about **rhetorical posture**, not weakening well-supported facts.

A useful test:

> If a reader strongly identified with either modern party, would the prose still feel like a description of the evidence rather than an argument aimed at them?

# 18A. HEADER FRAMING RULE

Headings should **orient, not argue**.

Especially on politically charged or contested material, avoid headings that sound like they are correcting an opponent, defending a side, or trying to persuade the reader before the evidence is presented.

Prefer descriptive headings:

```text
Emancipation, abolition, and Reconstruction
The New Deal and Black voters
Civil rights and the party coalitions
The Southern realignment
```

Avoid advocacy-sounding headings such as:

```text
Republicans really did lead...
What critics get wrong...
The truth about...
Yes, Democrats really were...
```

The body may state strong conclusions when the evidence supports them. The heading should not make the reader feel that the section has already chosen an argument to win.

# 19. MYTH / MEMORY RULE

Use this section when a popular historical claim materially affects modern understanding.

Structure:

```text
COMMON VERSION

WHAT IT GETS RIGHT

WHAT IT LEAVES OUT

WHAT THE EVIDENCE SUPPORTS

WHY THE SIMPLER VERSION SURVIVED
```

Avoid creating straw-man myths merely to knock them down.

“Memory” can include:

- school narratives;
- commemorations;
- monuments;
- partisan retellings;
- family/community memory;
- movies/books;
- Lost Cause / triumphalist / exceptionalist / revisionist narratives where historically relevant.

Do not treat “myth” as synonymous with “thing we disagree with.”

---

# 20. QUOTATION RULE

Use quotations primarily when the exact language itself matters.

Examples:

- declaration of political motive;
- law;
- constitutional text;
- testimony;
- striking contemporary description;
- evidence of prevailing assumptions;
- language later remembered or disputed.

Do not substitute quotation collections for historical analysis.

A quotation still requires context:

- who said it;
- to whom;
- when;
- why;
- whether it represents private correspondence, public persuasion, law, testimony, propaganda, etc.

---

# 21. RUNG TEACHING PASS

Rung should remain mostly invisible to the reader. It governs how the explanation is constructed.

Core reference:
[Rung Teaching Loop](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Teaching-Loop.md).

The loop is:

```text
ORIENT
→ ATTEMPT
→ DIAGNOSE
→ EXPLAIN
→ MINIMUM HELP
→ REATTEMPT
→ VERIFY
→ TRANSFER
```

For each major section ask:

## Orientation

Does the reader understand what problem the section is trying to explain?

## Prerequisites

Have necessary concepts been supplied?

Reference:
[Assistance Ladder](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Assistance-Ladder.md).

## Misconceptions

What incorrect but plausible mental model is the reader likely to bring?

Reference:
[Diagnosing Mistakes](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Diagnosing-Mistakes.md).

## Assistance

Are we explaining only what the reader needs at that moment?

## Reattempt

Does later evidence let the reader reconsider the initial simple model?

## Verification

Can the reader explain the underlying relationship?

## Transfer

Can the reader apply the principle when the surface form changes?

Reference:
[Mastery and Transfer](https://github.com/BigCatMellow/Rung_Teaching/blob/main/wiki/Mastery-and-Transfer.md).

---

# 22. TRANSFER TEST

End major conceptual sections with a small application.

Example after party realignment:

> In 1860 Republicans opposed the expansion of slavery and Democrats were deeply divided over slavery. Does that tell us what a Republican or Democrat in 2026 believes?

The reader should be able to reason:

> No. Party organization, ideology, voter coalition, and historical ancestry are different things.

Transfer questions test understanding rather than trivia.

Another example after a causation section:

> A law was passed shortly before an economic collapse. What additional evidence would you need before saying the law caused the collapse?

The goal is to transfer **historical reasoning**, not memorize the previous chapter.

---

# 23. VISUAL / INFORMATION DESIGN PASS

Use the Design Bible only after the information structure is correct.

Exact references:

- [AI Design Bible](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/README.md)
- [Foundations](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/FOUNDATIONS.md)
- [Interaction and Information Design](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/INTERACTION-AND-INFORMATION.md)
- [Visual Systems](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/VISUAL-SYSTEMS.md)
- [Evaluation](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/EVALUATION.md)
- [Anti-Patterns](https://github.com/BigCatMellow/Pilot_Projects/blob/main/ai-design-bible/ANTI-PATTERNS.md)

Potential tools:

- timelines;
- coalition diagrams;
- maps;
- before/after comparisons;
- causal chains;
- annotated primary sources;
- small tables;
- political-family trees;
- institutional lineage diagrams;
- “Simple Story / Look Closer” callouts.

## Design rule

Visual hierarchy should reflect information hierarchy.

Possible consistent treatments:

### Main narrative

Normal readable prose.

### Big idea

A strong short statement of the mental model.

### Context

Secondary block explaining necessary historical background.

### Primary evidence

Distinct treatment that makes source identity obvious.

### Competing interpretation

Clearly labeled as interpretation, not fact.

### Modern connection

Consistent end-of-section pattern.

### Myth / memory

Distinct but not sensationalized.

### Transfer

Short application question.

Do not create “card soup” or decorate every paragraph.

The reader should be able to skim the visual hierarchy and understand the section's logic.

---

# 24. REVIEW LEVEL

Assign proportional review.

Reference:
[MAPS_L Checks and Balances](https://github.com/BigCatMellow/MAPS_Lean/blob/main/docs/CHECKS_AND_BALANCES.md).

## LOW

Typical examples:

- straightforward dates;
- definitions;
- simple chronology;
- transitions already strongly sourced.

Minimum:

- owner verification.

## MEDIUM

Typical examples:

- important causal explanation;
- multi-source synthesis;
- interpretation that materially shapes a chapter;
- modern connection.

Minimum:

- evidence reproduction;
- independent review.

## HIGH

Typical examples:

- major disputed historical interpretation;
- politically consequential claim;
- claim likely to shape several later chapters;
- claim whose failure would materially distort the book's thesis.

Minimum:

- explicit acceptance criteria;
- claim-evidence package;
- evidence reproduction;
- independent review;
- adversarial challenge when useful.

Do not create fake controversy where strong evidence already resolves the matter.

---

# 25. INDEPENDENT REVIEW

Reviewer receives:

```text
section goal
central question
major claims
claim/evidence matrix
draft
source package
known uncertainties
review level
```

Reviewer checks:

## Accuracy

Do sources support the factual claims?

## Source use

Does the source actually establish the proposition assigned to it?

## Causation

Does evidence justify causal language?

## Context

Are actors being interpreted using knowledge unavailable to them?

## Omission

Is missing evidence materially distorting the explanation?

## Counterevidence

Has important contradictory evidence been ignored?

## Interpretation

Is interpretation being presented as established fact?

## Modern connection

Is the causal chain to the present demonstrated?

## Teaching

Could a novice reasonably construct the intended mental model?

## Transfer

Does the transfer task actually test the concept rather than repeat the section?

Possible verdicts:

```text
APPROVED
CHANGES_REQUESTED
BLOCKED — NEEDS RESEARCH
```

A reviewer should not invent new requirements after the section was built unless the new issue reveals a genuine correctness/evidence/scope/teaching failure.

---

# 26. ADVERSARIAL CHALLENGE

For consequential interpretations that reach strong internal consensus without having been meaningfully challenged, use a fresh challenger when proportional.

The structure is adapted from:
[MAPS_L Tenth Seat Review](https://github.com/BigCatMellow/MAPS_Lean/blob/main/playbook/TENTH_SEAT_REVIEW.md).

Important boundary:

The upstream Tenth Seat file is designed around MAPS_L PR/status triggers. Those triggers do **not** automatically govern the History Book.

The History Book borrows only the useful adversarial mechanism unless a future approved project decision defines stronger book-specific triggers.

The challenger asks:

```text
What exactly is our conclusion?

What assumptions must hold?

Which assumption is weakest?

What is the strongest credible alternative explanation?

What evidence should exist if that alternative is true?

Does that evidence exist?

What evidence weakens the alternative?

What would cause us to reopen this conclusion?

What is the cost if the book gets this wrong?
```

The challenger must record evidence against its own alternative too.

The goal is not contrarianism.

The goal is to test a load-bearing conclusion that has not received meaningful opposition.

---

# 27. SECTION ACCEPTANCE CRITERIA

A section is DONE only when all applicable conditions pass:

- [ ] its central historical question is answered as far as available evidence permits;
- [ ] important factual claims have recoverable sources;
- [ ] material assumptions are not presented as facts;
- [ ] interpretation is identified as interpretation where necessary;
- [ ] major causal claims identify mechanisms rather than chronology alone;
- [ ] important serious counterevidence has been investigated;
- [ ] uncertainty/disagreement remains visible where warranted;
- [ ] relevant historical actors are explained in contemporary context;
- [ ] relevant affected populations are not omitted in a way that distorts the account;
- [ ] modern connections contain an evidenced causal bridge;
- [ ] the simple explanation is understandable without specialized background;
- [ ] necessary complexity is introduced without overwhelming the basic model;
- [ ] the reader can identify the section's primary lesson;
- [ ] transfer tests the underlying concept;
- [ ] required review has passed.

---

# 28. STOP / RECOVERY RULES

If evidence contradicts the draft:

```text
DO NOT
defend the prose.

DO
change the prose.
```

If the evidence undermines a local claim:

```text
RESEARCH / CORRECT
```

If it undermines the research structure:

```text
PLAN
reassess what evidence is actually needed
```

If it undermines the causal/explanatory frame:

```text
THINK
reframe the historical question
```

If credible evidence cannot resolve the dispute:

```text
PRESERVE DISPUTED / UNKNOWN
```

If the section no longer contributes materially to the parent chapter:

```text
CUT / MERGE / RESTRUCTURE
```

If the necessary next action leaves approved project authority:

```text
HUMAN REAUTHORIZATION
```

Do not convert uncertainty into certainty for narrative convenience.

---

# 29. SECTION COMPLETION RECORD

When finished, preserve:

```text
SECTION
<title>

CENTRAL QUESTION
<question>

MAIN CONCLUSION
<short answer>

STATUS
DONE

MAJOR VERIFIED CLAIMS
<claims>

IMPORTANT INTERPRETATIONS
<interpretations>

RESIDUAL UNCERTAINTIES
<none or list>

MAJOR SOURCES
<source package>

REVIEW
<review evidence>

REOPEN IF
<new evidence / specific condition>

NEXT SECTION
<next dependent historical question>
```

This allows another writer or agent to recover the project without reconstructing the original conversation.

---

# 30. Minimal instruction packet for a fresh section author

For routine use, the full system above compiles down to:

```text
GOAL
Teach the reader <historical understanding>.

CENTRAL QUESTION
<question this section answers>

STARTING POINT
Assume <reader knowledge>.
Do not assume <specialized concepts>.

SOURCE OF TRUTH
Prefer primary evidence and high-quality historical scholarship.
Record important claims with exact source locations.
Distinguish VERIFIED / REPORTED / INTERPRETATION / ASSUMED / DISPUTED / UNKNOWN.

THINK
Decompose the question.
Expose important assumptions.
Identify serious alternative explanations.
Search for counterexamples.

PLAN
Identify the smallest evidence package capable of distinguishing the important explanations.
Do not research indiscriminately.

WRITE
Use, where relevant:
Question
→ Simple Story
→ Historical Context
→ What Happened
→ Why
→ Look Closer
→ Evidence / Competing Explanations
→ Consequences
→ Memory / Myth
→ How This Became Modern America
→ Transfer

BOUNDARY
Do not force evidence into a patriotic or anti-American narrative.
Do not present interpretation as fact.
Do not manufacture controversy.
Do not claim modern causation without showing the bridge.

ACCEPTANCE
A novice can explain the core model.
Claims are evidence-backed.
Material disagreement and uncertainty are preserved.
Modern connections are demonstrated.
Required independent review passes.

RECOVERY
Local evidence problem → research.
Research-structure problem → PLAN.
Broken explanatory frame → THINK.
Unresolvable question → preserve UNKNOWN/DISPUTED rather than guess.
```

The reusable fill-in version is:
[Section Build Contract](../templates/SECTION_BUILD_CONTRACT.md).

---

# 31. Core project maxim

The book should repeatedly do four things:

```text
MAKE IT SIMPLE ENOUGH TO UNDERSTAND

MAKE IT ACCURATE ENOUGH TO TRUST

MAKE IT DEEP ENOUGH TO EXPLAIN THE PRESENT

TEACH THE READER HOW TO TEST THE STORY THEMSELVES
```

That is the project's quality bar.

---

# 32. External source ownership

Do not copy upstream MAPS_L, Rung, THINK, PLAN, philosophy, or Design Bible rules into multiple History Book files as mutable parallel versions.

Use:

- [METHOD_SOURCES.md](METHOD_SOURCES.md) for the annotated external map;
- this file for the History Book-specific method;
- [SECTION_BUILD_CONTRACT.md](../templates/SECTION_BUILD_CONTRACT.md) for the compact derived execution packet;
- [../AGENTS.md](../AGENTS.md) for repository-wide operating rules.

If upstream methods change, evaluate whether the History Book should adopt the change. Do not automatically inherit it merely because the link target changed.

The History Book must remain independently understandable and operable.
