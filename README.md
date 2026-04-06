# Chem Spark Studyguide

A self-contained interactive chemistry study guide built in pure HTML, CSS, and JavaScript.

## Overview

**Chem Spark Studyguide** is an interactive chemistry revision tool designed to help students build **deep mastery of balancing chemical equations**.

Rather than treating balancing as a mechanical exercise, this study guide teaches the **underlying chemical logic** that makes balancing easier, faster, and more intuitive.

It combines:
- a structured study workflow,
- interactive mixed practice,
- mistake review loops,
- and conceptual chemistry deep dives

into a single **self-contained HTML study artifact**.

The central learning goal is:

> **Help students understand what is happening chemically, so they can balance equations with real confidence rather than memorized tricks.**

Everything is contained in **one HTML file** with no external assets or dependencies.

---

## Core Learning Focus

This project is built around one main revision target:

# **Balancing Chemical Equations**

But it approaches that target in a smarter way by also teaching the supporting concepts students often need in order to balance equations well, such as:

- conservation of mass
- reaction pattern recognition
- metal displacement logic
- halogen displacement logic
- precipitation reasoning
- ionic combinations
- organic reaction recognition
- combustion and oxygen accounting

In other words:

> This is not just “practice balancing equations.”  
> It is a study guide for understanding **why equations look the way they do**.

---

## What This Project Includes

## 1) Study System
A guided revision workflow that helps students study balancing equations in a more effective sequence.

Includes:

- **Session Plan**  
  A structured 40-minute interleaved chemistry revision session

- **Mixed Drills (25)**  
  Practice questions spanning reaction balancing and related chemistry patterns

- **Advanced Drills (10)**  
  Harder exam-style balancing and reaction reasoning questions

- **Review Loop**  
  A mistake-based review system so incorrect questions can be revisited deliberately

This structure is designed to support:
- **active recall**
- **interleaving**
- **pattern recognition**
- **mistake-driven improvement**

rather than passive rereading.

---

## 2) Chemistry Deep Dives
The deep-dive sections are included to help students understand the **reaction logic behind balancing**, not as isolated chemistry topics.

They are designed to answer questions like:

- *Why does this reaction happen?*
- *Which products should I expect?*
- *Why does this solid form?*
- *Why is oxygen count tricky here?*
- *Why does one reactant displace another?*

That deeper understanding makes balancing much easier.

---

## Deep Dive Modules

### Metal Reactivity & Displacement Reactions
This section helps students understand how to predict **whether a displacement reaction should happen at all**, which is essential before balancing it.

Covers:
- what the activity series is actually ranking
- why some metals are more reactive than others
- how electron loss drives displacement
- why hydrogen is used as a benchmark
- how to predict whether a reaction will occur

Includes:
- interactive metal reactivity visualization
- periodic table context for metals
- halogen comparison and displacement logic

### Solubility, Ksp & Precipitation Reactions
This section helps students understand **why some ion combinations stay dissolved while others form solids**, which is crucial for writing and balancing precipitation equations correctly.

Covers:
- solubility
- saturated solutions
- equilibrium in ionic dissolution
- what **Ksp** means
- why precipitates form
- how to reason through **“Will it precipitate?”**

Includes:
- conceptual explanation of the **Q vs Ksp** idea
- common solubility rule support
- a **“Will it precipitate?” checker**
- ionic / net ionic equation logic

### Core Organic Reactions
This section helps students recognize common **organic reaction patterns**, especially where students often get stuck balancing oxygen, carbon, and hydrogen.

Covers:
- **alkanes**
- **alcohols**
- **esters**

Includes support for:
- complete combustion
- incomplete combustion
- fermentation
- esterification
- cracking
- oxygen accounting in combustion balancing

Also includes a built-in **combustion balancing helper / O₂ calculator**.

---

## Why the Deep Dives Matter

A student often struggles with balancing not because they “can’t do coefficients,” but because they do not yet understand:

- what products should form
- what reaction type they are looking at
- which species stay aqueous
- which species form solids
- how organic formulas transform
- where oxygen and hydrogen counts come from

This project is designed to close that gap.

---

## Learning Design Principles

This project was designed around a few educational principles:

- **Understanding before memorization**
- **Balance the chemistry, not just the numbers**
- **Interleaved practice beats isolated drills**
- **Mistakes are part of the learning loop**
- **Conceptual clarity reduces balancing errors**
- **Student-friendly but academically serious presentation**

Where useful, the tutorial uses scaffolds such as:
- **Core idea**
- **Common mistake**
- **Exam shortcut**
- **Why this works**

to make difficult chemistry ideas easier to absorb and retain.

---

## Features

- Fully self-contained single HTML file
- No frameworks
- No build step
- No external assets
- Light “lab notebook” visual design
- Pure HTML / CSS / JavaScript interactivity
- Interactive tabbed study workflow
- Expandable concept explainers
- Drill answer reveal system
- “Got it / Missed it” tracking
- Review loop generated from mistakes
- Chemistry-themed UI built entirely inline

---

## Tech Stack

- **HTML**
- **CSS**
- **Vanilla JavaScript**

No React, no backend, no database, no dependencies.

---

## Project Structure

```text
chem-spark-studyguide/
├── index.html
├── README.md
├── LICENSE
└── prompts.md