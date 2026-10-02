---
name: evolutionary-learning
description: Build and teach complex subjects through an evolutionary learning path: reconstruct the sequence of problems, limitations, discoveries, abstractions, and new capabilities that cause concepts to emerge, then turn that path into an interactive curriculum with experiments, verification, and reconstruction tasks.
---

# Evolutionary Learning

## Purpose

Use this skill to learn a complex subject by **re-expanding its compressed mature knowledge into a learnable evolution path**.

The goal is not to make an easier summary of a mature knowledge system.

The goal is:

> Turn a mature knowledge system into a sequence of `problem → existing capability → limitation → discovery → abstraction → new capability → new problem`, then let the learner experience that sequence.

The desired outcome is not merely recall. The learner should be able to:

- understand concepts;
- derive important results;
- apply concepts to new problems;
- explain relationships between concepts;
- reconstruct the knowledge system after forgetting details.

---

# Core Principle

Mature knowledge is highly compressed.

A modern textbook may present:

```text
Concept A
Concept B
Concept C
Concept D
```

But the underlying cognitive structure is closer to:

```text
Problem
  ↓
Existing method
  ↓
Method reaches a limitation
  ↓
Observation
  ↓
New abstraction
  ↓
New capability
  ↓
New problem
  ↓
Next abstraction
```

Therefore:

> Organize learning around the **evolution of capabilities**, not around a list of knowledge points.

---

# When to Use

Use this skill when the user wants to:

- deeply learn a complex subject;
- understand why a field developed its current structure;
- build a tutorial or textbook for a difficult domain;
- avoid memorization-first learning;
- understand conceptual dependencies;
- reconstruct a discipline from basic problems;
- create an AI-assisted learning curriculum.

It is especially useful for:

- mathematics;
- physics;
- computer science;
- software engineering;
- operating systems;
- databases;
- programming languages;
- statistics;
- machine learning;
- artificial intelligence.

Do not require literal historical accuracy in the conceptual sequence. The target is **conceptual/cognitive evolution**, not a chronology of people and dates.

---

# Workflow

Follow this workflow:

```text
1. Identify
      ↓
2. Decompress
      ↓
3. Map
      ↓
4. Find Pressure
      ↓
5. Construct Evolution
      ↓
6. Build Curriculum
      ↓
7. Learn
      ↓
8. Verify
      ↓
9. Reconstruct
```

Do not jump directly from the subject name to a conventional chapter list.

---

# 1. Identify

Determine:

- What subject is being learned?
- What is the learner's current level?
- What is the desired target capability?
- What problems does the field fundamentally solve?
- What are the major concepts?
- What are the major conceptual dependencies?

Produce an initial model:

```text
Domain
Current Level
Target Capability
Core Problems
Major Concepts
Major Dependencies
```

If the learner's level materially changes the curriculum, ask for clarification. Otherwise make a reasonable assumption and state it.

---

# 2. Decompress

Take the mature knowledge system and decompose important concepts.

For each major concept, ask:

1. What problem does it solve?
2. What methods existed before it?
3. Why did those methods become insufficient?
4. What observation makes the new concept possible?
5. What abstraction captures that observation?
6. What new capability does the abstraction provide?
7. What new problem becomes visible afterward?

Represent each concept as:

```text
Problem
→ Existing Capability
→ Limitation
→ Discovery
→ Concept
→ New Capability
→ New Problem
```

Do not assume that every concept needs a literal historical origin. Prefer structural necessity over historical storytelling.

---

# 3. Map the Concept Dependencies

Build a conceptual dependency graph.

Example:

```text
Linear equations
      ↓
Elimination
      ↓
Matrix
      ↓
Vector
      ↓
Linear combination
      ↓
Span
      ↓
Independence
      ↓
Basis
      ↓
Dimension
```

A normal table of contents answers:

> What should I learn?

An evolutionary map answers:

> Why does the next thing become necessary?

Prefer the second.

