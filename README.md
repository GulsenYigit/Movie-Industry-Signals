## Folder Structure

```plaintext
The-Movie-Industry/
├── data/                          # Raw input data (ignored by Git)
├── gen/
│   ├── output/                    # Final plots and regression results
│   └── temp/                      # Temporary files (ignored by Git)
├── src/                           # R scripts and Makefile
│   ├── Makefile                   # Reproducible workflow
│   ├── 01_preprocess.R
│   ├── 02_feature_engineering.R
│   ├── 03_modeling.R
│   ├── 04_analysis.R
│   ├── 05_robustness_movie_year.R
│   ├── 06_robustness_lead_actor.R
│   └── 07_robustness_outliers_removed.R  
├── .gitignore
└── README.md

```


---

## Reproducibility

Navigate to the src folder and run:

```bash
cd src
make
```
---
