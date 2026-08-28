# PersistentValueCreation
A quantitative analysis of the level, persistence and resilience of corporate ROE as indicators of the ability to create value persistently.

This project studies the **level, persistence, and resilience of corporate Return on Equity (ROE)** as indicators of a company's ability to create value persistently over time. 

The analysis uses historical ROE data and quantitative methods in **R** to examine:
- **Level** - What is the magnitude of a company's ROE?
- **Persistence** - How consistently is ROE maintained over time?
- **Resilience** - How does ROE respond to and recover from negative shocks?

The project ultimately aims to determine whether these characteristics of ROE can provide meaningful evidence of a company's **persistent value creation ability**.

## Project Overview

The study:
- Begins with **intrinsic value** as the concept of interest and through the **Residual Income Model** it's shown how it's analysis can be reduced to the study of the company's **ROE**.
- Examines the **magnitude of ROE** and its behaviour over time.
- Measures **ROE persistence** using metrics obtained from the **AR(1) Model**.
- Measures **ROE resilience to shocks** through three components:
  - **Volatility**- average squared deviation from the long-run mean.
  - **Shock severity** - The distance of ROE below the defined shock level.
  - **Recovery time** - Time spent in a shock.
- Provides a practical demonstration in **R**, using 20 years of company ROE data to obtain the relevant metrics.
- Produces **10 quantitative metrics**, which are then interpreted together to form a coherent **story of the company's value creation ability**.
- Concludes with a discussion of **assumptions, limitations, potential improvements, and practical implications**.

## Methodology

The project combines:
- Financial and ROE analysis
- AR(1) time-series modelling
- Shock and recovery analysis
- Quantitative metric construction
- Practical implementation in **R**

The full methodology, mathematical development, coding, results, and interpretation are presented in the accompanying **Quarto document**.

## Repository Structure

```text
PersistentValueCreation/
│
├── Data/
│   ├── Capitec_ROE.xlsx
│   ├── ControlCompany_ROE.xlsx
│   ├── FirstRand_ROE.xlsx
│   └── Shoprite_ROE.xlsx
│
├── ROE_analysis.qmd
├── README.md
├── .gitignore
└── LICENSE
