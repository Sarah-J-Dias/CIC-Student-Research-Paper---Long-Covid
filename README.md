# CIC-Student-Research-Paper---Long-Covid
This repository contains the R-code which I used to analyze data from the U.S. Census Bureau’s Household Pulse Survey (HPS Phase 4.2 Cycle 9), specifically Health Tables 5 (vaccination) and 8 (Long COVID).  My analysis was conducted in three steps in which I investigated vaccination disparities, vaccination vs. Long COVID prevalence, and severity of long Covid by demographic.


## Quick Links
- 📄 **Paper/Write-up**: (add link if hosted or in `/output`)
- 📓 **R Markdown code**:
  1. **Vaccine Disparities** → [`analysis/01_vaccine_disparities.Rmd`](analysis/01_vaccine_disparities.Rmd)
  2. **Vaccination vs Long COVID** → [`analysis/02_vax_vs_longcovid.Rmd`](analysis/02_vax_vs_longcovid.Rmd)
  3. **Long COVID Severity** → [`analysis/03_longcovid_severity.Rmd`](analysis/03_longcovid_severity.Rmd)
- 📊 **Figures/Tables**: see `/output/figures` and `/output/tables`

---

## 3-Step Analysis Overview

| Step | Topic | Main Question | Key Outputs |
|---|---|---|---|
| 1 | **Vaccination Disparities** | How do vaccination rates vary across income, education, race/ethnicity, and age? | Stacked barplots by demographic; CSV summary tables |
| 2 | **Vaccination vs Long COVID** | Among those ever infected, is recent vaccination associated with lower Long COVID prevalence? | Prevalence plots and comparative tables |
| 3 | **Long COVID Severity** | How does reported severity (“a lot / a little / not at all”) vary by demographic group? | Severity distribution plots; stratified summaries |

---

## Reproducibility

**Requirements:** R ≥ 4.3

**Install packages:**
```r
install.packages(c("tidyverse","readxl","janitor","ggplot2","broom","gt","here"))

