---
title: LC-MS System — Standard Operating Procedure
description: Standard operating procedure for LC-MS system operation for peptide molecular weight determination and characterization.
tags:
  - equipment
  - sop
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "HowTo",
  "name": "LC-MS System — Standard Operating Procedure",
  "description": "Standard operating procedure for LC-MS system operation for peptide molecular weight determination.",
  "author": {
    "@type": "Organization",
    "name": "Zhangjiakou SENO Biotechnology Co., Ltd.",
    "url": "https://www.senopeptide.com"
  }
}
</script>

# LC-MS System — Standard Operating Procedure

## 1. Pre-Operation Checks

- [ ] Verify calibration status (mass accuracy check)
- [ ] Check N₂ gas supply (≥99.999%)
- [ ] Confirm source cleanliness
- [ ] Verify LC flow before connecting to MS
- [ ] Check waste line

## 2. System Calibration

1. Prepare calibration solution (NaI/CsI or commercial calibrant)
2. Infuse at 10 µL/min into source
3. Acquire calibration spectrum
4. Verify mass accuracy <5 ppm across range
5. Document calibration data

## 3. Sample Analysis

1. Dissolve peptide (1 – 10 µg/mL in 50% ACN/H₂O + 0.1% FA)
2. Infuse at 10 – 20 µL/min (direct infusion)
3. Acquire full scan spectrum (200 – 2000 m/z)
4. Deconvolute multiply charged envelope
5. Record observed monoisotopic mass

## 4. Data Interpretation

| Parameter | Criteria |
|---|---|
| Mass Match | ±0.5 Da of theoretical |
| Charge State Series | ≥3 observed charge states |
| Signal Intensity | ≥1×10⁵ counts |
| Adducts | Identify Na⁺, K⁺ adducts if present |

## 5. Shutdown

1. Flush source with 50% ACN/H₂O (5 min)
2. Switch MS to standby
3. Turn off N₂ supply
4. Log instrument usage
