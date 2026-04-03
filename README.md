# Earthquake Frequency Analysis (2006–2025)

This project examines whether the number of earthquakes with magnitude M ≥ 4.5 changed between two decades: 2006–2015 and 2016–2025. The analysis combines simple visualisations with three statistical tests.

You can view the full HTML version of the analysis here:  https://maria-kolouchova.github.io/Earthquake-frequency-analysis/
<hr>

**Overview**

**Line graph:** No clear long‑term trend.

**Boxplot:** Slightly higher median and wider spread in the second decade.

**Mann–Whitney U test:** No significant difference in distributions.

**Poisson rate test:** No significant difference in average annual rate.

**Brown–Forsythe test:** No significant difference in variability.

**Conclusion:**  
Across all tests, the frequency of earthquakes with M ≥ 4.5 does not differ significantly between the two decades.

**Important Note**
*This project analyses only the number of earthquakes above a fixed magnitude threshold.
It does not examine how earthquake magnitudes themselves may have changed.
Therefore, the results should not be interpreted as evidence about seismic intensity or the severity of natural hazards.*

**Files**
The repository contains the following components:

* notebook.ipynb – the full analysis including code, visualisations, and statistical tests

* analysis.pdf – an A5‑formatted export of the analysis showing outputs only (no code)

* analysis.html – an HTML version of the analysis showing outputs only

* data/ – a folder containing the reduced dataset used in the project
