---
type: post
title: "Selection Bias: Another Challenge in Real-World Evidence"
summary: Real-world studies are only as good as the data they draw from. Who enters the dataset, who stays, and how follow-up time is classified all shape findings — sometimes more than the statistical model.
date: 2025-10-20
authors:
  - admin
tags:
  - Real-World Evidence
  - Epidemiology
  - Clinical Research
  - Survival Analysis
---

Real-world studies are only as good as the data they draw from — and that data is rarely a perfect mirror of the real world.

## The selection bias problem

In real-world studies using registry or claims data, the dataset often captures only:

- Certain hospitals or clinics
- Insured populations
- Specific healthcare systems
- Biobanks or survey participants

The key question is always:

❓ *Are the people in the dataset different from the population we care about?*

Biobank and survey participants, for instance, tend to be **healthier** than the general population, which can quietly skew your findings.

## ▶️ Who enters matters. So does who stays.

In longitudinal studies, **loss to follow-up** is a common source of selection bias. The critical question here is:

❓ *Are those who drop out different from those who remain?*

In one of my previous studies on air pollution and autism/ADHD symptoms, participants with more severe symptoms were more likely to drop out over time. The result? Observed associations could **underestimate** the true effect, because the people most affected weren't there at the end.

- 📄 [Li et al., *Environmental Research* (2023)](https://www.sciencedirect.com/science/article/pii/S0013935123004966)

## ✅ Immortal time bias: a very important one in RWE survival analysis

When studying treatment effects on mortality (or other events), some patients receive treatment *after* the study begins — for example, two years in. If that pre-treatment window is incorrectly coded as "treated time," you've created **immortal time bias**.

Why? Because patients had to **survive** that entire period to receive treatment. Counting it as treated time artificially inflates the treatment's apparent protective effect.

It's not a real benefit — it's a classification error, and it leads to a false protective effect of the treatment.

## 🚩 The lesson

Always think in your design: **who's in it, when they entered, when they left, and how they were classified**. It shapes your findings just as much as your statistical model.

*#RealWorldEvidence #RWE #EvidenceBasedMedicine #ClinicalResearch #Pharma #HealthData #ClinicalTrials*
