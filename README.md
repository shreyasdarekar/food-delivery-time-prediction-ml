# Food Delivery Time Prediction Using Machine Learning

A machine-learning mini project comparing five regression algorithms to estimate food delivery duration in minutes.

## Algorithms
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regression (SVR)

## Files
- `Food_Delivery_Time_Prediction.ipynb` — Google Colab/Jupyter notebook for preprocessing, EDA, training, evaluation and saving outputs.
- `requirements.txt` — Python dependencies.
- `data/` — place the chosen dataset here if running locally.
- `outputs/` — generated results from the notebook.
- `report/` — college report document.

## Run in Google Colab
1. Open https://colab.research.google.com/
2. Select **File → Upload notebook** and upload the notebook.
3. Run cells from top to bottom.
4. Upload your CSV when prompted.
5. Set `TARGET_COLUMN` to the exact column name for actual delivery duration in minutes.
6. Check all metrics and plots, then use those actual results in the report.

If no CSV is uploaded, the notebook generates synthetic demonstration data so the workflow can be tested. **Do not present synthetic-demo results as real-world findings.** Before final submission, use a documented public dataset and record its source and license.

## Metrics
- **MAE (minutes):** average absolute prediction error; lower is better.
- **RMSE (minutes):** penalizes larger errors; lower is better.
- **R²:** goodness-of-fit metric; values closer to 1 are generally better, but it can be negative.

## Dataset
After selecting the final dataset, record its exact name, publisher, source URL, access date and license here. Ensure the target column and features match the notebook. Do not claim live delivery-platform integration unless implemented.

## Limitations
Predictions depend on dataset quality and features available at prediction time. This is not a live tracking system and does not guarantee a delivery time.

## Author
- Name: Shreyas Darekar
- Roll No.: CS3134
- Class: TY Div A
- Course: Machine Learning
- Academic Year: 2026–27
