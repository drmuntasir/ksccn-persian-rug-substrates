# KSCCN: Persian-Rug Substrates and Multi-Sector Curvature

Two-volume Knowledge Synthesis & Critical Commentary Notes (KSCCN) series.

**Author:** Dr Syed Muntasir Mamun, PhD, PGD (Oxon)  
**ORCID:** [0000-0001-6845-2853](https://orcid.org/0000-0001-6845-2853)

## Volumes

### Volume I — 30 August 2026
**Persian-Rug Substrates and Multi-Sector Curvature: An Anatomical Review of the Coming Substrate Crisis in Quantum Computing**

Anatomical review of J. Harlow, *The Coming Substrate Crisis in Quantum Computing* (29 August 2026). Accepts the theme that continuum single-sector holonomy is an atlas, not the manifold. Rejects the SU(0)–SU(7) lexicon as public geometry. Constructs a Persian-rug ontology: themed sectors with occupancy ledger and rug holonomy interrupted by wall operators.

- Generator: `build_ksccn_paper.py`
- Output: `KSCCN_Persian_Rug_Substrates_Mamun_2026.pdf` (rebuild locally)

### Volume II — 31 August 2026
**A Toy Rug: Three Sectors, Two Themes, and a Multifractal Error Measure on a Spin Chain**

Exact diagonalisation of a six-site XXZ chain. Three Hamiltonian sectors, two themes (even parity / full space), triangular control loop. Piecewise rug path versus interpolated single chart versus averaged Lindblad.

Headline residuals against the interpolated chart:

| knot angle ε | F vs smooth | ΔF |
|---:|---:|---:|
| 0.00 (identity quench) | 0.980 | 0.020 |
| 0.10 | 0.920 | 0.080 |
| 0.20 | 0.751 | 0.249 |
| 0.40 | 0.294 | 0.706 |

Legal knots preserve even-parity weight. A detector wall drops even-parity weight to 0.882. At N = 6, d2 does not separate sectors; gap and echo do.

- Computation: `toy_rug_compute.py`
- Results: `data/toy_rug_results.json`, `data/toy_rug_scan.json`
- Generator: `build_ksccn_vol2.py`
- Output: `KSCCN_Toy_Rug_Volume_II_Mamun_2026.pdf` (rebuild locally)

## Rebuild

```bash
python3 toy_rug_compute.py
python3 build_ksccn_paper.py
python3 build_ksccn_vol2.py
```

Requires NumPy and ReportLab, plus DejaVu fonts.

## Citation

Mamun, S. M. (2026) ‘Persian-rug substrates and multi-sector curvature: an anatomical review of the coming substrate crisis in quantum computing’, *KSCCN*, Vol. I, 30 August.

Mamun, S. M. (2026) ‘A toy rug: three sectors, two themes, and a multifractal error measure on a spin chain’, *KSCCN*, Vol. II, 31 August.

## Licence

© 2026 Syed Muntasir Mamun. Circulate with attribution.
