# Heart_disease_Prediction


1. Provide the Heart Disease Dataset:
- Place your `heart.csv` dataset in the project directory.
- Ensure the dataset follows the structure expected by the program.

2. Open and Run in RStudio:
- Open the project folder in RStudio.
- Install required packages if not already installed:
  ```r
  install.packages(c("shiny", "caret", "randomForest", "xgboost"))
  ```
- Open `app.R` and modify the dataset path if necessary:
  ```r
  heart <- read.csv("path/to/your/heart.csv")
  ```
- Run the Shiny application by executing:
  ```r
  shiny::runApp()
  ```

3. Use the Web Application:
- Access the application by opening your web browser and navigating to the provided URL.
- Input patient information and click "Predict" to obtain heart disease predictions from multiple models.

## Requirements

- R (version 3.5.0 or higher)
- RStudio (optional but recommended)
- Required R packages: `shiny`, `caret`, `randomForest`, `xgboost`
