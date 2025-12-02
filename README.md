This project analyzed over four decades of sea surface temperature data to detect and quantify long-term warming trends in the Bay of Bengal, using robust statistical methods to separate climate signals from seasonal cycles and natural variability.

Step-by-Step Process:

Data Acquisition & Preprocessing:
Monthly satellite-derived SST data from the NOAA OISST v2.1 dataset was extracted for the period 1982-2024.
The data was corrected using the scale factor (0.01) to convert from scaled integers to actual temperature in degrees Celsius.
Monthly median composites were created for each year-month combination to produce a continuous, gap-free time series.
Spatial averaging was performed over the entire Bay of Bengal region to create a single representative time series for the basin.

Time Series Decomposition (STL):
Seasonal-Trend decomposition using LOESS (STL) was applied to separate the raw SST data into three components:
Trend: The long-term, underlying climate signal.
Seasonal: The repeating annual cycle (higher in summer, lower in winter).
Residual: Random noise and short-term variability not explained by trend or seasonality.

Trend Detection & Quantification:
Mann-Kendall Test: A non-parametric statistical test was applied to the trend component to detect whether a monotonic (consistently upward or downward) trend exists. The test produced a Z-score and p-value.
Sen's Slope Estimator: This robust method calculated the actual rate of temperature change per month/year/decade, along with 95% confidence intervals to quantify uncertainty.

Pattern Identification & Real-World Interpretation:
The analysis revealed a statistically significant warming trend of 0.209°C per decade (or 0.90°C total over 43 years).
The Mann-Kendall test showed extremely strong significance (p ≈ 0.0000), confirming the trend is not due to random chance.
The seasonal component showed an expected annual cycle with ~3.5°C amplitude (warmer in summer months).
Residual variability was relatively low (0.197°C standard deviation), indicating the model effectively captured the main patterns.

Real-World Translation:
Climate Change Signal: The warming rate of ~0.21°C/decade aligns with global ocean warming trends but is specific to the Bay of Bengal. This represents a clear climate change signal in the region.

Ecological & Environmental Impacts:
Coral Bleaching Risk: Sustained warming increases thermal stress on coral reefs, making bleaching events more frequent and severe.
Marine Ecosystem Shifts: Warmer waters can alter species distributions, migration patterns, and breeding cycles.
Fisheries Productivity: Changes in temperature affect nutrient cycling and primary production, potentially impacting fish stocks.
Extreme Weather: Warmer sea surfaces can intensify cyclones and influence monsoon patterns through increased evaporation.
Regional Climate Context: The Bay of Bengal is a critical region for South Asian climate. This documented warming contributes to sea-level rise (through thermal expansion) and may influence rainfall patterns over adjacent landmasses.

Visualization & Validation:
A comprehensive six-panel figure was created showing:
1) Original data with trend overlay
2) Sen's slope with confidence intervals
3) Average seasonal cycle
4) Residual distribution
5) Decadal averages
6) Statistical summary

Additional verification using Kendall's tau correlation confirmed the robustness of findings.
