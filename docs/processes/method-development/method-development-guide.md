---
title: Analytical Method Development Guide — HPLC for Peptides
description: Guide for developing and optimizing analytical HPLC methods for peptide purity analysis at SENO Biotechnology — column selection, mobile phase optimization, gradient design, and troubleshooting.
tags:
  - process
---

<script type="application/ld+json">
{"@context":"https://schema.org","@type":"TechArticle","headline":"Analytical Method Development Guide — HPLC for Peptides"}
</script>

# Analytical Method Development Guide — HPLC for Peptides

## 1. Column Selection Guide

| Peptide Property | Recommended Column | Particle Size | Pore Size |
|---|---|---|---|
| MW <2000 Da, hydrophilic | C18 | 3 – 5 µm | 100 Å |
| MW 2000 – 5000 Da | C18 or C8 | 3 – 5 µm | 100 – 300 Å |
| MW >5000 Da, hydrophobic | C4 or C8 | 3 – 5 µm | 300 Å |
| Very basic peptides (pI >9) | C18 + ion pairing | 3 – 5 µm | 100 Å |

## 2. Mobile Phase Optimization

| Modifier | Concentration | UV Cutoff | Application |
|---|---|---|---|
| TFA | 0.05 – 0.1% | 210 nm | Standard, good peak shape |
| Formic acid | 0.1% | 210 nm | MS-compatible |
| NH₄HCO₃ | 10 – 20 mM | 200 nm | MS-compatible, volatile |
| NH₄OAc | 10 – 20 mM | 210 nm | MS-compatible |

## 3. Gradient Design Strategy

| Step | Objective |
|---|---|
| Start at 5% B | Ensure peptide retains; wash non-retained |
| Linear gradient 5→65% B over 20 min | Standard separation |
| Adjust slope based on first run | Target RT 12 – 18 min |
| Hold at 95% B 5 min | Column wash |
| Return to 5% B, 5 min | Re-equilibration |

## 4. Troubleshooting

| Issue | Cause | Solution |
|---|---|---|
| Poor peak shape | Column mismatch | Try C8 or C4 |
| Broad peaks | Overload | Reduce injection mass |
| Shouldering | Impurity co-elution | Reduce gradient slope |
| Retention drift | Column equilibration | Increase equilibration time to 10 min |
