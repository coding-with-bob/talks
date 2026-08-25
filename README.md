# talks

Talks by felho, published as self-contained web decks.

Every deck in this repo is a static site: plain HTML, CSS and a little
JavaScript, with the fonts and images it needs bundled alongside it. No build
step, no framework, no network calls at view time. Open `index.html` for the
full deck (arrow keys or space to navigate, print to get a PDF), or open a
single slide from the deck's `slides/` folder.

The decks are generated from source in a private working repo and synced here.
Treat the files here as build output: fixes belong upstream.

## Talks

| Talk | Where | Deck |
|---|---|---|
| From Prompts to Convergence: My Journey Building Reliable Agentic Workflows | Craft Conference 2026 | [from-prompts-to-convergence/](https://coding-with-bob.github.io/talks/from-prompts-to-convergence/) |

## From Prompts to Convergence

Craft Conference 2026. What it takes to get from one-shot prompting to agentic
workflows that actually converge: bounding the work an agent is given, adding
review roles, making the surrounding workflow deterministic so the
nondeterministic part stays contained, and measuring the result with fitness
functions instead of impressions. The talk is built around Pairflow, the agent
harness the work produced.

Pairflow: https://github.com/felho/pairflow

## Fonts

The decks ship the Inter typeface (SIL Open Font License 1.1). Slides that were
originally projected in a system font are re-calibrated to Inter so the line
breaks match the delivered version; no non-redistributable font file is
published here.
