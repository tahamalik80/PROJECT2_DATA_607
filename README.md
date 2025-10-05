# IS 607 – Project 2: Tidying and Analyzing Wide Data

## Overview

This project is for IS 607 Project 2 and focuses on practicing data preparation and transformation with "wide" datasets for downstream analysis. The assignment emphasizes the importance of data tidying, transformation, statistical inference, and clear, reproducible reporting.

## Project Goals

- **Select and use three wide-format datasets** (excluding the instructor's sample), each with at least 50 entries.
- **Create .csv files** for each dataset in a wide structure.
- **Tidy and transform each dataset** in R using the `tidyverse` (`tidyr`, `dplyr`).
- **Handle missing or malformed data** transparently with imputation or removal, and clearly document your approach.
- **Perform the requested analyses** for each dataset, including at least one inferential statistical test.
- **Visualize results with error bars/confidence intervals** and provide clear, descriptive captions and narrative at each step.
- **Document your entire workflow** with detailed explanations, analysis, and conclusions in an R Markdown file.
- **Publish your work** on both GitHub and RPubs for reproducibility and grading.

## File Structure

```
├── student_scores.csv        # Wide-format dataset: student test scores (50+ rows)
├── patient_vitals.csv        # Wide-format dataset: hospital patient vitals (50+ rows)
├── country_demo.csv          # Wide-format dataset: country demographic/economic stats (50+ rows)
├── tidying_and_analyzing_wide_data.Rmd   # Main R Markdown analysis file
└── README.md                 # This file
```

## Instructions

For each of the three datasets:
1. **CSV Creation:**  
   - Prepare a wide-format `.csv` file with at least 50 entries, mirroring the structure shown in the discussion items.
2. **Data Tidying and Transformation:**  
   - Read the `.csv` into R.
   - Use `tidyr` and `dplyr` to tidy the data (e.g., `pivot_longer()`) and perform necessary transformations.
   - Identify and treat missing or malformed data using imputation or appropriate handling.
3. **Analysis & Visualization:**  
   - Perform descriptive analysis (means, SDs, etc.), and at least one inferential test (paired t-test or repeated measures ANOVA).
   - Visualize results using plots with error bars or confidence intervals.
   - Include clear narrative explanations and captions for each step and plot.
4. **Reporting:**  
   - All code, outputs, and narrative explanations should be included in the `.Rmd` file.
   - Clearly explain your data cleaning, analysis, and interpretation at each step.
