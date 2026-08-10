---
layout: page
permalink: /programming/
title: programming
description: Statistical programming tools and learning resources I build and maintain.
nav: true
nav_order: 4
---

This page collects the programming tools and statistical software I build —
for my own learning and research, and for anyone who finds them useful. More
programs will appear here over time.

## Coding Practice Lab

<p>
  <a href="https://muzhi-liu.com/coding-practice-lab/" class="btn btn-sm z-depth-0" role="button">Open the Lab</a>
  <a href="https://github.com/muzhi-liu/coding-practice-lab" class="btn btn-sm z-depth-0" role="button">Source on GitHub</a>
</p>

A local-first, open laboratory of executable data-science practice problems
in **Python and R** — covering machine learning, data cleaning, temporal
joins, model evaluation, and quantitative interview-style problem solving.

Each practice is a complete, self-contained exercise:

- a real problem statement with runnable code cells for your own attempt;
- **hints and the official solution collapsed by default**, so you can test
  yourself before revealing anything;
- line-by-line explanations, common mistakes, and design rationale;
- small synthetic datasets, so everything runs offline on an ordinary laptop;
- automated tests proving every official solution actually runs;
- a transparent spaced-review scheduler that tells you when to re-attempt a
  problem you solved weeks ago.

The whole system is plain text — [Quarto](https://quarto.org) pages, YAML
metadata, and a thin Python tool layer — with no accounts, databases, or paid
services. Browse it directly in the browser, or clone the repository to run
the exercises, add your own practices, and track your own review schedule.
The site includes full-text search, a progress dashboard, and a filterable
catalog by topic, language, and difficulty.

The seed practice, *Hotel availability*, walks through a realistic
take-home-interview pipeline: cleaning scraped data, an as-of ownership join
(and why the naive join silently leaks future information), logistic
regression / random forest / XGBoost baselines, threshold selection on
validation F1, and producing a validated submission file — implemented twice,
in Python and in R.
