# Semaglutide Budget Impact Models

Comparative budget impact analyses of semaglutide (Wegovy) for obesity management using publicly available healthcare data from the United Kingdom, United States, and Italy, with Europe planned as a future extension.

---

# Project Overview

This repository develops transparent and reproducible Budget Impact Models (BIMs) to estimate the potential financial impact of introducing semaglutide-based obesity treatment across different healthcare systems.

The project applies Health Economics and Outcomes Research (HEOR) methods to evaluate:

* Adult and eligible patient populations
* Treatment uptake scenarios
* Annual medication costs
* Healthcare cost offsets where country-specific evidence is available
* Five-year net budget impact

All analyses use publicly available datasets and published evidence. Calculations are designed to be traceable and reproducible.

---

# Data Sources

The models use publicly available population, epidemiological, healthcare, and pharmaceutical data.

Detailed country-specific source documentation is available below:

* [United Kingdom sources](references/uk_sources.md)
* [United States sources](references/usa_sources.md)
* [Italy sources](references/italy_sources.md)

The Europe model is planned as a future extension of the project.

---

# Methods

Each country-specific Budget Impact Model follows a consistent analytical framework while allowing country-specific population, epidemiological, treatment-cost, and healthcare-cost assumptions.

The analysis includes:

* Population estimation
* Obesity prevalence estimation
* Eligible treatment population calculation
* Treatment uptake scenarios
* Semaglutide treatment cost estimation
* Healthcare cost offset estimation where appropriate
* Five-year net budget impact projection
* Sensitivity analysis of key model parameters

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

All calculations are based on publicly available healthcare data and documented assumptions.

---

## Results

### United Kingdom

* Adult population (18+): **55.0 million**
* Obesity prevalence: **29.9%**
* Eligible population: **3.29 million**
* Annual treatment cost: **£2,500**
* Year 1 net budget impact: **£394.9 million**
* Year 5 net budget impact: **£1.97 billion**

**Model outputs:**

* [UK model summary](reports/uk/uk_model_summary.csv)
* [UK budget impact table](reports/uk/tables/uk_budget_impact_summary.csv)
* [UK budget impact figure](reports/uk/figures/uk_budget_impact.png)
* [UK price sensitivity figure](reports/uk/figures/uk_price_sensitivity.png)

### United States

* Adult population (18+): **269.8 million**
* Obesity prevalence: **33.1%**
* Adults with obesity: **89.2 million**
* Annual treatment cost: **$17,537**
* Year 1 net budget impact: **$67.5 billion**
* Year 5 net budget impact: **$337.3 billion**

**Model outputs:**

* [USA model summary](reports/usa/tables/usa_model_summary.csv)
* [USA population summary](reports/usa/tables/usa_population_summary.csv)
* [USA eligibility summary](reports/usa/tables/usa_eligibility_summary.csv)
* [USA epidemiology summary](reports/usa/tables/usa_epidemiology_summary.csv)
* [USA drug cost summary](reports/usa/tables/usa_drug_cost_summary.csv)
* [USA healthcare cost parameter](reports/usa/tables/usa_healthcare_cost_parameter.csv)
* [USA semaglutide cost-offset summary](reports/usa/tables/usa_semaglutide_cost_offset_summary.csv)
* [USA budget impact summary](reports/usa/tables/usa_budget_impact_summary.csv)

**Visual outputs:**

* [Treated population growth](reports/usa/figures/usa_treated_population_growth.png)
* [Treatment cost vs healthcare savings](reports/usa/figures/usa_cost_vs_savings.png)
* [Net budget impact](reports/usa/figures/usa_net_budget_impact.png)
* [USA model summary dashboard](reports/usa/figures/usa_model_summary_dashboard.png)

### Italy

* Adult population (18+): **50.3 million**
* Obesity prevalence: **11.8%**
* Eligible population: **~5.94 million**
* Annual treatment cost: **€3,000**
* Year 1 uptake: **5%**
* Year 1 treated population: **~297,000**
* Year 1 net budget impact: **~€891 million**
* Year 5 uptake: **25%**
* Year 5 treated population: **~1.48 million**
* Year 5 net budget impact: **~€4.45 billion**

