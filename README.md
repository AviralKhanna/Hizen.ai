# Project Title: E-Commerce Analytics and Prediction

This project performs comprehensive data analysis and predictive modeling using e-commerce event data. The workflow includes data preprocessing, exploratory data analysis (EDA), churn analysis, feature engineering, and machine learning model building.

## Prerequisites

Ensure the following tools and libraries are installed:

- Python 3.7+
- Jupyter Notebook or Google Colab
- Required Python libraries:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn lightgbm.
  ```

## File Structure

- **`Hizen_ai_Internship_Project.ipynb`**: The main notebook containing all code and analysis steps.
- **Data Files**: 
  - `events.csv`: Raw event data.
  - `cleaned_events.csv`: Preprocessed event data (generated during execution).

## Running the Notebook

### Step 1: Set Up the Environment

1. Upload the notebook (`Hizen_ai_Internship_Project.ipynb`) to Google Colab or open it in Jupyter Notebook.
2. If using Google Colab, mount your Google Drive to access data:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

### Step 2: Data Inspection and Preprocessing

1. Modify the `file_path` variable to point to the location of `events.csv` in your environment.
2. Execute the cells in the **Data Inspection & Preprocessing** section to load and clean the data.

### Step 3: Exploratory Data Analysis (EDA)

1. Run the cells in the **EDA** section sequentially to generate insights:
   - Event distributions
   - Brand and category popularity
   - User-level summaries
   - Other trends and patterns
2. Outputs such as graphs and statistics will be displayed inline.

### Step 4: Advanced Analysis

1. Perform analyses such as churn detection, behavioral clustering, and event funnels.
2. Update any necessary parameters (e.g., churn thresholds) as prompted in the notebook.

### Step 5: Feature Engineering

1. Execute the feature engineering section to create additional variables required for modeling.
2. Verify the transformed dataset before proceeding.

### Step 6: Model Training and Evaluation

1. Run the cells in the **Model Building and Training** section.
2. Evaluate different models and track improvements (e.g., accuracy from 47% to 82.2%).
3. Update hyperparameters or configurations as needed for further enhancements.

### Step 7: Save Outputs

1. Save generated datasets or visualizations using the provided file paths in the notebook.
2. Modify file paths if needed for your environment.

## Notes

- The notebook includes both intermediate and advanced steps. Follow the section descriptions carefully.
- For optimal performance, ensure the system has adequate computational resources (especially for clustering and model training).

## Contributing

Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.
