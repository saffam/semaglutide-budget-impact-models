# Data Sources

This project uses publicly available healthcare datasets and published evidence to support transparent and reproducible Health Economics and Outcomes Research (HEOR) modelling.

Country-specific source documentation is provided in:

- [United Kingdom sources](uk_sources.md)
- [United States sources](usa_sources.md)
- [Italy sources](italy_sources.md)

No proprietary datasets, patient-level data, or confidential information are included in the repository.

---

# United Kingdom 🇬🇧

## Population Data

**Source:** Office for National Statistics (ONS)

**Purpose:**

- Estimate the adult population aged 18 years and over
- Provide the population denominator for obesity modelling

## Obesity Prevalence

**Source:** Health Survey for England (HSE)

**Purpose:**

- Estimate adult obesity prevalence
- Support calculation of the eligible treatment population

## Treatment Cost

**Source:** Published semaglutide treatment-cost information

**Purpose:**

- Estimate annual treatment acquisition cost
- Support the UK budget impact calculation

## Healthcare Context

**Sources:**

- NHS England
- Published healthcare cost evidence

**Purpose:**

- Provide healthcare-system context
- Support interpretation of the potential budget impact

---

# United States 🇺🇸

## Population Data

**Source:** U.S. Census Bureau

**Purpose:**

- Estimate the U.S. adult population aged 18 years and over
- Provide the population denominator for obesity modelling

## Obesity Prevalence

**Source:** Centers for Disease Control and Prevention (CDC) Behavioral Risk Factor Surveillance System (BRFSS)

**Purpose:**

- Estimate adult obesity prevalence
- Calculate the population with obesity for the model

## Treatment Cost

**Source:** Published Wegovy (semaglutide) pricing information

**Purpose:**

- Estimate annual treatment acquisition cost
- Support the U.S. budget impact calculation

## Healthcare Cost Offsets

**Source:** Published literature on obesity-associated healthcare expenditure

**Purpose:**

- Estimate potential healthcare cost offsets associated with obesity treatment
- Incorporate healthcare savings into the U.S. net budget impact calculation

---

# Italy 🇮🇹

## Population Data

**Source:** Italian population data

**Purpose:**

- Estimate the Italian adult population aged 18 years and over
- Provide the population denominator for obesity modelling

## Obesity Prevalence

**Source:** Publicly available Italian epidemiological evidence

**Purpose:**

- Estimate adult obesity prevalence
- Calculate the modelled eligible population

## Treatment Cost

**Source:** Published semaglutide treatment-cost information and documented modelling assumptions

**Purpose:**

- Estimate annual treatment acquisition cost
- Support the Italy treatment-cost impact scenario

## Treatment Uptake

**Source:** Modelling assumption

**Purpose:**

- Apply five-year treatment uptake scenarios
- Estimate treated population under different adoption levels

## Healthcare Cost Offsets

No Italy-specific healthcare cost offset is included in the current base-case model.

The Italy analysis is therefore interpreted as a **treatment-cost impact scenario**, rather than a current Italian NHS reimbursement budget impact.

---

# Europe 🇪🇺

A Europe-wide model is planned as a future extension.

Additional European country-specific population, epidemiological, treatment-cost, reimbursement, and healthcare-cost sources will be documented when the Europe model is developed.

---

# Data Availability

All datasets and evidence used in the project are publicly available.

The project does not use:

- Proprietary datasets
- Patient-level data
- Confidential healthcare information
- Simulated patient-level datasets

Model calculations are performed using publicly available data and explicitly documented modelling assumptions.