---
title: "Topic Title Here"
description: "One-sentence SEO description of the problem and solution."
tags:
  - systemverilog
  - uvm
  - debug
---

# Topic Title Here

## Problem summary

Write the exact problem in one paragraph.

Example:

> The monitor prints transactions, but the scoreboard does not receive anything through the analysis port.

## Where this happens

- UVM environments
- Monitor-to-scoreboard connections
- Analysis port/export/imp usage
- Testbench bring-up

## Why it happens

Explain the root causes.

Common causes:

1. Analysis port not connected
2. Wrong analysis imp declaration
3. Wrong transaction type
4. Scoreboard not constructed
5. Component hierarchy mismatch
6. Phase ordering issue

## Minimal broken example

```systemverilog
// Broken code goes here
```

## Corrected example

```systemverilog
// Fixed code goes here
```

## Debug flow

1. Confirm monitor writes the transaction.
2. Confirm scoreboard exists.
3. Confirm connection happens in `connect_phase`.
4. Confirm type matches.
5. Confirm scoreboard `write()` is implemented.
6. Add debug prints at each boundary.

## Checklist

- [ ] Monitor prints transaction before `ap.write(tx)`
- [ ] Analysis port is constructed
- [ ] Scoreboard is constructed
- [ ] Port is connected in `connect_phase`
- [ ] Transaction type matches
- [ ] Scoreboard has correct `write()` signature
- [ ] Factory did not replace the expected component accidentally

## Common simulator messages

```text
Add real error/warning messages here when available.
```

## Interview angle

A common interview version of this problem:

> A UVM monitor is collecting packets, but the scoreboard is empty. How would you debug it?

Expected answer:

- Check monitor write path
- Check analysis connection
- Check scoreboard implementation
- Check transaction type
- Check build/connect phase ordering

## Downloadable files

Example folder:

```text
examples/path/to/topic/
```

## Related topics

- Link to related topic 1
- Link to related topic 2
