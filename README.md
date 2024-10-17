# Body Fat Prediction Analysis - Group 10

This repository contains the code, data, and resources for the **Body Fat Prediction Analysis** project as part of STAT628. This project focuses on using various regression techniques to predict body fat percentage based on body measurements. It includes data preprocessing, model comparison, and a Shiny app for interactive prediction.

## Repository Structure

├── code/
│ ├── bodyfat.r # Main R script for data cleaning, modeling, and diagnostics
│ ├── app.r # Shiny app code for body fat prediction
│
├── data/
│ ├── BodyFat.csv # Raw body fat dataset
│ ├── data.csv # Cleaned and preprocessed data
│ ├── data_new.csv # Further processed data after model fitting
│
├── image/
│ ├── Residual_Plots.png # Residual plots for model diagnostics
│ ├── QQ_Plots.png # QQ plots for model diagnostics
│
├── 628report.pdf # Two-page summary report
├── STAT628 BODYFAT Project Group10.pdf # Full report
├── STAT628 BODYFAT Project Group10.pptx # Presentation slides

### Folders:

- `code/`: Contains the R scripts for data analysis (`bodyfat.r`) and the Shiny app (`app.r`).
- `data/`: Includes the raw and cleaned datasets used in the analysis.
- `image/`: Contains residual and QQ plots for model diagnostics.
- `628report.pdf`: The two-page summary of the project.
- `STAT628 BODYFAT Project Group10.pdf`: The full project report.
- `STAT628 BODYFAT Project Group10.pptx`: The presentation slides for the project.

## Shiny App Deployment

The Shiny app allows users to input body measurements and predict their body fat percentage.

https://andrewchanshiny.shinyapps.io/Bodyfat-Group10-P2-628/

#

### Model Diagnostics

- **Residual Plots**: Residual plots for different models are saved in the `image/Residual_Plots.png`.
- **QQ Plots**: QQ plots for checking the normality of residuals for different models are saved in the `image/QQ_Plots.png`.

### Model Comparison and Final Selection:

- Simple linear regression on individual predictors.
- Interaction terms between predictors.
- Stepwise regression for feature selection.

## Contact Information

For any questions or inquiries about the project, feel free to contact us:

- [zchen2353@wisc.edu](mailto:zchen2353@wisc.edu)
- [xdong95@wisc.edu](mailto:xdong95@wisc.edu)
- [xtang254@wisc.edu](mailto:xtang254@wisc.edu)
- [zwu535@wisc.edu](mailto:zwu535@wisc.edu)
