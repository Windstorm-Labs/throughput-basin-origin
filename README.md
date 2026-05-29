# Paper 7: The Throughput Basin Origin — Experiments & Code

**Four Orthogonal Experiments on Whether Serial Decoding Convergence Is Architectural, Thermodynamic, or Data-Driven**

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.19498582-blue)](https://doi.org/10.5281/zenodo.19498582)
[![License: MIT](https://img.shields.io/badge/Code-MIT-green)](https://opensource.org/licenses/MIT)

---

## Canonical Repository

All code, data, results, the manuscript PDF, and the adversarial review now live at:

**→ [Windstorm-Institute/throughput-basin-origin](https://github.com/Windstorm-Institute/throughput-basin-origin)**

This Labs mirror is maintained for org-level consistency. The canonical repo above has the paper (v1.6), the internal adversarial review, the Grand Slam supplementary materials, all CSVs, paper7.1 follow-up data, and the Paper 8 preliminary scripts.

**Companion article:** [windstorminstitute.org/articles/throughput-basin-origin.html](https://windstorminstitute.org/articles/throughput-basin-origin.html) · **Zenodo (concept DOI, always-latest):** [10.5281/zenodo.19498582](https://doi.org/10.5281/zenodo.19498582) · **v1.6:** [10.5281/zenodo.19672654](https://doi.org/10.5281/zenodo.19672654)

---

## Hardware (when this paper's experiments were originally run)

- **GPU:** Current-generation Nvidia GPU (32 GB VRAM, CUDA)
- **CPU:** Intel Core Ultra 9 285K (24 cores)
- **RAM:** 256 GB
- **OS:** Ubuntu 24.04, Python 3.12, PyTorch 2.11
- **Quantization:** bitsandbytes 0.49.2 (with CUDA 13.0 library path fix)

The seven-round verification journey detailed in v1.6 §1.3-3.12: ~14.5 hours autonomous Sonnet 4.5 execution (Exps 1-6), ~10 hours parallel Opus 4.6 follow-ups (B1/B4/R6/R9/stats), ~16 hours automated nohup R5 + intermediate-entropy runs, plus the Grand Slam round. Full per-round breakdown in the canonical paper's acknowledgments.

---

## Discuss this code

- **Bug, reproduction failure, or unexpected output?** → [Open an Issue](../../issues)
- **Q&A — version compatibility, hardware, generalization to other inputs?** → [Start a Discussion](../../discussions)
- **Discuss the paper itself** → [Comments on the website article](https://windstorminstitute.org/articles/throughput-basin-origin.html#comments) or [Issues on the Institute repo](https://github.com/Windstorm-Institute/throughput-basin-origin/issues)

---

---

## The Windstorm Institute — Two Research Tracks

### Track 1 — The Throughput Basin · 9 papers (Papers 1–9 globally; 1st through 9th in this track; arc complete)

| # | Paper | DOI |
|---|-------|-----|
| 1 | [The Fons Constraint](https://github.com/Windstorm-Institute/fons-constraint) | [10.5281/zenodo.19274048](https://doi.org/10.5281/zenodo.19274048) |
| 2 | [The Receiver-Limited Floor](https://github.com/Windstorm-Institute/receiver-limited-floor) | [10.5281/zenodo.19322973](https://doi.org/10.5281/zenodo.19322973) |
| 3 | [The Throughput Basin](https://github.com/Windstorm-Institute/throughput-basin) | [10.5281/zenodo.19323194](https://doi.org/10.5281/zenodo.19323194) |
| 4 | [The Serial Decoding Basin τ](https://github.com/Windstorm-Institute/serial-decoding-basin) | [10.5281/zenodo.19323423](https://doi.org/10.5281/zenodo.19323423) |
| 5 | [The Dissipative Decoder](https://github.com/Windstorm-Institute/dissipative-decoder) | [10.5281/zenodo.19433048](https://doi.org/10.5281/zenodo.19433048) |
| 6 | [The Inherited Constraint](https://github.com/Windstorm-Institute/inherited-constraint) | [10.5281/zenodo.19432911](https://doi.org/10.5281/zenodo.19432911) |
| 7 | [The Throughput Basin Origin](https://github.com/Windstorm-Institute/throughput-basin-origin) *(this paper)* | [10.5281/zenodo.19498582](https://doi.org/10.5281/zenodo.19498582) |
| 8 | [The Vision Basin](https://github.com/Windstorm-Institute/vision-basin) | [10.5281/zenodo.19672827](https://doi.org/10.5281/zenodo.19672827) |
| 9 | [The Hardware Basin](https://github.com/Windstorm-Institute/hardware-basin) | [10.5281/zenodo.19672921](https://doi.org/10.5281/zenodo.19672921) |

### Track 2 — Entropic Bounds in Analog Systems · 7 papers (Papers 10–16; line of inquiry active)

| # | Paper | DOI |
|---|-------|-----|
| 10 | [Phonon Extraction Bound (BEC Analog Gravity)](https://github.com/Windstorm-Institute/phonon-extraction-bound) | [10.5281/zenodo.20014391](https://doi.org/10.5281/zenodo.20014391) |
| 11 | [Gravitational Entropy Escrow](https://github.com/Windstorm-Institute/gravitational-entropy-escrow) | [10.5281/zenodo.20032023](https://doi.org/10.5281/zenodo.20032023) |
| 12 | [C8 Clarification Note](https://github.com/Windstorm-Institute/c8-clarification-note) | [10.5281/zenodo.20041992](https://doi.org/10.5281/zenodo.20041992) |
| 13 | [Lattice QFT Test of the Static Escrow Postulate](https://github.com/Windstorm-Institute/lattice-qft-test) *(4th in track; supplement to Paper 11)* | [10.5281/zenodo.20057538](https://doi.org/10.5281/zenodo.20057538) |
| 14 | [Spacetime as Escrow Bookkeeping](https://github.com/Windstorm-Institute/escrow-spacetime) *(5th in track; translation of standard GR results into the escrow vocabulary; companion to Paper 11)* | [10.5281/zenodo.20126091](https://doi.org/10.5281/zenodo.20126091) |
| 15 | [The 𝒩<sub>esc</sub> Recipe](https://github.com/Windstorm-Institute/nesc-recipe) *(6th in track; formalizes 𝒩<sub>esc</sub> as a cross-regime function; continuation of Paper 14)* | [10.5281/zenodo.20145106](https://doi.org/10.5281/zenodo.20145106) |
| 16 | [The Compton Corollary](https://github.com/Windstorm-Institute/compton-corollary) *(7th in track; short Bekenstein observation at the Compton scale; uses 𝒩<sub>esc</sub> notation only, escrow recipe not invoked)* | [10.5281/zenodo.20163451](https://doi.org/10.5281/zenodo.20163451) |

**Website:** [windstorminstitute.org](https://windstorminstitute.org)

---

*Code: MIT License · Data: CC BY 4.0*
