---
type: post
title: "How Can Goodness-of-Fit Mislead Causality?"
summary: A better model fit does not necessarily mean a better causal estimate. Three common situations — collider bias, confounding, and mediation — illustrate why we need to define the causal structure before chasing R².
date: 2025-09-15
authors:
  - admin
tags:
  - Causal Inference
  - Biostatistics
  - Epidemiology
  - Real-World Evidence
---

I recently joined a webinar on Causal Inference by Justin Bélair, and one key takeaway was:

🚩 **A better model fit does not necessarily mean a better causal estimate.**

Here are three common situations that helped clarify this.

## 1. Collider bias

A **collider** is a variable influenced by both the exposure and the outcome. It should **not** be adjusted for.

Adjusting for a collider can improve model fit (e.g., increase R²), because it captures additional associations. However, this can introduce bias and distort the estimated effect of the exposure on the outcome.

▶️ *Better fit, but potentially the wrong conclusion.*

A practical example is in clinical trials: if we restrict the analysis to patients who remain in the study (i.e., ignore dropout), this can introduce collider bias. For instance, patients in the control group with worse outcomes are more likely to drop out.

## 2. Confounding

A **confounder** is a cause of both the exposure and the outcome, and it **should** be adjusted for.

Model fit may improve. More importantly, it helps reduce bias and move closer to the true causal effect.

## 3. Mediation

Whether to adjust for a **mediator** depends on the research question:

- ❎ **Total effect** → do not adjust
- ✅ **Indirect (mediated) effect** → explicitly model or adjust for it

## ✨ Takeaway

Goodness-of-fit reflects **association**, not **causation**.

Before fitting a model, we need to first define the causal structure — often using **Directed Acyclic Graphs (DAGs)** — to guide appropriate adjustment, especially in observational data and Real-World Evidence.

*#CausalInference #Biostatistics #Epidemiology #RealWorldEvidence*
