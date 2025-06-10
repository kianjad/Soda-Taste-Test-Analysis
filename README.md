# Soda Taste Test Factorial Design with Blocking

This project investigates how subtle serving methods can influence the perception of soda taste. It explores the idea that taste is not solely about flavor, but also about the consumer's experience influenced by external factors like pouring and drinking methods.

## Experiment Design

The study was designed as a **blocked factorial experiment**.
* **Factors Investigated:**
    * **Pouring Method:** Comparing pouring soda straight into a glass versus pouring it down the side of the glass.
    * **Drinking Method:** Comparing drinking soda directly from the can versus drinking it through a straw.
* **Blocking:** The experiment likely utilized blocking to control for extraneous variability and enhance the precision of the results.

## Methodology & Analysis

To analyze the data and test for significant effects, the project applied a robust statistical approach:
* **Linear Modeling:** Used to model the relationship between the experimental factors and taste perception.
* **ANOVA (Analysis of Variance):** Employed to assess the significance of individual factors and their interaction effects on taste perception.
* **Permutation Tests:** Utilized to validate conclusions, especially when traditional ANOVA assumptions might have been violated, ensuring robust statistical inference.
* **Power Analysis & Sample Size Validation:** Power curves were built, and sample size analysis was conducted to confirm the experiment was well-powered to detect effects under moderate variability.

## Key Findings

The analysis demonstrated that **simple changes in pouring and drinking methods can significantly alter taste perception** for consumers. This supports the idea that the overall sensory experience of a beverage is influenced by external serving factors.

## How to Run the Code

1.  **Prerequisites:** Ensure you have R and RStudio installed.
2.  **R Packages:** Install the necessary R packages (e.g., `dplyr`, `ggplot2`, `lme4` for mixed models/blocking, `car` for `Anova`, `lmPerm` for permutation tests, etc.
3.  **Data:** soda_data.xlsx
4.  **Execute R Markdown:** Open the `.Rmd` file in RStudio and knit it to reproduce the analysis and generate the report.

## Technologies Used

* **R**
* **RStudio**
* **R Packages:** (e.g., `dplyr`, `ggplot2`, `lme4`, `car`, `lmPerm`, etc.
* **Markdown**

---

Kian Jadbabaei
