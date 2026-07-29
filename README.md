# Semaglutide Budget Impact Models

Comparative budget impact analyses of semaglutide (Wegovy) for obesity management using publicly available healthcare data from the United Kingdom, United States, Italy, and Europe.

---

# Project Overview

This repository develops transparent and reproducible Budget Impact Models (BIMs) to estimate the financial impact of introducing semaglutide-based obesity treatment across different healthcare systems.

The project applies Health Economics and Outcomes Research (HEOR) methods to evaluate:

- Eligible patient populations
- Treatment uptake scenarios
- Annual medication costs
- Healthcare cost offsets
- Overall budget impact on healthcare systems

All analyses use publicly available datasets and published evidence. Every calculation is designed to be traceable and reproducible.

# Key Results

## United Kingdom

The UK model estimates the financial impact of introducing semaglutide among eligible adults with obesity.

## United States

The US model estimates a substantially larger gross budget impact due to higher drug acquisition costs and population size.

## Cross-country comparison

The project compares how healthcare system structure, obesity prevalence, treatment eligibility and drug pricing influence budget impact.

---

# Research Question

**What would be the potential healthcare budget impact of introducing semaglutide for obesity management across different healthcare systems?**

The project compares how population size, obesity prevalence, treatment costs, and healthcare structures influence the financial impact of adoption.

---

# Project Objectives

- Build country-specific budget impact models
- Estimate eligible populations for obesity treatment
- Compare healthcare system impacts across countries
- Apply HEOR modelling principles
- Demonstrate reproducible healthcare analytics using Python
- Create an open-source healthcare economics portfolio project

---

# Countries Included

| Country | Status |
|----------|--------|
| 🇬🇧 United Kingdom | ✅ Completed |
| 🇺🇸 United States | ✅ Completed |
| 🇮🇹 Italy | 🔄 Planned |
| 🇪🇺 Europe | 🔄 Planned |

---

# Modelling Approach

Each country model follows a similar framework:

1. Estimate adult population
2. Apply obesity prevalence estimates
3. Define eligible treatment population
4. Apply treatment uptake scenarios
5. Estimate annual treatment costs
6. Estimate healthcare cost offsets
7. Calculate net budget impact

---

# Current Results
---

# Visualisations

## Eligible Treatment Population Comparison

![Eligible Population Comparison](reports/comparison/eligible_population_comparison.png)

## Five-Year Budget Impact Comparison

![Budget Impact Comparison](reports/comparison/budget_impact_comparison.png)

## 🇬🇧 United Kingdom

| Metric | Value |
|--------|------:|
| Adult population | 55.0 million |
| Obesity prevalence | 29.9% |
| Eligible population | 3.29 million |
| Year 1 net budget impact | £394.9 million |
| Year 5 net budget impact | £1.97 billion |

## 🇺🇸 United States

| Metric | Value |
|--------|------:|
| Adult population | 269.8 million |
| Obesity prevalence | 33.1% |
| Adults with obesity | 89.2 million |
| Annual treatment cost | $17,537 per patient |
| Year 1 net budget impact | $67.5 billion |
| Year 5 net budget impact | $337.3 billion |

## General model structure:

```
Net Budget Impact = Drug Costs − Healthcare Cost Offsets
```

The same framework is applied across all country models while allowing country-specific assumptions, costs, and epidemiological data.