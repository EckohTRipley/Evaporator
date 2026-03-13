# EVAPORATOR

**A behavioral analysis and redirection tool based on the Psychological Least-Discrepancy Principle (PLDP)**

---

## What is this?

EVAPORATOR predicts and redirects human action selection using the PLDP formula:

```
ΔH_total(a,O | H,H*,w,L,R) = w_C|C'(a,O)−C*| + w_A|A'(a,O)−A*| + w_S|S'(a,O)−S*| + L(a,O) + cost(a,O,R)
a*, O* = argmin
```

Given a description of a person's situation, EVAPORATOR estimates their psychological state (H), ideal state (H*), learned biases (L), and resource level (R) — then calculates which action they are most likely to take, and what intervention would redirect that action.

---

## How to use

1. Open `evaporator_v06.html` in any modern browser (Chrome recommended)
2. Enter your [Anthropic API key](https://console.anthropic.com) — stored in memory only, never transmitted elsewhere
3. Describe the subject in the input field
4. Run **ANALYZE** (Phase 1) to predict action and target
5. Run **REDIRECT** (Phase 2) to find the optimal intervention

No installation. No server. Single file.

---

## Theoretical foundation

EVAPORATOR is the practical implementation of the Psychological Least-Discrepancy Principle.

**Published works (open access):**

| Paper | DOI |
|-------|-----|
| The Psychological Least-Discrepancy Principle (PLDP) | [10.5281/zenodo.18497776](https://doi.org/10.5281/zenodo.18497776) |
| EVAPORATOR — Prototype Design Specification | [10.5281/zenodo.18793897](https://doi.org/10.5281/zenodo.18793897) |
| The Moving Structure | [10.5281/zenodo.18912586](https://doi.org/10.5281/zenodo.18912586) |

**Part of Project Ozymandias** by Eckoh T. Ripley (Independent Researcher)

---

## License

GNU Affero General Public License v3.0

Any commercial use requires full source disclosure. Monopolization is structurally impossible.
