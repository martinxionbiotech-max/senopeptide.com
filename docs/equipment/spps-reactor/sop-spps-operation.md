---
title: SPPS Synthesis Reactor — Standard Operating Procedure
description: Standard operating procedure for SPPS reactor operation at SENO Biotechnology — pre-startup checks, Fmoc synthesis cycle execution, Kaiser test monitoring, TFA cleavage procedure, and cleaning/decontamination protocols.
tags:
  - equipment
  - sop
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "HowTo",
  "name": "SPPS Synthesis Reactor — Standard Operating Procedure",
  "description": "Standard operating procedure for solid-phase peptide synthesis reactor — pre-startup through cleaning.",
  "author": {
    "@type": "Organization",
    "name": "Zhangjiakou SENO Biotechnology Co., Ltd.",
    "url": "https://www.senopeptide.com"
  }
}
</script>

# SPPS Synthesis Reactor — Standard Operating Procedure

!!! note "Official SOP"
    This standard operating procedure governs operation of SPPS synthesis reactors. For product inquiries, visit the [SENO Biotechnology Official Website](https://www.senopeptide.com).

## 1. Safety Precautions

| Hazard | Source | Required PPE | Engineering Controls |
|---|---|---|---|
| Chemical exposure | TFA, piperidine, DMF, DCM | Nitrile gloves (double for TFA), safety goggles, lab coat, chemical apron | Fume hood required for TFA handling |
| TFA burns | Concentrated acid | Acid-resistant gloves (neoprene or butyl) over nitrile, face shield | Dedicated TFA station with spill tray |
| N₂ asphyxiation | Compressed N₂ supply | — | Adequate room ventilation, O₂ monitor recommended |
| Piperidine toxicity | Deprotection reagent | Nitrile gloves, goggles | Closed system transfer |
| Flammable solvents | DCM, ether, ACN | Flame-resistant lab coat | No open flames, grounded containers |

## 2. Pre-Operation Check List

| Item | Check | Acceptable |
|---|---|---|
| N₂ supply | Pressure gauge reading | 2.0 – 4.0 bar |
| N₂ purity | Certificate verified | ≥99.999% |
| Reagent vessels | Sufficient volume for synthesis | ≥2× estimated requirement |
| Frit integrity | N₂ back-pressure test (0.5 bar) | Pressure holds steady |
| Temperature sensor | Comparison with reference thermometer | ±0.5 °C at current temp |
| Drain valve | Manual verification | Fully closed |
| Waste container | Capacity check | ≥50% empty |
| Batch record | All fields completed to current step | No gaps |
| Emergency stop | Visual inspection | Unobstructed, accessible |

## 3. Resin Loading and Swelling

1. Weigh required resin mass within ±1% of target using analytical balance
2. Transfer resin to reactor vessel with DMF rinse
3. Add sufficient DMF to cover resin (3 – 5 bed volumes, approximately 10 mL/g resin)
4. Initiate N₂ bubbling at low flow rate (0.5 L/min, adjust as needed)
5. Allow swelling for 30 – 60 min at 25 °C with gentle agitation
6. Drain DMF through frit, retain resin
7. Record initial resin mass and swelling time in batch record

## 4. Fmoc Deprotection Cycle

1. Add 20% (v/v) piperidine in DMF (10 mL/g resin)
2. Agitate with N₂ bubbling for 5 min at 25 °C
3. Open drain valve; collect deprotection solution (optional UV monitoring at 301 nm)
4. Add fresh 20% piperidine in DMF (10 mL/g resin)
5. Agitate for 10 min at 25 °C
6. Drain fully
7. Wash resin with DMF (10 mL/g resin, 3 – 5 min each, repeat 5×)
8. Collect and discard washes appropriately

## 5. Amino Acid Coupling Cycle

1. Prepare amino acid solution:
   - Dissolve Fmoc-AA-OH (3.0 – 5.0 eq. relative to resin loading) in minimal DMF
   - Add coupling reagent (3.0 – 5.0 eq.): HBTU, HATU, or DIC + Oxyma Pure
   - Add activator base (6.0 – 10.0 eq.): DIPEA or NMM
   - Vortex or stir until fully dissolved (2 – 5 min)
2. Add activated amino acid solution to reactor
3. Initiate N₂ bubbling at moderate flow (1.0 L/min)
4. Couple at 25 – 40 °C for 30 – 60 min
5. Drain coupling solution
6. Wash resin with DMF (10 mL/g resin, 3 – 5 min each, repeat 5×)

## 6. Kaiser Test (Ninhydrin Monitoring)

| Component | Preparation |
|---|---|
| Solution A | 40 g phenol in 10 mL ethanol |
| Solution B | 65 mg KCN in 100 mL H₂O, dilute 2 mL to 100 mL with pyridine |
| Solution C | 0.5 g ninhydrin in 10 mL ethanol |

**Procedure:**
1. Transfer 5 – 10 resin beads to a small glass test tube
2. Add 2 – 3 drops each of Solutions A, B, and C
3. Heat at 100 °C for 5 min
4. **Colorless/yellow** = coupling complete (negative test)
5. **Blue/purple** = free amines present (positive test → repeat coupling)
6. Document result in batch record

## 7. Capping Step (Optional)

1. Prepare capping solution: Acetic anhydride (10 eq.) + DIPEA (10 eq.) in DMF
2. Add to reactor
3. Agitate for 10 – 15 min at 25 °C
4. Drain
5. Wash with DMF (3×, 10 mL/g resin)

## 8. Final Wash Before Cleavage

1. Wash resin with DCM (10 mL/g resin, 3 – 5 min each, repeat 3×)
2. Drain thoroughly
3. Record final resin mass (optional: dry small sample for gravimetric yield check)

## 9. Peptide Cleavage and Precipitation

1. Prepare cleavage cocktail fresh:
   - 95% (v/v) TFA
   - 2.5% (v/v) triisopropylsilane (TIS)
   - 2.5% (v/v) water
2. Add cleavage cocktail (10 mL/g resin) to reactor
3. Agitate at 25 °C for 2 – 4 h (longer for Arg-rich sequences: 3 – 5 h)
4. Filter cleavage solution through frit into round-bottom flask
5. Wash resin with minimal TFA (2 × 2 mL); combine filtrates
6. Concentrate filtrate under reduced pressure (rotary evaporator) if volume >50 mL
7. Add cold diethyl ether (−20 °C, 10× volume of filtrate) to precipitate peptide
8. Centrifuge at 3000 – 4000 × g for 10 – 15 min at 4 °C
9. Decant supernatant carefully
10. Wash peptide pellet with cold ether (2 × 20 mL)
11. Dry under N₂ stream or vacuum desiccator (30 min – 2 h)
12. Transfer crude peptide to pre-weighed vial; record yield

## 10. Cleaning Procedure (Post-Batch)

| Step | Solvent | Volume | Time | Repeat |
|---|---|---|---|---|
| Pre-rinse | DMF | 500 mL | 5 min | 1× |
| Main wash | DMF | 500 mL | 10 min with N₂ agitation | 2× |
| Organic wash | DCM | 500 mL | 10 min | 1× |
| Alcohol wash | Methanol | 500 mL | 5 min | 1× |
| Aqueous wash | DI Water | 500 mL | 5 min | 1× |
| Drying | Acetone | 250 mL | 5 min | 1× |

## 11. Troubleshooting Guide

| Symptom | Possible Cause | Corrective Action |
|---|---|---|
| Low coupling yield | Insufficient AA excess | Increase to 5 eq. |
| Kaiser test positive after coupling | Steric hindrance or difficult sequence | Use HATU, increase temperature to 40 °C, extend time to 90 min |
| N₂ bubbling too vigorous | Resin splashing on vessel walls | Reduce flow rate, check frit condition |
| N₂ bubbling absent | Clogged frit | Back-flush N₂ from drain side; replace frit if persistent |
| Temperature deviating | Sensor drift or circulator failure | Recalibrate PT100; check circulator fluid level |
| Frit blockage | Resin fines accumulation | Back-flush with DMF under pressure; sonicate if needed |
| Incomplete cleavage | Insufficient time or scavenger | Extend to 4 h; verify TFA quality |
