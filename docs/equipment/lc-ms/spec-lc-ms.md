---
title: LC-MS System — Technical Specification
description: Technical specification for liquid chromatography-mass spectrometry (LC-MS) systems at SENO Biotechnology — ESI ionization, 50-3000 m/z range, <5 ppm mass accuracy, for peptide molecular weight verification.
tags:
  - equipment
  - specification
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "TechArticle",
  "headline": "LC-MS System — Technical Specification",
  "description": "Technical specification for LC-MS systems — ESI+/- ionization, 50-3000 m/z range, <5 ppm mass accuracy.",
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

# LC-MS System — Technical Specification

## 1. Mass Spectrometer Specifications

| Parameter | Specification |
|---|---|
| Mass Range (m/z) | 50 – 3000 |
| Resolution | ≥10,000 (FWHM at m/z 1000) |
| Mass Accuracy | <5 ppm RMS (external calibration); <2 ppm (external with lock mass) |
| Mass Stability | ±0.1 Da over 24 h (ambient conditions ±2 °C) |
| Scan Speed | ≤10,000 Da/s |
| Dynamic Range | 4 × 10⁴ (4 orders of magnitude) |
| Detector | Microchannel plate (MCP) or electron multiplier |

## 2. ESI Source Parameters

| Parameter | Positive Mode | Negative Mode |
|---|---|---|
| Capillary Voltage | 3.5 – 4.5 kV | 2.5 – 3.5 kV |
| Cone Voltage | 20 – 60 V | 20 – 60 V |
| Source Temperature | 100 – 150 °C | 100 – 150 °C |
| Desolvation Temperature | 250 – 350 °C | 250 – 350 °C |
| Desolvation Gas (N₂) | 500 – 800 L/h | 500 – 800 L/h |
| Cone Gas (N₂) | 50 – 100 L/h | 50 – 100 L/h |
| Nebulizer Gas | N₂, 7 bar | N₂, 7 bar |

## 3. LC Component Specifications

| Parameter | Specification |
|---|---|
| Flow Rate | 0.1 – 2.0 mL/min (splitting to MS) |
| Max Pressure | 6000 psi |
| Solvent Delivery | Binary or quaternary |
| Detector (inline) | DAD or UV (optional, for LC-MS) |
| Column | C18, 2.1 × 50 – 100 mm, 1.7 – 3.5 µm |

## 4. System Performance

| Test | Parameter | Acceptance |
|---|---|---|
| Sensitivity (ESI+) | 1 pg reserpine (609 m/z) | S/N >100:1 |
| Mass Accuracy | External calibration | <5 ppm over full range |
| Isotopic Distribution | Leucine enkephalin (556 m/z) | >95% match to theoretical |
