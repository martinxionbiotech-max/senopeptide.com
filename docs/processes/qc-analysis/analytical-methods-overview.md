---
title: Analytical Methods Overview — Quality Control and Characterization
description: Comprehensive overview of analytical methods for peptide quality control at SENO Biotechnology — HPLC purity analysis, ESI-MS, Karl Fischer, GC residual solvents, LAL endotoxin, amino acid analysis, and peptide content determination.
tags:
  - process
  - quality
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "TechArticle",
  "headline": "Analytical Methods Overview — Quality Control and Characterization",
  "description": "Comprehensive overview of analytical methods for peptide QC — HPLC purity, ESI-MS, Karl Fischer, GC, LAL, amino acid analysis.",
  "author": {
    "@type": "Organization",
    "name": "Zhangjiakou SENO Biotechnology Co., Ltd.",
    "url": "https://www.senopeptide.com"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Zhangjiakou SENO Biotechnology Co., Ltd.",
    "url": "https://www.senopeptide.com"
  }
}
</script>

# Analytical Methods Overview — Quality Control and Characterization

!!! note "Official QC Methods Reference"
    This document provides a comprehensive overview of analytical methods used for peptide quality control and characterization at SENO Biotechnology. For commercial inquiries, visit the [SENO Biotechnology Official Website](https://www.senopeptide.com).

## 1. HPLC Purity Analysis (Reversed-Phase)

### Standard Method Parameters

| Parameter | Setting |
|---|---|
| Stationary Phase | C18, 150 × 4.6 mm ID, 3 – 5 µm particle size, 100 Å pore |
| Mobile Phase A | 0.1% (v/v) TFA in H₂O |
| Mobile Phase B | 0.1% (v/v) TFA in acetonitrile |
| Gradient | 5% B → 65% B over 25 min |
| Flow Rate | 1.0 mL/min |
| Detection | UV absorbance at 220 nm (peptide bond), 280 nm (aromatic residues) |
| Injection Volume | 5 – 20 µg peptide (10 – 20 µL of 0.5 – 1.0 mg/mL solution) |
| Column Temperature | 25 °C (controlled) |
| Run Time | 30 min (including re-equilibration) |
| Data Acquisition | 0 – 25 min gradient + 5 min re-equilibration |

### Purity Calculation

$$\text{Purity (\%)} = \frac{\text{Peak area of target peptide}}{\sum{\text{All integrated peak areas}}} \times 100$$

### Reporting Thresholds

| Peak Area (% of total) | Reporting Requirement |
|---|---|
| ≥0.05% | Report and identify if possible |
| 0.05 – 0.5% | Report as minor impurity |
| <0.05% | Report as trace (below reporting threshold) |

## 2. Mass Spectrometry (ESI-MS)

| Parameter | Setting |
|---|---|
| Ionization Mode | Electrospray positive (ESI+) |
| Scan Range | 200 – 2000 m/z |
| Scan Time | 1 s |
| Sample Concentration | 1 – 10 µg/mL in 50% ACN/H₂O + 0.1% formic acid |
| Infusion Rate | 10 – 20 µL/min (direct infusion) |
| Capillary Voltage | 3.5 – 4.5 kV |
| Desolvation Temperature | 250 – 350 °C |
| Cone Voltage | 20 – 60 V (optimized per peptide) |

### Mass Interpretation

| Observed Species | m/z Value | Neutral Mass Calculation |
|---|---|---|
| [M+H]⁺ | m/z₁ | M = (m/z₁ − 1) × 1 |
| [M+2H]²⁺ | m/z₂ | M = (m/z₂ × 2) − 2 |
| [M+3H]³⁺ | m/z₃ | M = (m/z₃ × 3) − 3 |
| [M+Na]⁺ | m/z₍M+Na₎ | Confirm by +22.0 Da shift |

## 3. Water Content (Karl Fischer Coulometric Titration)

| Parameter | Setting |
|---|---|
| Method | Coulometric (generation of I₂) |
| Sample Size | 5 – 50 mg peptide (weighed accurately) |
| Anode Solution | Hydranal Coulomat AG |
| Cathode Solution | Hydranal Coulomat CG |
| Extraction Time | 2 – 5 min with stirring |
| Acceptance (Bulk) | ≤1.0% (w/w) |
| Acceptance (Formulated) | ≤0.5% (w/w) |

## 4. Residual Solvents (GC-FID Headspace)

| Parameter | Setting |
|---|---|
| Column | DB-624 or equivalent (30 m × 0.32 mm × 1.8 µm) |
| Detector | Flame ionization (FID) |
| Injection | Headspace, 80 °C for 30 min equilibration |
| Carrier Gas | Helium, 2.0 mL/min |
| Oven Program | 40 °C (5 min) → 10 °C/min → 200 °C (5 min) |
| Target Analytes | Acetonitrile, TFA, methanol, ethanol, DMF, DCM, diethyl ether, 2-methyl-2-butene |

### ICH Q3C Limits

| Solvent | Class | Limit (ppm) |
|---|---|---|
| Acetonitrile | Class 2 | 410 |
| Methanol | Class 2 | 3000 |
| DCM | Class 2 | 600 |
| DMF | Class 2 | 880 |
| Ethanol | Class 3 | 5000 |
| TFA | Not classified | Report |

## 5. Endotoxin Testing (LAL)

| Parameter | Setting |
|---|---|
| Method | Limulus Amebocyte Lysate (gel-clot or chromogenic) |
| Sample Preparation | Dissolve in LAL reagent water (LRW) |
| pH Range | 6.0 – 8.0 (adjust if necessary) |
| Inhibition/Enhancement | Spike recovery 50 – 200% |
| Acceptance (Research Grade) | <0.05 EU/mg |
| Acceptance (High-Purity) | <0.01 EU/mg |

## 6. Peptide Content Determination

### UV Spectrophotometric Method

$$\text{Content (\%)} = \frac{A_{280} \times \text{Dilution factor}}{\varepsilon \times \text{Sample weight (mg)}} \times 100$$

Where ε (molar extinction coefficient at 280 nm) is calculated from:
- Tryptophan: ε = 5690 M⁻¹cm⁻¹
- Tyrosine: ε = 1280 M⁻¹cm⁻¹
- Cystine: ε = 120 M⁻¹cm⁻¹

### Alternative: Amino Acid Analysis

- Hydrolysis: 6 N HCl, 110 °C, 24 h
- Derivatization: AccQ-Tag, OPA/FMOC, or ninhydrin
- Quantification: HPLC or UPLC with UV or fluorescence detection
- Correction factors applied for acid-labile residues (Ser, Thr, Met)

## 7. Optional Characterization Methods

| Method | Purpose | When Used |
|---|---|---|
| SEC-HPLC | Aggregation/dimer detection | Long peptides, stored solutions |
| Ion-exchange chromatography | Charge variant analysis | Peptide salts, counterion determination |
| HILIC | Hydrophilic impurity detection | Very polar peptides |
| CD spectroscopy | Secondary structure assessment | Conformational studies |
| DSC | Thermal stability | Formulation development |
| NMR (1D, 2D) | Structural confirmation | Advanced characterization (>95% purity) |
