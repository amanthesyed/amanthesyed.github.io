# Aman Syed — Product, Growth & AI Systems

**Live site:** https://amanthesyed.github.io/

This repository is the implementation of my product portfolio. It is deliberately a working site rather than a template: the case studies pair product decisions with small interactive tools so a reader can inspect assumptions instead of taking a slide's headline at face value.

## What is inside

- **Product case studies** — chronic-care onboarding and Cashback Streak, including scope choices, funnel events, experiment setup, and trade-offs.
- **Growth models** — adjustable traffic, conversion, AOV, and retention assumptions. Outputs are labelled as modelled opportunities rather than realised business results.
- **AI decision labs** — support triage and agent workflows that distinguish routine, low-risk actions from cases needing human review.
- **Automation concepts** — trigger → context → decision → routing → system-of-record patterns, including the reasons to escalate exceptions.
- **Product artifacts** — a PRD, measurement map, decision record, integration architecture, opportunity scoring model, and agent-safety spec.
- **Engineering examples** — integration and operational automation work, framed around constraints, reliability, and measurable outputs.

## Implementation

The site is a static GitHub Pages project built with:

- Semantic HTML for the page structure
- CSS for layout, responsive behaviour, and the visual system
- Vanilla JavaScript for sliders, decision labs, tabs, and interactive case-study controls
- SVG for the site favicon

There is no package install or build step. The live site is served from the repository's `main` branch.

## Run locally

Clone the repository and open `index.html` in a browser. Because this is a static site, a local server is optional; using one is useful when checking browser behaviour:

~~~bash
git clone https://github.com/amanthesyed/amanthesyed.github.io.git
cd amanthesyed.github.io
python -m http.server 8000
~~~

Then visit http://localhost:8000.

## Reading the numbers

The portfolio intentionally separates **observed context**, **experiment design**, **targets**, and **modelled opportunity**. Interactive calculators are sensitivity tools, not predictive models; a projected lift should not be interpreted as a shipped or causal result. The surrounding case-study text explains the intended measurement and validation.

## Why it exists

I work at the intersection of customer-facing product, growth, and technical execution. The portfolio is designed to show the reasoning behind the work: how the problem was framed, which constraint mattered, what was kept out of scope, and how success would be measured.
