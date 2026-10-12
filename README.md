<!-- solve-problem:bab2f6af-6ac7-4ff2-99e7-43c20a624fd3 -->
# ALGO-000019: Cell-probe lower bounds for static data structures

A [Tangle Solve problem](https://solve.tangle.tools/problems/bab2f6af-6ac7-4ff2-99e7-43c20a624fd3).

Source verification label: unverified. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000019: Cell-probe lower bounds for static data structures
- **Subfield:** streaming, data structures, online
- **Open:** Prove t_q = Ω(log^2 n / log w) type optimal lower bounds for natural static problems (3SUM indexing, adjacency in nnz o(n^2) graphs, predecessor) in the cell-probe model with polynomial space.
- **Status:** Open; best lower bounds for predecessor are Ω(log n / log(w/n)) (Pătraşcu–Thorup 2006) matching van Emde Boas-type upper bounds, but for many listing/reporting problems only log^Ω(1) bounds exist. Larsen's cell-sampling technique gives Ω(log^2 n / log(Sw/n)) for some range problems (2012).
- **Type:** theory
- **Why:** A t_q lower bound beyond log^2 n for any explicit problem would be a breakthrough comparable to circuit lower bounds.
- **Key works:** K. Green Larsen, "The cell probe complexity of dynamic range counting", STOC 2012 (arXiv:1203.5135); M. Pătraşcu, M. Thorup, "Time-space trade-offs for predecessor search", STOC 2006
- **Related:** dynamic connectivity lower bound
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "id": "ALGO-000019",
  "label": "unverified",
  "origin": "sourced",
  "source_kind": "manual",
  "triage": "clean",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/bab2f6af-6ac7-4ff2-99e7-43c20a624fd3?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000019.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000019)