When concepts have multiple dependencies, represent them explicitly rather than forcing a false linear chain.

---

# 4. Find Pressure

Every major abstraction should have a clear **pressure** that motivates its introduction.

Pressure means:

> The problem that makes the existing conceptual toolkit insufficient.

Examples:

```text
Many equations
→ individual manipulation becomes unwieldy
→ matrix

Many related quantities
→ need to manipulate them as a unit
→ vector

Need to understand Ax
→ expand Ax by coordinates
→ linear combination

Many possible descriptions of the same space
→ need a minimal non-redundant description
→ basis
```

For every major concept, be able to answer:

> If this concept did not exist, what problem would become difficult?

If there is no convincing answer, reconsider whether the concept belongs at that point.

---

# 5. Construct the Evolution

Construct chains of:

```text
Problem
↓
Try
↓
Failure / Limitation
↓
Observation
↓
Discovery
↓
Abstraction
↓
New Capability
↓
New Problem
```

The chain must preserve causality.

Example:

```text
Need to solve many equations
        ↓
Repeated elimination
        ↓
Too much repeated structure
        ↓
Separate coefficients from variables/results
        ↓
Matrix
        ↓
Represent the whole system as one object
        ↓
What does the matrix do to an input?
        ↓
Matrix as transformation
        ↓
Linear transformation
```

This is the fundamental unit of the curriculum.

---

# 6. Build the Curriculum

Convert the evolution graph into chapters.

Do not organize primarily by textbook categories.

Organize around the cognitive problems that force the next abstraction.

Prefer problem-oriented chapter titles when appropriate.

Instead of:

```text
Chapter 5: Linear Combination
```

prefer something like:

```text
What vectors can we produce from a given set of vectors?
```

Then introduce the formal term `linear combination` after the learner has encountered the underlying need.

The curriculum should feel like:

```text
I have a problem.
↓
I try what I already know.
↓
It starts to fail.
↓
I notice a pattern.
↓
I invent/encounter an abstraction.
↓
The abstraction solves the problem.
↓
The solution exposes a deeper problem.
↓
Continue.
```

---

# 7. Chapter Protocol

Each chapter should use the following structure when appropriate:

```text
# Problem

Present a concrete problem.

# Try

Give the learner an opportunity to solve or reason before revealing the abstraction.

# Failure

Show where the existing method becomes insufficient.

# Discovery

Highlight the structure that becomes visible.

# Concept

Introduce and formally define the new concept.

# Derivation

Derive important formulas or results from previously established knowledge.

# Experiment

Use computation or examples to make the structure observable.

# Visualization

Use diagrams or geometry when they genuinely clarify the idea.

# Connection

Connect the new concept to earlier concepts.

# New Problem

Show what new question becomes possible because of the new capability.

# Reconstruction

Ask the learner to rebuild the idea without looking.
```

Do not mechanically force every section into every chapter. Preserve the causal structure above all else.

---

# 8. Do Not Leak Future Concepts

Do not reveal the conceptual destination before the learner has encountered the pressure that motivates it.

For example, when introducing linear combinations, do not begin by saying:

> Matrix-vector multiplication is a linear combination of the columns.

Instead:

1. Ask the learner to compute `Ax`.
2. Expand the result.
3. Group terms by the input coordinates.
4. Let the structure become visible.
5. Then name it `linear combination`.

Principle:

> A concept should appear as the result of discovery, not as a prematurely supplied answer.

---

# 9. Mathematical and Factual Rigor

Evolutionary presentation must not reduce rigor.

Maintain:

- correct definitions;
- consistent notation;
- valid derivations;
- verifiable examples;
- correct theorems;
- clear assumptions;
- distinction between intuition and formal definition.

When useful, separate:

```text
Intuition
Strict Definition
Derivation
Proof
```

If the conceptual path is pedagogically reconstructed rather than historically exact, say so.

Never present a constructed conceptual sequence as literal historical fact.