The Italy analysis should be interpreted as a **treatment-cost impact scenario**, rather than a current Italian NHS reimbursement budget impact. No Italy-specific healthcare cost offset is included in the base case.

**Model outputs:**

* [Italy model summary](reports/italy/tables/italy_model_summary.csv)
* [Italy adult population summary](reports/italy/tables/italy_adult_population_summary.csv)
* [Italy budget impact summary](reports/italy/tables/italy_budget_impact_summary.csv)
* [Italy drug cost sensitivity](reports/italy/sensitivity/italy_drug_cost_sensitivity.csv)
* [Italy uptake sensitivity](reports/italy/sensitivity/italy_uptake_sensitivity.csv)

**Visual outputs:**

* [Italy budget impact](reports/italy/figures/italy_budget_impact.png)
* [Italy price sensitivity](reports/italy/figures/italy_price_sensitivity.png)
* [Italy uptake sensitivity](reports/italy/figures/italy_uptake_sensitivity.png)

### Cross-Country Comparison

Country-level model outputs are stored in:

* [UK reports](reports/uk/)
* [USA reports](reports/usa/)
* [Italy reports](reports/italy/)
* [Comparative reports](reports/comparative/)


# Research Question

**What would be the potential healthcare budget impact of introducing semaglutide for obesity management across different healthcare systems?**

The analysis examines how population size, obesity prevalence, treatment costs, uptake scenarios, and healthcare-cost assumptions influence the potential financial impact of adoption.

---

# Project Objectives

* Build country-specific Budget Impact Models
* Estimate eligible populations for obesity treatment
* Compare potential healthcare-system impacts across countries
* Apply HEOR modelling principles
* Conduct sensitivity analyses for key assumptions
* Demonstrate reproducible healthcare analytics using Python
* Create an open-source healthcare economics portfolio project

---

# Countries Included

| Country             | Status    |
| ------------------- | --------- |
| 🇬🇧 United Kingdom | Completed |
| 🇺🇸 United States  | Completed |
| 🇮🇹 Italy          | Completed |
| 🇪🇺 Europe         | Planned   |

---

# Modelling Approach

Each country model follows a consistent budget impact framework:

1. Estimate the adult population
2. Apply obesity prevalence estimates
3. Define the eligible treatment population
4. Apply treatment uptake scenarios
5. Estimate annual treatment costs
6. Estimate healthcare cost offsets where supported by country-specific evidence
7. Calculate net budget impact
8. Conduct sensitivity analyses

The same core framework is applied across country models while allowing country-specific data, costs, and assumptions.

---

# Limitations

This analysis represents a budget impact scenario model and does not predict actual future expenditure.

Important limitations include:

* Treatment uptake assumptions represent hypothetical scenarios rather than observed future utilization
* Drug prices may vary by payer, reimbursement arrangement, discounts, and negotiated agreements
* Healthcare cost offsets depend on the availability and applicability of published evidence
* Country-specific healthcare systems and reimbursement rules may affect the real-world budget impact
* Country models use publicly available aggregate data rather than individual patient-level data
* Some model parameters require assumptions where suitable country-specific evidence is unavailable
* The Italy base case does not include an Italy-specific healthcare cost offset
* The Italy treatment-cost parameter is a modelling assumption and should not be interpreted as a current Italian NHS reimbursement tariff

The purpose of this project is to demonstrate transparent HEOR modelling methods and compare potential financial impacts across healthcare systems using reproducible public data.

---

# Project Structure

```text
semaglutide-budget-impact-models/

│
├── data/
│   ├── uk/
│   ├── usa/
│   ├── italy/
│   └── europe/
│
├── notebooks/
│
├── references/
│   ├── uk_sources.md
│   ├── usa_sources.md
│   └── italy_sources.md
│
├── reports/
│   ├── uk/
│   ├── usa/
│   ├── italy/
│   └── comparative/
│
├── src/
│
└── README.md
```

---

# Project Status

| Component                          | Status      |
| ---------------------------------- | ----------- |
| UK Budget Impact Model             | Completed   |
| USA Budget Impact Model            | Completed   |
| Italy Budget Impact Model          | Completed   |
| Country-level sensitivity analyses | Completed   |
| Cross-country comparison           | In progress |
| Europe model                       | Planned     |
| Final documentation                | In progress |

