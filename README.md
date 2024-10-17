# Body Fat Prediction Analysis - Group 10

This repository contains the code, data, and resources for the **Body Fat Prediction Analysis** project as part of STAT628. This project focuses on using various regression techniques to predict body fat percentage based on body measurements. It includes data preprocessing, model comparison, and a Shiny app for interactive prediction.

### Folders:

- `code/`: Contains the R scripts for data analysis (`bodyfat.r`) and the Shiny app (`app.r`).
- `data/`: Includes the raw and cleaned datasets used in the analysis.
- `image/`: Contains residual and QQ plots for model diagnostics.
- `628report.pdf`: The two-page summary of the project.
- `STAT628 BODYFAT Project Group10.pdf`: The full project report.
- `STAT628 BODYFAT Project Group10.pptx`: The presentation slides for the project.

## Installation and Usage

### Prerequisites

To run the code or Shiny app, ensure you have R and RStudio installed. You will also need the following R packages:
- `MASS`
- `car`
- `caret`
- `shiny`
- `ggplot2`

You can install these packages by running:
```r
install.packages(c("MASS", "car", "caret", "shiny", "ggplot2"))
```

### Running the Analysis

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/Andrewczcz/628-Group10-P2.git
   ```

2. **Run the analysis**:
   - Open the `bodyfat.r` file in RStudio.
   - Run the script to preprocess the data, remove outliers, and build various regression models. This script also generates model comparison and diagnostic plots.
   - The results will be output to the console.

3. **Model Comparison**: The script evaluates different models and computes metrics such as adjusted R-squared and Mean Squared Error (MSE) using 10-fold cross-validation.

## Shiny App Deployment

The Shiny app allows users to input body measurements (abdomen circumference, weight, and age group) and predict their body fat percentage.

### Running the Shiny App Locally

1. Open the `app.r` file in RStudio.
2. Click on the "Run App" button, or use the following command to run it in R:
   ```r
   shiny::runApp('path_to_app_directory')
   ```

Or you can click here: https://andrewchanshiny.shinyapps.io/Bodyfat-Group10-P2-628/

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
