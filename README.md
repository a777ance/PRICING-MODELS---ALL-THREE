# PRICING-MODELS---ALL-THREE

Interactive calculator for A777ance's three deployment models — **Self-Service**, **Remote**,
and **Local** — covering who pays whom (Customer / Operator / Alliance HQ), the hardware
storefront, and how the business scales with N (nodes/operators).

**→ [`pricing/master-amounts-calculator.html`](pricing/master-amounts-calculator.html)** — open
directly in a browser. Every figure is editable, with a reset-to-defaults button.

## What's in it

- **Per-model ledger** (tabs: Self-Service / Remote / Local) — setup fee, recurring fee, and (for
  Local) the flat per-operator licensing due, with computed net for the Customer, Operator, and
  Alliance HQ.
- **Hero N + macro split** — a big editable N (nodes/operators/mesh) and a diet-style macro bar
  mapping Self-Service (protein/lean), Remote (carbs/easy money — inversely proportional to N,
  hardwired to `100/N` with a floor of 10%), and Local (fat/bulking — exponential).
- **Storefront** — specialized hardware, new or refurbished, rent-or-own margin.
- **Three bottom-line totals**, each scaling with N: recurring, one-time (setup), and storefront
  (rent + own), kept separate so nothing is double-counted.
