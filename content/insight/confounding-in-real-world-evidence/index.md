---
type: post
title: "Confounding: A Core Challenge in Real-World Evidence"
summary: One of the key challenges in observational studies is confounding. From ice cream and swimming pools to age as a hidden driver in autism and cardiometabolic risk — why properly addressing confounders is essential to RWE.
date: 2025-10-01
authors:
  - admin
tags:
  - Causal Inference
  - Biostatistics
  - Epidemiology
  - Real-World Evidence
---

One question that often comes up in real-world evidence (RWE) discussions is:

❓ *"What are the key challenges in observational studies?"*

**Confounding** is one of the key challenges and lies at the core of epidemiology.

The concept of observational studies (RWE) is in contrast to **intervention studies (clinical trials)**, where treatment/exposure assignment is assigned (often via randomization) so that confounding is generally balanced across groups. Observational studies rely on real-world data without randomization.

▶️ A **confounder** is a variable that influences both the exposure and the outcome, potentially creating a spurious association.

## 🍦 A classic and easy-to-remember example

Ice cream sales and swimming pool attendance are positively correlated. Obviously, not because one causes the other — the underlying driver is **temperature**, which affects both.

In healthcare research, common confounders include **age, sex, and socioeconomic status (SES)**. These factors are often associated with both disease outcomes and health-related factors. Failing to properly address confounding can lead to biased estimates and misleading conclusions.

## One example from my previous work

🫀 I examined whether individuals with autism are more likely to develop cardiometabolic conditions using nationwide registry data (ages 12–65 years).

In an **initial crude comparison**, the autism group appeared to have a *lower* incidence of cardiometabolic diseases, which is contrary to expectations.

However, a closer look revealed a key difference: the autism group was substantially younger than the non-autism group. This has multiple reasons, such as historical underdiagnosis of autism in older generations and elevated mortality rates among individuals with autism.

In this context, **age acts as a confounder**: it is associated with both the likelihood of an autism diagnosis and the risk of cardiometabolic outcomes. As expected, after accounting for age (e.g., through stratification), the association became apparent.

- 📄 Full text: [https://rdcu.be/eUIkV](https://rdcu.be/eUIkV)
- 🔗 DOI: [https://doi.org/10.1038/s44220-025-00546-9](https://doi.org/10.1038/s44220-025-00546-9)

In real-world evidence (RWE) studies, particularly those based on large registry or claims data, many confounders are often **unmeasured**. These limitations should be kept in mind.

*#CausalInference #Biostatistics #Epidemiology #RealWorldEvidence*
