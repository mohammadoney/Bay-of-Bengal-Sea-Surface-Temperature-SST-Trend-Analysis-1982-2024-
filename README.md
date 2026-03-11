Data Acquisition & Processing:

Leveraged Google Earth Engine to process the NOAA OISST V2.1 dataset.

Built a pipeline to create monthly median composites and sampled ~27km pixels directly to a CSV.


Analysis Pipeline (Python):

Data Quality: Verified 100% spatial coverage across the entire 41-year record.

Pre-whitening: Detected significant serial correlation (Lag-1 ACF of 0.72), confirming the need for a modified approach.

Trend Detection: Applied the Yue & Wang (2004) modified Mann-Kendall test to account for autocorrelation.

Magnitude: Calculated the Theil-Sen slope to determine the robust rate of change.


Key Findings:

Basin-Wide Warming: The Bay of Bengal is warming at a statistically significant rate of 0.212°C per decade.

Statistical Confidence: This trend is highly robust (Yue-Wang p-value ≈ 0.0), with a 95% confidence interval of [0.147 to 0.276] °C/decade.

Spatial Patterns: Mapped the significant pixel-wise trends, highlighting regions of accelerated warming.

Sensitivity Check: A Jackknife analysis confirmed the trend is stable and not driven by any single anomalous year.
