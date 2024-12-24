# Anatomy of Municipal Green Bond Yield Spreads
This repository is associated with the methodology presented in the paper titled **"Anatomy of Municipal Green Bond Yield Spreads"**.  
A PDF version of the paper is accessible at [URL] or in the **"paper"** folder, which also contains the Supplementary Materials.
# Abstract
Exploring the attributes of the rapidly evolving green bond market is crucial for directing
capital towards projects that mitigate climate risks and facilitate adaptation to environmen-
tal changes. We propose novel approaches to compute green bond spreads based on yields
to maturity and their term structure. Based on California’s green municipal bond market,
we find that these two types of green bond spread are on average positive and disparate
but reach negative territories and converge after 2022. Using Association Rule Learning, we
find that positive tenor-specific spreads are associated with tax status, callability, pricing
strategy, and maturity, while negative spread associations are more complex. Yield curve
spreads tend to relate to maturity-related attributes. Sector-specific differences in credit
ratings, issue sizes, and use of proceeds have also been identified. The distinctive spread
structuring attributes highlight the dynamic and heterogeneous nature of green bonds and
offer practical insights for green bond screening practice.

## Organization of the Repository

The repository is organized into the following folders:

### 1) Codes

## 2) R_code

> This folder contains the R code developed for the analysis of the paper. It is structured within the following folders:

1. **CCA**  
   This folder contains the code for the extraction of the Canonical Correlation Analysis given in `cca_cali.R` and the code for producing the helioplots in the paper and in the description above (only some) in `cca_circular_barplot.R`.

2. **climate**  
   This folder contains the code for the extraction, pre-processing, feature engineering, and PCA/kPCA computations of the climate data.

3. **financial**  
   This folder contains the code for the extraction, pre-processing, feature engineering, and PCA/kPCA computations of the financial data.

4. **pollution**  
   This folder contains the code for the extraction, pre-processing, feature engineering, and PCA/kPCA computations of the pollution data.



### 2) Data
### 3) Paper









