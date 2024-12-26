# Anatomy of Municipal Green Bond Yield Spreads
This repository is associated with the methodology presented in the paper titled **"Anatomy of Municipal Green Bond Yield Spreads"**.  
A PDF version of the paper is accessible at [URL] or in the **"paper"** folder, which also contains the Supplementary Materials.
# Abstract
Exploring the attributes of the rapidly evolving green bond market is crucial for directing capital towards projects that mitigate climate risks and facilitate adaptation to environmental changes. To address the limitations of traditional bond matching-based spread methods, we propose a novel approach to compute green bond spreads based on yields to maturity and their term structure. We then analyze the key attributes related to the magnitude and sign of these spreads, as well as their consistency over time. Based on California's green municipal bond market, we find that these two types of green bond spread are on average positive and disparate but reach negative territories and converge after 2022. We identify structuring attribute associations of these spreads using a Bayesian machine learning approach, namely Association Rule Learning. Positive (and extreme positive) spreads based on tenor-specific information are associated with attributes such as tax status, pricing strategy, and maturity, while negative spreads are typically associated with a more complex interaction of attributes, including spread and yield on issuance, and callability. Spreads embedding information from the yield curve term structure are associated with attributes such as duration, maturity, and callability. Sector-specific differences in credit ratings, issue sizes, and use of proceeds have also been identified. The distinctive structuring attributes of these two types of spreads highlight the dynamic and heterogeneous nature of green bond spreads and offer practical insights regarding green bond screening to inform investment and diversification strategies, and policy decisions for sustainable portfolio management. 

## Organization of the Repository

The repository is organized into the following folders:

<<div style="background-color: #f0f0f0; padding: 10px; font-weight: bold; border-radius: 5px;">
    <b>1) <span style="background: linear-gradient(90deg, yellow, lightyellow); padding: 0 5px; border-radius: 3px;">Codes</span></b>
</div>
<p>This folder contains the R markdown developed for the paper's methodology. It is structured within the following folders:</p>


---

<b>1) Spreads</b>
<p>In this folder, the following R Markdown files are used for the proposed novel bond spread calculations:</p>

<ul>
    <li><b>Approach 1 Spread.Rmd</b>: This R Markdown file is used for a tenor-specific time series approach that calculates green bond spreads based on yield to maturity (YTM).</li>
    <li><b>Approach 2 Spread.Rmd</b>: This R Markdown file is used for a yield curve time series approach that calculates green bond spreads based on the YTM term structure.</li>
</ul>















3. **ARL**  
   

4. **ANOVA**  
   

5. **BMS**  
   

### 2) Data
This folder contains the US Treasury par yield data and data generated using the ARL technique. 
### 3) Paper
 This folder contains the latest version of the paper and its associated supplementary materials, which can also be found at the following link:
 [URL] 








