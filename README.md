# LIV_multiGRB

Reproducible public-data analysis of Lorentz invariance violation constraints from Fermi-LAT GRB photon timing.

## Associated manuscript

This repository supports the manuscript:

**Reproducible Multi-GRB Constraints on Lorentz Invariance Violation from Public Fermi-LAT Photon Timing**

## GRB sample

The analysis uses five Fermi-LAT GRBs with known redshift:

- GRB 080916C
- GRB 090510
- GRB 090902B
- GRB 090926A
- GRB 130427A

## Main result

Using a conservative 3-degree angular selection, the strongest linear LIV constraint is obtained from GRB 090510:

```text
E_QG,1 > 4.708 x 10^18 GeV
```text
E_QG,1 > 4.708 x 10^18 GeV
```

corresponding to approximately:

```text
0.386 E_Planck
```

No evidence for Lorentz invariance violation is found.

## Reproducibility

To reproduce the analysis, install the required packages and run the notebook:

```bash
pip install -r requirements.txt
jupyter notebook 01_multigrb_liv_analysis.ipynb
```
