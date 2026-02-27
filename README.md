# Energy-Dunkelflaute-Analysis-
 
This repository provides a reproducible workflow for the identification and analysis of renewable energy Dunkelflaute (Energy Drought) events. The framework focuses on the joint behavior of wind and solar PV generation and quantifies the impact of diversification on low-production periods.

The analysis enables:

    Detection and characterization of Dunkelflaute events based on user-defined capacity factor (CF) thresholds.

    Assessment of wind-solar complementarity to identify how different resources balance each other.

    Quantification of smoothing vs. complementarity effects within a hybrid energy portfolio.

    Scenario-based evaluation of various renewable mixes.

    Diagnostic visualization including Heatmaps, GEV Extreme Value analysis, and Portfolio Radar charts.

This code is based on and extends the methodology and implementation provided in the repository:

- RES_droughts hosted on (https://github.com/BorisM202/RES_droughts?tab=readme-ov-file)

which accompanies the research article:
_Reducing RES Droughts through the integration of wind and solar PV
by Boris Morin, Aina Maimó Far, Damian Flynn, and Conor Sweeney
published in Renewable Energy (2025)
DOI: 10.1016/j.renene.2025.123392_

**Requirements**

**Main Dependencies:**

    pandas

    numpy

    matplotlib

    seaborn

    scipy

    openpyxl

    pyyaml

**Data Requirements:**
Input data must be hourly time series with no missing timestamps or duplicate entries, providing capacity factor or normalized generation values.


Contributions and feedback are welcome.
