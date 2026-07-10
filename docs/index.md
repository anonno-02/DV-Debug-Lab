---
title: DV Debug Lab
description: Practical debug notes, code examples, and checklists for verification engineers.
---

# DV Debug Lab

**Practical debug notes for SystemVerilog, UVM, GLS, CDC, X-propagation, assertions, coverage, and regression scripting.**

This site is built for engineers who do not need another vague textbook explanation. They need the bug, the cause, the fix, and the checklist before the simulator invents a new way to ruin lunch.

## What you will find here

<div class="grid cards topic-card-grid" markdown>

-   [:material-code-tags:{ .lg .middle } **SystemVerilog**](systemverilog/index.md){ .topic-card-link }

    ---

    Blocking and non-blocking assignments, race conditions, clocking blocks, randomization failures, plusargs, and package/import debug.

-   [:material-bug-check:{ .lg .middle } **UVM Debug**](uvm-debug/index.md){ .topic-card-link }

    ---

    Scoreboards, analysis ports, config DB, virtual interfaces, sequences, drivers, monitors, and phase objections.

-   [:material-chip:{ .lg .middle } **GLS Debug**](gls-debug/index.md){ .topic-card-link }

    ---

    SDF annotation, X propagation, timing violations, reset behavior, and why RTL passes while GLS behaves like a haunted netlist.

-   [:material-sync:{ .lg .middle } **CDC & X-Propagation**](cdc-xprop/index.md){ .topic-card-link }

    ---

    Synchronizers, pulse crossing, metastability, glitches, and gate-level-only clock-domain problems.

-   [:material-checkbox-marked-circle-outline:{ .lg .middle } **Assertions & Coverage**](assertions-coverage/index.md){ .topic-card-link }

    ---

    SVA protocol checks, assertion failures, covergroups, bins, sampling issues, and practical closure workflows.

-   [:material-code-braces:{ .lg .middle } **Regression & Scripting**](regression-scripting/index.md){ .topic-card-link }

    ---

    Shell scripts, Makefiles, plusargs, logs, grep, awk, sed, Vim, and automation workflows for verification teams.

-   [:material-school:{ .lg .middle } **Interview Prep**](interview-prep/index.md){ .topic-card-link }

    ---

    Practical DV questions, debug scenarios, whiteboard flows, and concise explanations across SystemVerilog, UVM, CDC, GLS, and scripting.

</div>

## Start here

- [Start Here](start-here.md)
- [Topic Index](topics.md)
- [Templates & Downloads](templates-downloads/index.md)

## 30-day build target

The first content sprint will publish **30 practical topics in 30 days**.

Each topic will include:

- a full article
- a minimal broken example
- a corrected example
- debug checklist
- common error messages
- interview angle
- downloadable code folder

## Current status

This is the Phase 0 website shell. Topic pages will be added daily.
