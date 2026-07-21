---
title: Environmental Monitoring System — Technical Specification
description: Technical specification for environmental monitoring systems tracking temperature, humidity, and differential pressure in cleanroom production areas at SENO Biotechnology.
tags:
  - equipment
  - specification
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "TechArticle",
  "headline": "Environmental Monitoring System — Technical Specification"
}
</script>

# Environmental Monitoring System — Technical Specification

## 1. System Parameters

| Parameter | Sensor Type | Range | Accuracy |
|---|---|---|---|
| Temperature | PT100 RTD | 0 – 50 °C | ±0.3 °C |
| Relative Humidity | Capacitive | 10 – 90% RH | ±2% RH |
| Differential Pressure | Piezoresistive | −50 to +50 Pa | ±0.5 Pa |
| Particle Count | Laser diode | 0.5 – 25 µm | ISO 21501-4 |

## 2. Monitoring Locations

| Area | Parameters | Alarm Limits |
|---|---|---|
| Production Suites | Temp, RH, DP | 20 – 25 °C, 30 – 65% RH, ≥15 Pa |
| Analytical Labs | Temp, RH | 20 – 25 °C, 30 – 60% RH |
| Storage (4 °C) | Temp | 2 – 8 °C |
| Storage (−20 °C) | Temp | −25 to −15 °C |
