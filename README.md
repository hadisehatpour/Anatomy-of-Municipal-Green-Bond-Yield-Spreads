# Anatomy of Municipal Green Bond Yield Spreads
This repository is associated with the methodology presented in the paper titled **"Anatomy of Municipal Green Bond Yield Spreads"**.  
A PDF version of the paper is accessible at [URL] or in the **"paper"** folder, which also contains the Supplementary Materials.
# Abstract
Exploring the attributes of the rapidly evolving green bond market is crucial for directing capital towards projects that mitigate climate risks and facilitate adaptation to environmental changes. To address the limitations of traditional bond matching-based spread methods, we propose a novel approach to compute green bond spreads based on yields to maturity and their term structure. We then analyze the key attributes related to the magnitude and sign of these spreads, as well as their consistency over time. Based on California's green municipal bond market, we find that these two types of green bond spread are on average positive and disparate but reach negative territories and converge after 2022. We identify structuring attribute associations of these spreads using a Bayesian machine learning approach, namely Association Rule Learning. Positive (and extreme positive) spreads based on tenor-specific information are associated with attributes such as tax status, pricing strategy, and maturity, while negative spreads are typically associated with a more complex interaction of attributes, including spread and yield on issuance, and callability. Spreads embedding information from the yield curve term structure are associated with attributes such as duration, maturity, and callability. Sector-specific differences in credit ratings, issue sizes, and use of proceeds have also been identified. The distinctive structuring attributes of these two types of spreads highlight the dynamic and heterogeneous nature of green bond spreads and offer practical insights regarding green bond screening to inform investment and diversification strategies, and policy decisions for sustainable portfolio management. 

## Organization of the Repository

The repository is organized into the following folders:

<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px; font-weight: bold;">
    <h3>1) Codes</h3>
</div>
<p>This folder contains the R markdown developed for the paper's methodology. It is structured within the following folders:</p>


---

<b>1) Spreads</b>
<p>In this folder, the following R Markdown files are used for the proposed novel bond spread calculations:</p>

<ul>
    <li><b>Approach 1 Spread.Rmd</b>: This R Markdown file is used for a tenor-specific time series approach that calculates green bond spreads based on yield to maturity (YTM).</li>
    <li><b>Approach 2 Spread.Rmd</b>: This R Markdown file is used for a yield curve time series approach that calculates green bond spreads based on the YTM term structure.</li>
</ul>




<b><span style="color: gold;">★</span>) ARL</b>
<p>In In this folder, the following R Markdown files are used for the screening process employing a machine learning technique called Association Rules Learning::</p>

<ul>
    <li><b>ARL_S1.Rmd</b>: This R-markdown uses the first spread for association rule learning.</li>
    <li><b>ARL_S2.Rmd</b>: This R-markdown uses the second spread for association rule learning.</li>
    <li><b>ARL_Med_Extreme_S1.Rmd</b>: This R-markdown uses the first spread for finding rules associated with extreme spread values.</li>
    <li><b>ARL_Med_Extreme_S2.Rmd</b>: This R-markdown uses the second spread for finding rules associated with extreme spread values.</li>
    <li><b>ARL_Stability_S1.Rmd</b>: This R Markdown file uses the first spread to determine the temporal consistency of the strong identified rules.</li>
    <li><b>ARL_Stability_S2.Rmd</b>: This R Markdown file uses the second spread to determine the temporal consistency of the strong identified rules.</li>

</ul>
   

<b>3) ANOVA</b>
<p>In this folder, the following R Markdown file is used to test the statistical significance of the ARL results (Order 2):</p>

<ul>
    <li><b>ANOVA.Rmd</b>: This R-markdown uses the first spread for association rule learning.</li>
</ul>
   

<b>4) ANOVA</b>
<p>In this folder, the following R Markdown file is used for Bayesian model selection:</p>

<ul>
    <li><b>ANOVA.Rmd</b>: This R Markdown file is used for Bayesian model selection utilizing both spreads.</li>

</ul> 
   





<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px; font-weight: bold;">
    <h3>2) Data</h3>
</div>
<p>This folder contains some data sets used for analysis in this paper. It is structured within the following folders:</p>

---

<b>1) ARL</b>
<p>In this folder, the following R Markdown files are used for the proposed novel bond spread calculations:</p>

<ul>
    <li><b>Ext:</b> This folder contains data for results from ARL for extreme spread values.</li>
    <li><b>Rules:</b> This folder contains data for results from ARL for rules in various orders.</li>
</ul>

<b>2) US_Treasury </b>
<p> This folder contains US Treasury par yield data. <p>



<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
    <h3 style="font-weight: bold;">3) Paper</h3>
</div>
<p>This folder contains the latest version of the paper and its associated supplementary materials, which can also be found at the following link: [URL]</p>









