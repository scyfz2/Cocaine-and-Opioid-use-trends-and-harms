# Cocaine-and-Opioid-use-trends-and-harms

# 🏴󠁧󠁢󠁳󠁣󠁴󠁿 Cocaine-&-Opioid Use Trends & Harms in Scotland (2015-2022)

> MSc Medical Statistics & Health Data Science, University of Bristol  
> Author: Fan Zhang  
> Date: 26 Aug 2025  
> Word count: 2 793 paper + 250 abstract + 323 plain-language summary  

---

## 🎯 Research questions

1. What is the trend of concurrent **Cocaine-&-Opioid (C&O) dependence** among people in OAT 2015-2022?  
2. Did C&O vs. opioid-only users differ on:  
   - Drug-related deaths (DRD)  
   - All-cause mortality (ACM)  
   - Non-fatal overdose hospitalisations (NFOD)  
   - Cardiovascular mortality (CVD)  
3. Were associations **modified** by age, sex, accommodation, region?

---

## 🧪 Key methods 

Retrospective cohort of **37 409 OAT recipients** ➜ **Poisson regression** with interaction terms ➜ **IRR (95 % CI)** adjusted for age, sex, year, NHS board & homelessness.

---

## 🔑 Top findings

| Outcome | C&O vs opioid-only (adjusted) | Interaction highlights |
|---------|-------------------------------|------------------------|
| **NFOD** | IRR 1.74 (1.67-1.82) | Highest in **young men 15-34**; older males **lower** than females. |
| **DRD** | IRR 0.93 (0.85-1.01) | No strong C&O excess after adjustment. |
| **ACM** | IRR 0.86 (0.80-0.92) | Slightly **lower** in C&O group. |
| **CVD** | IRR 0.71 (0.66-0.77) | **Strong Drug×Accommodation**: C&O & **housed** → IRR 0.47 (0.38-0.57) vs homeless/opioid. |

Crude rates of DRD/ACM/NFOD **rose** 2015-2021; CVD **fell** >70 %.  
Homelessness, Tayside residence, age 50-64 and male sex were independent risk amplifiers.

---

## 🧾 Data dictionary (abbreviated)

| Variable | Values | Note |
|----------|--------|------|
| `drug` | opioid / C&O | C&O = any cocaine record in SDMD/DAISy |
| `age_grp` | 15-34 / 35-49 / 50-64 | at cohort entry |
| `sex` | Female / Male | |
| `board` | GGC / Tayside / Other NHS Scotland | most recent OAT |
| `accommodation` | Homeless / Other | includes prison→Other |
| `year` | 2015 … 2022 | calendar year of follow-up |
| `outcome` | drd / acm / nfod / cvd | see ICD-10 list in supplement |



---

## ⚖️ Ethics & licence

- **Data**: © Public Health Scotland – provided under Scottish Public Health Drug Linkage Programme.
- **Code & text**: MIT Licence – feel free to fork, adapt, credit.


---

**Plain-language summary**:  
  
Scotland has one of the highest drug-related death rates in Europe. Many individuals who use opioids also use other drugs at the same time. One combination of concern is cocaine and opioid (C&O), because it can increase health risks. Cocaine can place strain on the heart and blood vessels, while opioids also can affect heart function. Cocaine, as a stimulant, can mask the sedative effect of opioids. When used together, they can lead individuals to take higher doses, increasing the risk of overdose or other serious problems.
  
This study looked at the trends over time of C&O dependence and related health harms in individuals in Scotland who were receiving opioid agonist therapy (OAT), a substitution therapy for opioid dependence. We used data from national health records collected between 2015 and 2022. We included 37,409 individuals aged 15–64 with at least one OAT prescription in the past two years. We compared individuals who used opioid with those who also used cocaine. We focus on four health outcomes: drug-related deaths, all-cause mortality, non-fatal overdoses (where someone is taken to hospital but survives), and cardiovascular mortality.
  
We found that about 1 in 5 individuals (21.6%) receiving OAT also used cocaine. This group was more likely to experience a non-fatal overdose than individuals who used opioid, even after accounting for differences in age, sex, region, and accommodation status. The highest overdose risk was in young men aged 15–34. However, individuals with C&O dependence had a lower rate of cardiovascular mortality compared with those with opioid dependence. 
Across all groups, older age, homelessness, and living in certain areas (such as Tayside) were linked to higher risks of death. Men generally had higher risks of cardiovascular death than women, especially in the middle-aged and older groups. This study found that individuals with combined C&O dependence had higher risks of non-fatal overdose compared with those with opioid dependence, but not consistently higher risks of other drug-related, all-cause or cardiovascular mortality. 