---

# 10. Experiments

Use experiments whenever they reveal a structure better than prose.

Suitable tools include:

- Python;
- NumPy;
- Matplotlib;
- SymPy;
- domain-specific simulators.

The purpose of an experiment is not to show code.

Its purpose is:

> Let the learner observe the behavior implied by the abstraction.

Examples:

```text
Matrix
→ change matrix entries
→ observe transformation

Eigenvector
→ observe directions that remain invariant

Projection
→ observe geometric decomposition

Least squares
→ observe error minimization

SVD
→ observe low-rank reconstruction
```

Experiments should be reproducible whenever practical.

---

# 11. Verification

Do not verify learning through recall alone.

Use four levels:

## Recall

Can the learner explain the concept?

## Derivation

Can the learner derive the important result?

## Application

Can the learner use it on a new problem?

## Reconstruction

Can the learner recreate the concept from more basic ideas?

Example:

```text
Recall:
What is an eigenvector?

Derivation:
Why does Av = λv?

Application:
Find the eigenvectors of a given matrix.

Reconstruction:
If you forgot the definition, can you reconstruct the problem
of finding directions whose direction is unchanged by a transformation?
```

Prioritize reconstruction because it tests structural understanding.

---

# 12. Hint Policy

When the learner is stuck, do not immediately provide the complete solution.

Use progressive hints:

```text
Level 1
Direction hint

Level 2
Local observation

Level 3
Key relationship

Level 4
Full derivation
```

Example:

```text
Level 1:
Look at the columns of the matrix.

Level 2:
What happens if Ax is grouped by x₁ and x₂?

Level 3:
Try writing Ax as a weighted sum of two vectors.

Level 4:
Provide the complete derivation.
```

The objective is:

> Maximize the learner's own cognitive work while preventing unproductive dead ends.

---

# 13. Learning State

When running an interactive course, track learning by concept rather than only by chapter completion.

Suggested state:

```text
Concept
Recall
Derivation
Application
Reconstruction
Confidence
```

Example:

```text
Concept: Linear Independence

Recall: ✓
Derivation: ✓
Application: △
Reconstruction: ✗
```

Do not equate:

```text
Chapter completed
```

with:

```text
Concept mastered
```

If reconstruction repeatedly fails, revisit the conceptual pressure and earlier dependencies.

---

# 14. Periodic Reconstruction

After several chapters, stop normal progression.

Ask the learner to reconstruct the conceptual map from memory.

For example:

```text
Equation
 ↓
Elimination
 ↓
Matrix
 ↓
Vector
 ↓
Linear combination
 ↓
Span
 ↓
Independence
 ↓
Basis
 ↓
Dimension
```

Then ask:

- Why did A lead to B?
- What problem did B solve?
- What limitation would appear without B?
- How does B enable C?

The learner should be able to reconstruct **relationships**, not merely names.

---

# 15. Final Reconstruction Mode

After completing a substantial domain, stop teaching chapter-by-chapter.

Return to the original foundational problem.

Example:

> You only know elementary algebra. You are given a large system of linear equations. Rebuild the conceptual tools needed to solve increasingly difficult versions of the problem.

The learner should progressively recover the system:

```text
Equations
→ Elimination
→ Matrix
→ Vector
→ Linear combination
→ Space
→ Basis
→ Transformation
→ Eigenstructure
→ Orthogonality
→ Projection
→ Least squares
→ SVD
```

The AI should provide the smallest useful hint when the learner is stuck.

The goal is:

> Knowledge becomes something the learner can regenerate, not merely something the learner remembers.

---

# 16. Output Artifacts

This skill may produce:

- `evolution-map.md` — conceptual evolution graph;
- `curriculum.md` — complete learning path;
- chapter files;
- exercises;
- experiments;
- verification tasks;
- reconstruction tasks;
- knowledge graphs;
- learner state.

A reusable course should ideally contain:

