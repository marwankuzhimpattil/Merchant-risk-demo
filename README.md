# Merchant Risk Intelligence System

Interactive prototype for the PM assessment from Modus AI.

## Live demo
https://YOUR-USERNAME.github.io/merchant-risk-demo/

## What this is
A decision-support prototype for risk analysts at Payment Aggregators.
Demonstrates the end-to-end pipeline: Queue → Submit → Processing → Decision → Audit.

## Architectural thesis
> The AI's job is to produce evidence, not verdicts.

Rules answer auditable questions; AI answers semantic questions; the deterministic engine combines both. The LLM is never on the verdict path.

## How to use
Click "+ Submit new merchant" and use one of the three presets to see how different inputs produce different verdicts. Same inputs always produce the same verdict — the demo is reproducible.

## Tech
Single HTML file. React via CDN. No build step.
