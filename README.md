# Dormant LLM Puzzle — Interactive Circuit Dashboard

Interactive visualization of MoE expert activation cascades for backdoor triggers discovered in DeepSeek V3 671B models.

Part of the [Dormant LLM Puzzle](https://dormant-puzzle.janestreet.com/) submission by T. Mancino.

## Usage

Open `index.html` in any browser — self-contained, no server required.

Or visit the hosted version: https://tmancino.github.io/dormant-dashboard/

## What This Shows

- Force-directed graph of expert activation cascades across 59 MoE layers
- Click any trigger to highlight its cascade pathway
- Click any expert node for cross-model activation data and base model routing affinity
- Filter by model (M1/M2/M3) or pathway type
- Nodes sized by gate logit delta, colored by activation strength
