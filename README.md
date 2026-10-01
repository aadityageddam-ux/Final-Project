# Final Project: PhenoAge analysis of U.S. adults (PUBH 1142)

`final_project.ipynb` is the final project for PUBH 1142, Introduction to Health Data Science (George Washington University, May 2025). It is a cross-sectional analysis of NHANES 1999-2000 using the Phenotypic Age (PhenoAge) formula from Levine et al. 2018 to compare biological and chronological age from standard clinical biomarkers.

The notebook describes its data as the NHANES 1999-2000 cycle, read directly from CDC files at run time (demographics and laboratory files), and uses pandas, numpy, scipy, statsmodels, seaborn and matplotlib.

## Status and limits

- This is a student course project from my first year, not a validated clinical tool.
- I have not re-run the notebook end to end from a clean environment since submission. There is no pinned environment, so results may differ with library versions.
- Later work on the same calculation is in [phenoage-calc](https://github.com/aadityageddam-ux/phenoage-calc) (tested library) and [labage](https://github.com/aadityageddam-ux/labage), which fix problems this version does not handle (for example explicit CRP units).
