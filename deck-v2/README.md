# DeFi Loans Workshop deck, V2

Source files of the V2 slide deck published at https://claude.ai/artifact/V5ZwB3Um4DyWLTLYi8mKnq
(artifact version 7, saved 2026-11-19). V1 is in `../deck/`.

Event name: "DeFi loans from collateralized to uncollateralized". V2 has two parts, 60 minutes in all:

- **Part 1, 40 minutes: collateralized loans.** Mortgages and Lombard loans, how a DeFi loan works, a live Aave V3 demo, Morpho and Aave v4, staying alive, cashing out, tips and hacks.
- **Part 2, 20 minutes: uncollateralized loans.** Unlloo crowd loans, run as a discussion: an opening question, an exercise, "Discuss" prompts on each slide and a closing feedback round.

Files:

- `deck.json`: the index (slide order, sections, cover, typeface).
- `slides/<id>.html`: one slide per file, in the order `deck.json` gives. Each `<section>` is a 1920×1080 slide with inline styles; the `<aside>` at the end holds the speaker notes, which start with the minute the slide begins.

New in V2: `agenda` (two-part plan), `q-lend` (opening question) and `feedback` (closing round). Dropped from V1: `flash-loans`, `crowd-borrow`, `crowd-lend`. The sell-vs-borrow and tax slides use a generic tax example instead of Slovak rates.

Design: the Unlloo website look, per https://www.unlloo.com/ai-design/SKILL.md.

Open placeholders on the last slide: Signal group link or QR, Lightning address.
