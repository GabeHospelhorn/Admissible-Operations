# Admissible Operations
### AO-01 — Admissible Operations Law

Systems scale reliably only when non-admissible workflows are removed, not optimized.

## Quick Diagnostic

Before improving any workflow, ask:

- Does this require rework?
- Does it rely on human correction?
- Does it degrade under volume?

If any answer is yes:
→ redesign required

## Where This Shows Up

- RCM teams correcting upstream errors
- Call centers absorbing system failures
- AI increasing rework instead of reducing it
- Scheduling systems breaking under growth

## Use This If

- Your system works at low volume but breaks as it scales
- You are adding people to fix recurring issues
- Automation is increasing complexity instead of reducing it

## Core Idea

Scaling is not an optimization problem.  
It is a selection problem.

Remove what cannot scale. Then improve what remains.

## 1-Minute Version

Most teams try to improve everything.

That is often the wrong move.

Some workflows are structurally non-admissible. They only appear functional because people keep correcting them.

These workflows should not be optimized. They should be removed or redesigned.

The system scales only after those workflows are eliminated.

## Diagram Notes

### Diagram — Optimize vs Remove

LEFT:
Broken Workflow → Optimize → Still fragile → More fixes

RIGHT:
Broken Workflow → Remove or Redesign → Stable → Then optimize

## Applied Examples

### Revenue Cycle

RCM often appears to be working when it is actually compensating for errors introduced earlier in the process.

### Call Centers

Call centers often absorb ambiguity, confusion, and scheduling failures that should have been prevented upstream.

## Note

If your system keeps adding labor to fix recurring issues, it may be optimizing non-admissible workflows.