```text
course/
├── README.md
├── SUMMARY.md
├── evolution-map.md
├── hugo.yaml
├── content/
│   ├── _index.md
│   ├── SUMMARY.md
│   └── chapters/
├── exercises/
├── experiments/
└── reconstruction/
```

## Ebook publishing default: OINK

When producing a reusable ebook or course site with this skill, use **OINK** (https://oink.pgsty.com/) as the default publishing theme and presentation system. Treat this as the default unless the learner explicitly requests another format or the target platform cannot use Hugo.

- Build the book as Markdown content in a Hugo project using the OINK theme. Keep the learning sequence, exercises, and experiments as source files rather than baking them into a one-off export.
- Use OINK's book/documentation navigation for chapters, a readable table of contents, cross-references, code examples, diagrams, and print output where appropriate.
- Preserve the evolutionary chapter structure: each chapter should expose the motivating problem before naming the abstraction, and should end by opening the next problem or asking for reconstruction.
- Include a concise landing page, course summary, and ordered chapter navigation. Keep exercises, experiments, and reconstruction prompts accessible from the relevant chapters.
- Prefer Hugo-native setup and local assets. Do not add a Node/npm toolchain just to publish the book. Pin or document the OINK theme version/source and required Hugo version in the project setup.
- Deliver the Hugo project so it can be built and published as a website; create a PDF or other ebook export when requested or when it materially helps the learner.

If the output is only an interactive chat lesson rather than a reusable ebook/site, OINK is not required. If a different output medium is required, retain the same clean typography, strong hierarchy, navigation, and code/diagram readability where that medium allows.

---

# 17. Anti-Patterns

Avoid turning Evolutionary Learning into:

## Historical storytelling

A chronology of people and dates is not enough.

History can provide context, but the core is conceptual necessity.

## Conventional textbook with stories

Adding narrative to:

```text
Definition → Theorem → Formula → Exercise
```

does not make it evolutionary.

## Concept lists

```text
Today:
Vector
Matrix
Eigenvalue
SVD
```

without explaining why each becomes necessary is not evolutionary.

## Premature answers

Do not introduce a concept before the learner has encountered the problem pressure that motivates it, unless necessary for safety, prerequisites, or explicit user preference.

## Entertainment-first gamification

The purpose is not merely to make learning fun.

The purpose is to make the **generation logic of knowledge experienceable**.

## False historical claims

Do not confuse a pedagogically reconstructed conceptual path with literal historical development.

---

# 18. Generalization

The method can be applied to many domains.

### Probability

```text
Uncertainty
→ events
→ probability
→ conditional information
→ Bayes
→ random variables
→ distributions
→ expectation
→ variance
→ laws of large numbers
→ central limit behavior
```

### Databases

```text
File storage
→ repeated lookup
→ indexing
→ data organization
→ concurrency
→ transactions
→ logging
→ recovery
→ MVCC
→ distributed databases
```

### Operating Systems

```text
Program
→ multiple programs
→ resource competition
→ process
→ isolation
→ virtual memory
→ files
→ concurrency
→ synchronization
→ scheduling
```

These examples illustrate the method, not necessarily literal historical sequences.

---

# 19. Fundamental Question

Throughout the entire learning process, repeatedly ask:

> **If the previous world already existed, why did we need this new concept?**

This is the central question of Evolutionary Learning.

Do not primarily ask:

> What is this concept?

Ask:

> **What problem forced this concept to become necessary?**

---

# 20. Final Principle

The ultimate goal is not:

> Learn a knowledge system.

It is:

> **Acquire the ability to recreate the knowledge system.**

A strong outcome looks like:

```text
Forget some formulas
        ↓
Still remember the underlying problem
        ↓
Remember why old methods were insufficient
        ↓
Recognize the missing structure
        ↓
Reconstruct the concept
        ↓
Re-derive the formula
```

When this happens:

> Knowledge has changed from something that is merely remembered into something that can be regenerated.
