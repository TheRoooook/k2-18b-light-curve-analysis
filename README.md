# K2-18b: Exoplanet Light-Curve Analysis

## About the Project

This project focuses on analysing the light curve of K2-18b, a sub-Neptune exoplanet orbiting an M-dwarf star.
The aim was to study its observed brightness variations, identify possible transit events, and estimate key 
planetary properties using established astrophysical equations.

I used real photometric data downloaded from the NASA Exoplanet Archive and carried out the data processing
and analysis using Microsoft Excel. The calculated parameters were then compared with published values to 
assess how closely the results agreed with existing measurements.

## Methodology

The analysis involved the following steps:

- Obtained the original photometric light-curve data from the NASA Exoplanet Archive.
- Organised and processed the data in Microsoft Excel.
- Applied normalisation, baseline processing, and detrending to examine the light curve.
- Plotted the original and processed data to study variations in stellar brightness and identify possible
   transit events.
- Used astrophysical equations to estimate the planet's radius, equilibrium temperature, and density.
- Compared the calculated values with published measurements of K2-18b.

The Excel workbook contains the structured data tables, calculations, processing steps, and graphs.
The project report explains the procedure, equations, assumptions, and results in greater detail.

## Files in This Repository

- `Original_L.C.D.tbl` — Original photometric light-curve data downloaded from the NASA Exoplanet Archive.
- `Final_LCD.xlsx` — Excel workbook containing the processed data, calculations, tables, and graphs.
- `K2-18b_data_latest.csv` — Reference data from the NASA Exoplanet Archive used for cross-checking.
- `Project_Report.pdf` — Detailed report covering the methodology, calculations, results, and scientific interpretation.

## Tools and Techniques

- Microsoft Excel
- Photometric data analysis
- Data normalisation and detrending
- Scientific data visualisation
- Astrophysical parameter estimation
- Comparison with published scientific measurements

## Data Source

NASA Exoplanet Archive: https://exoplanetarchive.ipac.caltech.edu/

The original light-curve observations were used for the analysis, while the separately downloaded
planetary-parameter data served as a reference for cross-checking the derived values.

## Additional References

The full bibliographic entries for two papers cited in the calculation sections were inadvertently
omitted from the reference list of the original submitted report. They are included here for completeness.

1. Sarkis, P., Henning, T., Kürster, M., et al. (2018).
 *The CARMENES search for exoplanets around M dwarfs: A low-mass planet in the temperate zone of
 the nearby K2-18.* The Astronomical Journal, 155, 257.

   - [Read the paper (NASA ADS/arXiv record)](https://arxiv.org/abs/1805.00830)
   - [Published paper (DOI)](https://doi.org/10.3847/1538-3881/aac108)

2. Kruse, E., Agol, E., Luger, R., & Foreman-Mackey, D. (2019). *Detection of Hundreds of New Planet
 Candidates and Eclipsing Binaries in K2 Campaigns 0–8.* The Astrophysical Journal Supplement Series, 244(1), 11.

   - [Read the paper on arXiv](https://arxiv.org/abs/1907.10806)
   - [Published paper (DOI)](https://doi.org/10.3847/1538-4365/ab346b)

Note: The correct spelling is “Kruse et al. (2019)”; “Kreus et al. (2019)” in the original report is a typographical error.

## Conclusion

This project provided an opportunity to work with real astronomical observations and apply data processing,
visualisation, and astrophysical calculations to study a known exoplanet. Comparing the derived parameters 
with published values helped assess their consistency with existing measurements.

The results depend on the adopted reference parameters, data-processing methods, and underlying assumptions.
This is an independent analysis of an already known exoplanet, rather than a claim of a new discovery.
