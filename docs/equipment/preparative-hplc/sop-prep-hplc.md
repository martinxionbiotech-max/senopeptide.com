---
title: Preparative HPLC System — Standard Operating Procedure
description: Standard operating procedure for preparative HPLC system operation at SENO Biotechnology — equilibration, sample loading, gradient purification, fraction analysis, and column cleaning/storage.
tags:
  - equipment
  - sop
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "HowTo",
  "name": "Preparative HPLC System — Standard Operating Procedure",
  "description": "Standard operating procedure for preparative HPLC system — equilibration through column storage.",
  "author": {
    "@type": "Organization",
    "name": "Zhangjiakou SENO Biotechnology Co., Ltd.",
    "url": "https://www.senopeptide.com"
  }
}
</script>

# Preparative HPLC System — Standard Operating Procedure

!!! note "Official SOP"
    This standard operating procedure governs preparative HPLC system operation. For product inquiries, visit the [SENO Biotechnology Official Website](https://www.senopeptide.com).

## 1. Pre-Operation Safety

- Wear solvent-resistant gloves (Viton or nitrile) and safety goggles
- Verify adequate ventilation or connect to exhaust
- Confirm waste container has ≥50% empty capacity
- Inspect all tubing connections for leaks

## 2. Pre-Operation Checks

| Item | Check | Acceptable |
|---|---|---|
| Mobile phase A | H₂O + 0.1% TFA (filtered 0.22 µm) | Prepared fresh, labeled |
| Mobile phase B | ACN + 0.1% TFA (filtered 0.22 µm) | Prepared fresh, labeled |
| System pressure test | Pump at 10 mL/min, 50% B, monitor 5 min | <5% pressure fluctuation |
| UV lamp | Warm up ≥15 min before use | Baseline drift <0.5 mAU/min |
| Column condition | Visual inspection (no end-fitting leakage) | Dry exterior |
| Waste container | Volume check | ≥50% empty |
| Fraction collector | Tube/bottle positions confirmed | Set collection mode |

## 3. System Equilibration

1. Purge pump heads with mobile phase (5 mL/min each head, 2 min)
2. Set flow rate to 10 mL/min at initial %B (typically 5% B)
3. Allow column to equilibrate for 3 – 5 column volumes
4. Monitor UV baseline at 220 nm (peptide bond) and 280 nm (aromatic)
5. Accept equilibration when baseline drift <0.5 mAU/min over 2 min
6. Record equilibration parameters in batch record

## 4. Sample Preparation

1. Weigh crude peptide (record mass)
2. Dissolve in mobile phase A or ACN/H₂O mixture (10 – 50 mg/mL typical)
3. Filter through 0.45 µm PTFE syringe filter into clean vial
4. Record sample concentration and volume
5. Load sample into injection loop using Luer-lock syringe

## 5. Gradient Purification Method

| Step | Time (min) | Flow (mL/min) | %B | Curve | Purpose |
|---|---|---|---|---|---|
| Equilibration | 0 – 5 | 50 | 5 | — | Ready column |
| Injection | 0 (event) | 50 | 5 | — | Inject sample |
| Gradient 1 | 0 – 5 | 50 | 5 → 20 | Linear | Wash non-retained |
| Gradient 2 | 5 – 45 | 50 | 20 → 55 | Linear | Elute target peptide |
| Gradient 3 | 45 – 50 | 50 | 55 → 95 | Linear | Column wash |
| Hold | 50 – 55 | 50 | 95 | Isocratic | Elute strongly retained |
| Re-equilibration | 55 – 65 | 50 | 95 → 5 | Linear | Return to start |

## 6. Fraction Collection Criteria

1. Set collection threshold: **≥50 mAU** at 220 nm (adjust for concentrated samples)
2. Collect peak apex ±0.5 min for primary fraction
3. Collect leading and trailing shoulders separately (may contain impurities)
4. Label each fraction with:
   - Batch number
   - Fraction number
   - Collection time window
   - UV absorbance at apex

## 7. Post-Run Fraction Analysis

1. Transfer 5 – 20 µL from each fraction to auto-sampler vial
2. Analyze by analytical HPLC (see [Analytical HPLC SOP](../analytical-hplc/sop-analytical-hplc.md))
3. Pool fractions meeting purity threshold (≥95% for standard grade)
4. Record pooled fraction volume, concentration (by UV), and total peptide mass

## 8. Column Cleaning and Storage

| Step | Solvent | Volume | Purpose |
|---|---|---|---|
| Post-run wash | 100% ACN | 3 CV (50 mL/min) | Remove hydrophobic impurities |
| Intermediate | 70% ACN / 30% H₂O | 3 CV | Transition |
| Storage | 80% ACN / 20% H₂O | — | Prevent microbial growth |
