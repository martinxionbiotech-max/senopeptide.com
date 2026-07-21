---
title: SPPS Solid-Phase Peptide Synthesis — Process Description
description: Detailed technical description of the Fmoc/tBu solid-phase peptide synthesis (SPPS) process at SENO Biotechnology — resin selection, coupling chemistry, deprotection, cleavage, and QC verification. Covers peptides up to 80 aa.
tags:
  - process
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "TechArticle",
  "headline": "SPPS Solid-Phase Peptide Synthesis — Process Description",
  "description": "Complete technical description of Fmoc/tBu SPPS process — resin selection through cleavage for peptides up to 80 amino acids.",
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

# SPPS Solid-Phase Peptide Synthesis — Process Description

!!! note "Official Process Documentation"
    This document describes the solid-phase peptide synthesis process used at SENO Biotechnology. For product inquiries or custom synthesis services, visit the [SENO Biotechnology Official Website](https://www.senopeptide.com).

## 1. Process Overview

Solid-phase peptide synthesis (SPPS), originally developed by Robert Bruce Merrifield (Nobel Prize in Chemistry, 1984), is the primary method for producing synthetic peptides at SENO Biotechnology. The process involves sequential assembly of protected amino acids on an insoluble polymer resin support, proceeding from the C-terminus to the N-terminus. After complete chain assembly, the peptide is cleaved from the resin with simultaneous side-chain deprotection.

General reaction sequence:
$$\text{Resin-OH} \xrightarrow{\text{Fmoc-AA-OH, Coupling}} \text{Resin-AA-Fmoc} \xrightarrow{\text{Piperidine}} \text{Resin-AA-NH}_2 \xrightarrow{\text{Repeat}} \text{Resin-Peptide} \xrightarrow{\text{TFA}} \text{H-Peptide-OH}$$

## 2. Fmoc/tBu Protection Strategy

The Fmoc (9-fluorenylmethoxycarbonyl) strategy is the primary protection scheme. The Fmoc group is base-labile (removed by piperidine), while side-chain protecting groups are acid-labile (removed by TFA during cleavage).

| Protection Group | Location | Removal Conditions | Mechanism | Absorbance |
|---|---|---|---|---|
| Fmoc | N-α-amino | 20% piperidine in DMF (5+10 min) | β-elimination | UV 301 nm |
| tBu | Side chain (Ser, Thr, Tyr, Asp, Glu) | TFA (95%, 2–4 h) | Acidolysis | — |
| Trt | Side chain (Cys, Asn, Gln, His) | TFA (1–5%) / TIS | Acidolysis | — |
| Boc | Side chain (Lys, Trp) | TFA (95%) | Acidolysis | — |
| Pbf | Side chain (Arg) | TFA (95%) | Acidolysis | — |

## 3. Resin Selection

| Resin Type | Functional Group | Linker Structure | Loading Range | Product | Application |
|---|---|---|---|---|---|
| Wang Resin | Hydroxymethyl | p-Alkoxybenzyl alcohol | 0.3 – 1.0 mmol/g | Peptide acid (C-terminal -OH) | Standard peptides |
| Rink Amide Resin | Amino | 4-(2,4-Dimethoxyphenyl-Fmoc-aminomethyl) | 0.3 – 0.8 mmol/g | Peptide amide (C-terminal -CONH₂) | Amide-terminated peptides |
| 2-Chlorotrityl Chloride Resin | Chloro | Trityl chloride | 0.5 – 1.5 mmol/g | Protected peptide fragments | Fragment condensation, side-chain protected peptides |

**Swelling volumes** (mL/g resin in DMF):
- Wang resin: 4 – 6 mL/g
- Rink Amide resin: 5 – 7 mL/g
- 2-CT Cl resin: 3 – 5 mL/g

## 4. Coupling Chemistry

### Reagent Selection Table

| Reagent | Excess (eq.) | Base (eq.) | Coupling Time | Temperature | Racemization | Cost Index | Best For |
|---|---|---|---|---|---|---|---|
| HBTU | 3 – 5 | DIPEA (6 – 10) | 30 – 60 min | 25 °C | Low | 1.0 (ref) | Standard couplings |
| HATU | 3 – 5 | DIPEA (6 – 10) | 15 – 30 min | 25 °C | Very low | 3.5 | Difficult sequences, hindered AAs |
| DIC + Oxyma Pure | 3 – 5 | — (in situ) | 30 – 60 min | 25 – 40 °C | Lowest | 0.8 | His, Cys, low-epimerization |
| DIC + HOBt | 3 – 5 | — (in situ) | 30 – 60 min | 25 °C | Low | 0.7 | General purpose |

### Kaiser Test (Ninhydrin) Protocol

| Component | Preparation |
|---|---|
| Reagent A | 40 g phenol dissolved in 10 mL ethanol |
| Reagent B | 65 mg KCN in 100 mL H₂O; dilute 2 mL to 100 mL with pyridine |
| Reagent C | 500 mg ninhydrin in 10 mL ethanol |

**Procedure:** Transfer 5 – 10 resin beads to test tube → Add 3 drops each A, B, C → Heat 100 °C × 5 min → Observe color.

| Color | Interpretation | Action |
|---|---|---|
| Pale yellow / colorless | No free amines | Coupling complete → proceed |
| Blue / purple | Free amines present | Coupling incomplete → repeat coupling with fresh reagents |

## 5. Stepwise Process Parameters

| Step | Solvent/Reagent | Volume (mL/g resin) | Time | Temperature |
|---|---|---|---|---|
| Swelling | DMF | 10 | 30 – 60 min | 25 °C |
| Deprotection 1 | 20% Piperidine/DMF | 10 | 5 min | 25 °C |
| Deprotection 2 | 20% Piperidine/DMF | 10 | 10 min | 25 °C |
| Wash | DMF | 10 | 5 × 3 min | 25 °C |
| AA activation | Fmoc-AA-OH + HBTU + DIPEA in DMF | 5 | 2 – 5 min | 25 °C |
| Coupling | Activated solution | 5 | 30 – 60 min | 25 – 40 °C |
| Wash | DMF | 10 | 5 × 3 min | 25 °C |
| Kaiser test | — | — | 5 min (100 °C) | — |
| Capping (if used) | Ac₂O/DIPEA/DMF (1:1:8) | 5 | 10 min | 25 °C |
| Wash | DCM | 10 | 3 × 3 min | 25 °C |

## 6. Cleavage and Global Deprotection

| Standard Cocktail | Proportion | Role |
|---|---|---|
| Trifluoroacetic acid (TFA) | 95% v/v | Cleavage + side-chain deprotection |
| Triisopropylsilane (TIS) | 2.5% v/v | Carbocation scavenger |
| Deionized Water | 2.5% v/v | Carbocation scavenger |

**Conditions:** 10 mL cocktail per gram resin, 2 – 4 h at 25 °C (stirring or agitation).

**Modified cocktails for sensitive sequences:**
- **Cys-containing:** Add 2.5% EDT (ethanedithiol)
- **Met-containing:** Add 1% DMS (dimethyl sulfide)
- **Trp-containing:** Add 2.5% EDT to prevent Trp oxidation

## 7. Precipitation and Isolation

| Step | Reagent | Ratio | Temperature | Time |
|---|---|---|---|---|
| Precipitation | Cold diethyl ether | 10:1 (ether:cleavage sol.) | −20 °C | 15 min |
| Centrifugation | — | 3000 – 4000 × g | 4 °C | 10 – 15 min |
| Wash 1 | Cold diethyl ether | 20 mL | −20 °C | Decant |
| Wash 2 | Cold diethyl ether | 20 mL | −20 °C | Decant |
| Drying | N₂ stream or vacuum | — | 25 °C | 30 min – 2 h |

## 8. Crude Peptide Quality Assessment

| Parameter | Method | Acceptance |
|---|---|---|
| Crude yield | Gravimetric | Within ±10% of theoretical |
| Crude purity | Analytical HPLC (220 nm) | Report value (typically 60 – 85%) |
| Identity | ESI-MS | Within ±0.5 Da of theoretical mass |
| Appearance | Visual | White to off-white powder |
