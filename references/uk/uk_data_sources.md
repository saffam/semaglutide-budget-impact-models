# United Kingdom Data Sources 🇬🇧

## Population Data

Source:
Office for National Statistics (ONS)

Dataset:
Mid-year population estimates (MYE2)

Use in model:
- Adult population aged 18+
- Population denominator for obesity calculations


---

## Obesity Prevalence Data

Source:
NHS Digital

Dataset:
Health Survey for England (HSE) 2024

Use in model:
- Adult obesity prevalence
- Population eligible for treatment


---

## Treatment Cost Data

Source:
National Institute for Health and Care Excellence (NICE)
and publicly available NHS medicine pricing information

Use in model:
- Annual semaglutide treatment cost assumption


---

## Healthcare Cost Offset Data

Source:
Publicly available UK obesity healthcare cost literature

Use in model:
- Potential healthcare cost savings associated with obesity treatment


---

## Modelling Approach

The UK budget impact model estimates:

- Eligible population
- Treatment uptake scenarios
- Annual drug expenditure
- Potential healthcare cost offsets
- Net budget impact over 5 years

All calculations were performed using Python.